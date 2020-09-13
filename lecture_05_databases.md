# Databaser i molnet

Lektion 5 av 12, måndag den 14:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 80% klar
* Lektionsteori: 30% klar
* Bakgrunds litteratur: 10% klar
* Uppgifter: 30% klar

Målet med denna lektion är att lära hur man kan spara strukturerat data i molnet (med utgångspunkt i Azure) i t.ex. en databas. Det kunna vara båda en SQL eller en no-SQL.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Helen + Uppsamling från förra lektion (Automatisering av bygg och release)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Databaser
* 10:00 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/> Uppstart av projekt 2
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Projekt 2
* 16:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

* Video (12 min): [AZ-900 Episode 12 | Database Services | Cosmos DB, SQL Database, Db for MySQL & PostgreSQL](https://www.youtube.com/watch?v=RqD4nMyBazU)
* Artikel (5 min): [Azure Databaser](https://azure.microsoft.com/sv-se/product-categories/databases/)
* Artikel (7 min) [Azure-databas för MariaDB](https://azure.microsoft.com/sv-se/services/mariadb/)
* Artikel (7 min) [Azure Cosmos DB](https://azure.microsoft.com/sv-se/services/cosmos-db/)
* Artikel (7 min) [Azure SQL Database](https://azure.microsoft.com/sv-se/services/sql-database/)
  * Artikel (): [Azure SQL-hanterad instans](https://azure.microsoft.com/sv-se/services/azure-sql/sql-managed-instance/)
* Video: [How to create an Azure SQL database](https://www.youtube.com/watch?v=p7X8lH_XMtI)

**Total**:

- Artiklar: 4 stk, total 42 min
- Video: 3 stk, total 18 min
- Total: 60 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 10 (sida 141 till 157) - CosmosDB, detta omhandlar enbart CosmosDB

# Bakgrundsmaterial

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

SQL Server

* Artikel (7 min):[What is DTU in Azure SQL Database and How to Figure Out How Much We Need](https://www.spotlightcloud.io/blog/what-is-dtu-in-azure-sql-database-and-how-much-do-we-need)
* Video (12 min): [Azure SQL Database Serverless](https://www.youtube.com/watch?v=2ykwUOfEPoU)
* Article: [Azure SQL Database serverless](https://docs.microsoft.com/en-us/azure/azure-sql/database/serverless-tier-overview)
* Video (30 min): [Azure SQL Database Tutorial](https://www.youtube.com/watch?v=BgvEOkcR0Wk)

MariaDb + MySQL

* Video (12 min): [Introduction to Azure Database for MySQL](https://www.youtube.com/watch?v=F66qd93h-1I)
* Video (35 min): [Azure Database for MariaDB](https://www.youtube.com/watch?v=FVG_l-ucS_U)

Cosmos DB

* [Getting Started with Graph Databases in Azure Cosmos DB](https://towardsdatascience.com/getting-started-with-graph-databases-in-azure-cosmos-db-cbfbf708cda5)

* Video (31 min): [Azure Cosmos DB Tutorial | Globally distributed NoSQL database](https://www.youtube.com/watch?v=R_Fi59j6BMo)

* 

  

# Buddy uppgifter

## Dagens blogg

Dagens blogg ska innehålla:

Skriv en tutorial men vart ni tar utgångspunkt i dissa övningar, lägg gärna till litet teori (vad är en pipeline etc).

* Hur ser ert setup ut?
* Vilka delar är i eran yaml pipeline fil

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *05.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *05a.md*, *05b.md* etc.

# Övning 1: SQL server i Azure

Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen

## Övning 1a

Starta en SQL server i azure och skriv ett litet program som använder denna, använd entity framework och migrations.

Ni kan evt ta en eksisterende applikation

Hints:

* [Använd Azure CLI för att skapa en enskild databas och konfigurera en brand Väggs regel](https://docs.microsoft.com/sv-se/azure/azure-sql/database/scripts/create-and-configure-database-cli)

* [EntityFrameworkCore, code-first migrations in Azure DevOps](https://medium.com/vx-company/entityframeworkcore-code-first-migrations-in-azure-devops-b5eb845fce18)

## Övning 1b

Starta SQL serveren med Pulumi

```csharp
class AppServiceStack : Stack
{
    public AppServiceStack()
    {
var resourceGroup = new ResourceGroup("appservice-rg");        
var username = config.Get("sqlAdmin") ?? "pulumi";
var password = config.RequireSecret("sqlPassword");
var sqlServer = new SqlServer("sql", new SqlServerArgs
    {
       ResourceGroupName = resourceGroup.Name,
       AdministratorLogin = username,
       AdministratorLoginPassword = password,
       Version = "12.0",
    });

var database = new Database("db", new DatabaseArgs
    {
        ResourceGroupName = resourceGroup.Name,
        ServerName = sqlServer.Name,
        RequestedServiceObjectiveName = "S0",
    });
    
    ConnectionString =
            {
                new AppServiceConnectionStringArgs
                {
                    Name = "db",
                    Type = "SQLAzure",
                    Value = Output.Tuple<string, string, string>(sqlServer.Name, database.Name, password).Apply(t =>
                    {
                        (string server, string database, string pwd) = t;
                        return
                            $"Server= tcp:{server}.database.windows.net;initial catalog={database};userID={username};password={pwd};Min Pool Size=0;Max Pool Size=30;Persist Security Info=true;";
                    }),
                },
            },
    }
    
[Output] public Output<string> ConnectionString { get; set; }
}
```

Source: [Azure App Service with SQL Database and Application Insights](https://github.com/pulumi/examples/blob/master/azure-cs-appservice/AppServiceStack.cs)

