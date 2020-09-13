# Databaser i molnet

Lektion 5 av 12, måndag den 14:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 80% klar
* Lektionsteori: 30% klar
* Bakgrunds litteratur: 10% klar
* Uppgifter: 90% klar

Målet med denna lektion är att lära hur man kan spara strukturerat data i molnet (med utgångspunkt i Azure) i t.ex. en databas. Det kunna vara båda en SQL eller en no-SQL.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Helen + Uppsamling från förra lektion (Automatisering av bygg och release)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Databaser
* 10:00 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/> Uppstart av SpacePark-projekt
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

* Video (12 min): [AZ-900 Episode 12 | Database Services | Cosmos DB, SQL Database, Db for MySQL & PostgreSQL](https://www.youtube.com/watch?v=RqD4nMyBazU)
* Artikel (5 min): [Azure Databaser](https://azure.microsoft.com/sv-se/product-categories/databases/)
* Artikel (7 min) [Azure-databas för MariaDB](https://azure.microsoft.com/sv-se/services/mariadb/)
* Artikel (7 min) [Azure Cosmos DB](https://azure.microsoft.com/sv-se/services/cosmos-db/)
* Artikel (7 min) [Azure SQL Database](https://azure.microsoft.com/sv-se/services/sql-database/)
  * Artikel (7 min): [Azure SQL-hanterad instans](https://azure.microsoft.com/sv-se/services/azure-sql/sql-managed-instance/)

**Total**:

- Artiklar: 6 stk, total 33 min
- Video: 1 stk, total 12 min
- Total: 45 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 10 (sida 141 till 157) - CosmosDB, detta omhandlar enbart CosmosDB

# Bakgrundsmaterial

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## SQL Server

* Artikel (7 min): [What is DTU in Azure SQL Database and How to Figure Out How Much We Need](https://www.spotlightcloud.io/blog/what-is-dtu-in-azure-sql-database-and-how-much-do-we-need)
* Video (12 min): [Azure SQL Database Serverless](https://www.youtube.com/watch?v=2ykwUOfEPoU)
* Article (16 min): [Azure SQL Database serverless](https://docs.microsoft.com/en-us/azure/azure-sql/database/serverless-tier-overview)
* Video (30 min): [Azure SQL Database Tutorial](https://www.youtube.com/watch?v=BgvEOkcR0Wk)
* Video (6 min): [How to create an Azure SQL database](https://www.youtube.com/watch?v=p7X8lH_XMtI)

## MariaDb + MySQL

* Video (12 min): [Introduction to Azure Database for MySQL](https://www.youtube.com/watch?v=F66qd93h-1I)
* Video (35 min): [Azure Database for MariaDB](https://www.youtube.com/watch?v=FVG_l-ucS_U)

## Cosmos DB

* [Getting Started with Graph Databases in Azure Cosmos DB](https://towardsdatascience.com/getting-started-with-graph-databases-in-azure-cosmos-db-cbfbf708cda5)
* Video (31 min): [Azure Cosmos DB Tutorial | Globally distributed NoSQL database](https://www.youtube.com/watch?v=R_Fi59j6BMo)

# Buddy uppgifter

## Dagens blogg

* Ge minst två pris ekempler på vad det koster att ha en databas i Azure
* Skriv en tutorial vart ni tar utgångspunkt i övning 2
  * Hur ni lägger upp databasen med Azure CLI
  * Hur ser dom viktiga delar av eran EF applikation ut
  * Hur deployar ni den och får upp migrations automatisk
  * Skulle ni har en eller fler databas konfigurationer? Prod / dev?

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *05.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *05a.md*, *05b.md* etc.

# Övning 1: Databas pris

## Övning 1a: Databas i Azure

Ta fram prisen per månad för olika typer av databaser, använda [Azure Pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator) till att få fram olika priser på:

* SQL server
  * Serverless compute
  * Provisioned compute
  * Manged instance
* MariaDB
* MySQL
* CosmosDB

Ta fram priser för olika scenarier, data mängder, backup planer, lokationer etc.

# Övning 2: SQL server i Azure

## Övning 2a, Serverless SQL server via CLI

Starta en serveless SQL server instans i azure, använd Azure CLI

Hints:

* `az sql db create -g mygroup -s myserver -n mydb -e GeneralPurpose -f Gen5 -c 2 --compute-model Serverless --auto-pause-delay 120`
* [Use the Azure CLI to create a single database and configure a firewall rule](https://docs.microsoft.com/en-us/azure/azure-sql/database/scripts/create-and-configure-database-cli)
  * Svenska: [Använd Azure CLI för att skapa en enskild databas och konfigurera en brand Väggs regel](https://docs.microsoft.com/sv-se/azure/azure-sql/database/scripts/create-and-configure-database-cli)

## Övning 2b, SQL application

Skriv ett litet program som använder eran nya SQL server. Använd entity framework  code och migrations.

Ni kan evt ta en eksisterende applikation

I steg 1 få den att köra i en lokal **Docker** container mot eran Azure SQL databas

## Övning 2c, CD med DevOps och migrations

Configura CD med eran nya container i Azure DevOps och se till at när applikationen starter att alla migrations körs eran SQL databas på automatisk

Hints:

* [EntityFrameworkCore, code-first migrations in Azure DevOps](https://medium.com/vx-company/entityframeworkcore-code-first-migrations-in-azure-devops-b5eb845fce18)

# Extra övningar

## Extra: SQL server Pulumi

Konfigurera SQL server + databas med Pulumi

Hints:

* Pulumi reference: [SqlServer](https://www.pulumi.com/docs/reference/pkg/azure/sql/sqlserver/)
* [Azure App Service with SQL Database and Application Insights](https://github.com/pulumi/examples/blob/master/azure-cs-appservice/AppServiceStack.cs)

