# Webb applikationer i molnet

Lektion 6 av 12, onsdag den 16:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 80% klar
* Lektionsteori: 20% klar
* Bakgrunds litteratur: 0% klar
* Uppgifter: 30% klar

Målet med denna lektion är titta på olika sätt att använda molnet (specifikt Azure) till att hosta en webbapplikation. Vi kommer även att titta på hur ens arkitektur påverkar vilka möjligheter man har.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Uppsamling från förra lektion (Databaser i molnet)
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Databaser
* 10:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Samling
* 13:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.

[Azure hosting recommendations for ASP.NET Core web apps](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/azure-hosting-recommendations-for-asp-net-web-apps)

* Azure Web Apps
  * https://azure.microsoft.com/en-us/services/app-service/web/
  * video 7 min How to deploy a static web app https://www.youtube.com/watch?v=H2MPsgujpNk
* Arkitektur
  * Micro services
  * https://www.ibm.com/cloud/blog/four-architecture-choices-for-application-development
  * https://cloud.google.com/blog/products/application-development/5-principles-for-cloud-native-architecture-what-it-is-and-how-to-master-it
  * https://techbeacon.com/enterprise-it/5-steps-building-cloud-ready-application-architecture
  * https://channel9.msdn.com/Events/dotnetConf/Focus-on-Microservices/Why-You-Should-Care-About-Microservices?ocid=player
* Serverless
  * https://azure.microsoft.com/en-us/services/app-service/api/
  * https://azure.microsoft.com/en-us/services/app-service/
  * https://azure.microsoft.com/en-us/services/functions
  * https://www.taztopia.com/single-post/2019/07/28/Azure-Function-vs-Web-App-aka-Serverless-vs-PaaS
  * https://azure.microsoft.com/en-us/solutions/serverless/#solutions
  * video 6 min How to create a function app https://www.youtube.com/watch?v=BEIZKCDElMs
  * video 3 min The new Azure Functions experience https://www.youtube.com/watch?v=0bdT_9uOqkg
  * video 7 min How to monitor Azure Functions https://www.youtube.com/watch?v=eVDZz8h0s00
  * Deploy to Azure Functions using Pulumi

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 3 (sida 33 till 46) - Azure Web Apps
* Kapitel 21 (sida 317 till 332) - Serverless computing

# Bakgrundsmatrial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

* https://12factor.net/
* TBD

# Buddy uppgifter

## Dagens blogg

* Ge minst två pris ekempler på vad det koster att ha en webb applikation i Azure
* Skriv en tutorial vart ni tar utgångspunkt i övning 2
  * 

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *06.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *06a.md*, *06b.md* etc.

# Övning 1: Website pris

## Övning 1a: Website i Azure

Ta fram prisen per månad för olika sätt att deploya en webbsida i Azure, använda [Azure Pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator) till att få fram olika priser på:

* Virtuell Maskin
* App Service
* Azure Container Instance
* Kubernetes

# Övning 2: Website i Azure

Deploy eran webb applikation till App Service med Docker

Docker

Kubernetes

# Extra övningar

## Extra: Kubernetes

## Extra: Web app med Pulumi

## 



