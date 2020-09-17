# Webb applikationer i molnet

*Lektion 6 av 12, onsdag den 16:e september 2020*

Målet med denna lektion är titta på olika sätt att använda molnet (specifikt Azure) till att hosta en webbapplikation. Vi kommer även att titta på hur ens arkitektur påverkar vilka möjligheter man har.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Uppsamling från förra lektion (Databaser i molnet)
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Webbapplikationer i Azure
* 10:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Samling
* 13:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

Artikel (9 min): [Azure hosting recommendations for ASP.NET Core web apps](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/azure-hosting-recommendations-for-asp-net-web-apps)

## Azure Web Apps

* Artikel (4 min): [App Service overview](https://docs.microsoft.com/en-us/azure/app-service/overview)
* Video (7 min): [How to deploy a static web app](https://www.youtube.com/watch?v=H2MPsgujpNk)

## Azure Web Apps for containers

* Artikel (4 min): [Azure Web App for Containers, Part One](https://www.ais.com/azure-web-app-for-containers-part-one/)
* Video (15 min): [Azure Web App for Containers](https://www.youtube.com/watch?v=xnUOu-yPEzo)

## Microservices - Arkitektur

* Artikel (7 min): [Four Architecture Choices for Application Development in the Digital Age](https://www.ibm.com/cloud/blog/four-architecture-choices-for-application-development)
* Video (55 min): [Why You Should Care About Microservices](https://channel9.msdn.com/Events/dotnetConf/Focus-on-Microservices/Why-You-Should-Care-About-Microservices?ocid=player)

## Serverless - Arkitektur

* Video (11 min): [Build apps faster with Azure Serverless](https://www.youtube.com/watch?v=OnJt4qfsfOc)

* Artikel (6 min): [Serverless computing](https://azure.microsoft.com/en-us/overview/serverless-computing/)

**Total** (109 min):

- Artiklar: 4 stk, total 21 min
- Video: 4 stk, total 88 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 3 (sida 33 till 46) - Azure Web Apps
* Kapitel 21 (sida 317 till 332) - Serverless computing

# Bakgrundsmatrial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel serie (totalt 39 min): [The twelve factor app](https://12factor.net/) - a methodology for building software-as-a-service apps

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (10 min): [Azure Function v.s. Web App aka. Serverless v.s. PaaS](https://www.taztopia.com/single-post/2019/07/28/Azure-Function-vs-Web-App-aka-Serverless-vs-PaaS)

## Azure Web Apps

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (4 min): [Azure App Service Explained](https://www.youtube.com/watch?v=iSzez17lMuQ)

## Azure Web Apps for containers

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (8 min): [Run a custom container in Azure](https://docs.microsoft.com/en-us/azure/app-service/quickstart-custom-container?pivots=container-linux)

## Cloud native - Arkitektur

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (3 min): [Cloud Native Definition](https://github.com/cncf/toc/blob/master/DEFINITION.md)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (13 min): [5 principles for cloud-native architecture—what it is and how to master it](https://cloud.google.com/blog/products/application-development/5-principles-for-cloud-native-architecture-what-it-is-and-how-to-master-it)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (11 min): [5 steps to building a cloud-ready application architecture](https://techbeacon.com/enterprise-it/5-steps-building-cloud-ready-application-architecture)

## Serverless - Arkitektur

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>Kurs (491 min): Microsoft Learn: [Create serverless applications](https://docs.microsoft.com/en-us/learn/paths/create-serverless-applications/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (10 min): [Azure Functions](https://azure.microsoft.com/en-us/services/functions)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (6 min): [How to create a function app](https://www.youtube.com/watch?v=BEIZKCDElMs)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (3 min): [The new Azure Functions experience](https://www.youtube.com/watch?v=0bdT_9uOqkg)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (7 min): [How to monitor Azure Functions](https://www.youtube.com/watch?v=eVDZz8h0s00)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (19 min): [Build Your First Serverless Web Application on Azure](https://mikepfeiffer.io/blog/azure-serverless-101)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (8 min): [Running Azure Functions in a Docker Container: A Beginner’s Guide](https://medium.com/faun/running-azure-functions-in-a-docker-container-a-beginners-guide-f921c150eab4)

## Microservices - Arkitektur

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (13 min): [Microservice Architecture](https://microservices.io/patterns/microservices.html)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (37 min): [Microservices a definition of this new architectural term](https://martinfowler.com/articles/microservices.html)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (9 min), wikipedia: [Conway's law](https://en.wikipedia.org/wiki/Conway%27s_law)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (5 min): [What is a Monolith?](http://www.codingthearchitecture.com/2014/11/19/what_is_a_monolith.html)

# Buddy uppgifter

## Dagens blogg

* Ge minst två pris ekempler på vad det koster att ha en webb applikation i Azure
* Skriv en tutorial vart ni tar utgångspunkt i övning 2

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *06.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *06a.md*, *06b.md* etc.

# Övning 1: Website pris

## Övning 1a: Website i Azure

Ta fram prisen per månad för olika sätt att deploya en webbsida i Azure, använda [Azure Pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator) till att få fram olika priser på:

* Virtuell Maskin
* App Service
* Azure Container Instance
* Trafik

Hints:

* [Bandwidth Calculator](https://www.calculator.net/bandwidth-calculator.html)

# Övning 2: Website i Azure

Ni borde redan ha en docker container i ACR, deploy denna till App Service (istället för ACI) med Docker.

Hints:

* [Deploy and run a containerized web app with Azure App Service](https://docs.microsoft.com/en-us/learn/modules/deploy-run-container-app-service/)
* [Deploy an Azure Web App Container](https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp-on-container-linux?view=azure-devops&tabs=dotnet-core%2Cyaml)

# Övning 3: Azure functions

Följ denna tutorial och skåpa en Hallo World funktion: [Create your first function in Azure using Visual Studio](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-your-first-function-visual-studio)

Denna övning ska inte vara i eran blog.



