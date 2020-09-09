# Databaser i molnet

Lektion 5 av 12, måndag den 14:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 80% klar
* Lektionsteori: 10% klar
* Bakgrunds litteratur: 0% klar
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

* Artikel (5 min): [Azure Databaser](https://azure.microsoft.com/sv-se/product-categories/databases/)

* Artikel (7 min) [Azure-databas för MariaDB](https://azure.microsoft.com/sv-se/services/mariadb/)
* Artikel (7 min) [Azure Cosmos DB](https://azure.microsoft.com/sv-se/services/cosmos-db/)
* Artikel (7 min) [Azure SQL Database](https://azure.microsoft.com/sv-se/services/sql-database/)
* Video: [How to create an Azure SQL database](https://www.youtube.com/watch?v=p7X8lH_XMtI)

**Total**:

- Artiklar: 4 stk, total 42 min
- Video: 3 stk, total 18 min
- Total: 60 min

# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

* [What is DTU in Azure SQL Database and How to Figure Out How Much We Need](https://www.spotlightcloud.io/blog/what-is-dtu-in-azure-sql-database-and-how-much-do-we-need)

  

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

https://docs.microsoft.com/sv-se/azure/azure-sql/database/scripts/create-and-configure-database-cli

## Övning 1b

Starta SQL serveren med Pulumi

# Övning 2: Cosmos DB



