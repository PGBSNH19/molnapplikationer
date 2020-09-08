# Automatisering av bygg och release

Lektion 4 av 12, onsdag den 9:e september 2020

Målet med denna lektion är att lära hur man kan automatisera sina bygg och release (med utgångspunkt i Azure DevOps). 

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"/> Uppsamling från förra lektion (Containrar)
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"/> Presentation av dagens teori: 
  * Automatiserat release
  * Azure DevOps
* 10:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"/> Klassråd m. Helen + Samling i klassen
* 13:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> [Buddy uppgifter](#Buddy uppgifter) försatt
* 16:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Continuous Integration

* Video (6 min): [What is Continuous Integration?](https://www.youtube.com/watch?v=1er2cjUq1UI)
* Artikel (8 min): Extreme Programming Practice: [Continuous Integration](https://explainagile.com/agile/xp-extreme-programming/practices/continuous-integration/)
* Artikel (14 min): [Continuous Integration (CI) Explained](https://semaphoreci.com/continuous-integration)

## Continuous Deployment / Delivery

* Artikel (6 min): [What is Software Deployment](https://www.goodfirms.co/glossary/software-deployment/)
* Artikel (10 min): [Continuous Delivery and Continuous Deployment](https://circleci.com/blog/a-brief-history-of-devops-part-iv-continuous-delivery-and-continuous-deployment/)
* Video (6 min): [Continuous Deployment vs Continuous Delivery](https://www.youtube.com/watch?v=LNLKZ4Rvk8w)

## DevOps

* Video (6 min): [What is DevOps?](https://www.youtube.com/watch?v=UbtB4sMaaNM)
* Artikel (15 min): [A beginner's guide to building DevOps pipelines with open source tools](https://opensource.com/article/19/4/devops-pipeline)

**Total** (71 min):

- Artiklar: 5 stk, total 53 min
- Video: 3 stk, total 18 min

# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Continuous Integration

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (6 min): [What is Proper Continuous Integration?](https://semaphoreci.com/blog/2017/03/02/what-is-proper-continuous-integration.html)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel: [Why We Need Continuous Integration](https://semaphoreci.com/community/tutorials/continuous-integration)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel: Martin Fowler: [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html)

## Continuous Deployment / Delivery

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (13 min): [CI/CD Pipeline: A Gentle Introduction](https://semaphoreci.com/blog/cicd-pipeline)

## DevOps

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (9 min): [The Eight Phases of a DevOps Pipeline](https://medium.com/taptuit/the-eight-phases-of-a-devops-pipeline-fda53ec9bba)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>[The Feedback Loop: How to Adapt to Constant Change](https://circleci.com/blog/the-feedback-loop-how-to-adapt-to-constant-change/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[DORA](https://www.devops-research.com/research.html): Accelerate [State of DevOps 2019](https://services.google.com/fh/files/misc/state-of-devops-2019.pdf)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Puppet: [2019 State of DevOps Report](https://puppet.com/resources/report/state-of-devops-report/)

## Azure DevOps

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (52 min): [Deploying anything to Azure with Azure DevOps ](https://www.youtube.com/watch?v=L1Ra1qXv79k)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel + Video (5 min + 2 min): [What is Azure DevOps?](https://www.devopsgroup.com/insights/resources/tutorials/all/what-is-azure-devops/)

### Pipelines

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (2 min): [What is Azure Pipelines?](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines?view=azure-devops)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Tutorial (4 min): Microsoft [DevOps build and deploy image](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/build-image?view=azure-devops)

# Buddy uppgifter

## Dagens blogg

Skriv en tutorial vart ni tar utgångspunkt i dissa övningar, lägg gärna till litet teori (vad är en pipeline etc).

* Vilka steg har ni gått igenom?
* Vilka delar är i eran pipeline definition (yaml-fil)?
* Är ert bygg-jobb i containern eller ni definierat ett eget i DevOps?

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *04.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *04a.md*, *04b.md* etc.

# Övning 1: CI pipeline i Azure DevOps

Hints för 1a + 1b:

* Artikel: [Get started with Azure DevOps CLI](https://docs.microsoft.com/en-us/azure/devops/cli/?view=azure-devops)
* Artikel: [Create your first pipeline](https://docs.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline?view=azure-devops&tabs=net%2Cyaml%2Cbrowser%2Ctfs-2018-2)
* Tutorial (5 min): [Deploy to an Azure Web App for Containers](https://docs.microsoft.com/en-us/azure/devops/pipelines/apps/cd/deploy-docker-webapp?view=azure-devops&tabs=dotnet-core)
* Artikel (7 min): [How to create and configure Azure DevOps Pipelines Agent](https://itnext.io/how-to-create-and-configure-azure-devops-pipelines-agent-88848763f109)
* Tutorial (10 min): [Continuous integration and deployment](https://docs.microsoft.com/en-us/aspnet/core/azure/devops/cicd?view=aspnetcore-3.1)

## Övning 1a: Bygg

1. Konfigurera en bygg-pipeline i Azure for ett Github projekt.
   * Ni kan använda ett tidigare webprojekt eller bygga på ett par enhetstestar på [Hallo World](https://github.com/skjohansen/SimpleWebHalloWorld)
   * Om ni använder Hallo World, bör ni forka repoet så att ni kan få med en DevOps yaml-fil i repoet samt en Dockerfile
2. Konfigurera så att alla enhets tests körs som en del av byggen

## Övning 1b: Trigger på bygg

1. Konfigurera byggen så att den köras till vi varje push till Github
   * Det göras med en [trigger](https://docs.microsoft.com/en-us/azure/devops/pipelines/repos/github?view=azure-devops&tabs=yaml#ci-triggers) i DevOps
2. Sätt en build-sticker på ert Github projekt, så alla kan se status på projektet

# Övning 2: CD pipeline i Azure DevOps

Hints för 2a + 2b:

* Artikel: [Build and push to Azure Container Registry](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/acr-template?view=azure-devops)
* Artikel: [Configure CI/CD for Azure Container Instances using Azure / Azure DevOps Pipelines](https://mohitgoyal.co/2018/11/01/configure-ci-cd-for-azure-container-instances-using-azure-azure-devops-pipelines/)
* Video: [Build, Run, & Continuously Deploy Docker Containers to Azure App Service](https://www.youtube.com/watch?v=O5aXcmKc1HU) exempel med en nodes app

## Övning 2a

1. Se till att ett Docker image är output av ditt CI byggen
   * Evt kan man bygga Docker imaget efter CI bygget, så att det inte tar tid ifrån CI bygget
2. Push denna container från DevOps till Azure Container Registry (ACR) efter varje byggen, med en ny tag för varje varje bygg
   * En naturlig tag är: Build Id

## Övning 2b
Skåpa en release pipeline som deployer din webb app till ACI (eller en App Service) från ACR

# Extra övningar

*Dissa är extra övningar ni kan göra om ni har tid över, de kan göras i den ordning ni känner för*

## Extra: Kubernetes

Få Kubernetes (AKS) till att kontrollera en image in ACI.

Hints:

* Artikel: [Deploying your first Kubernetes app with Azure DevOps](https://info.acloud.guru/resources/deploy-kubernetes-app-with-azure-devops)

* Tutorial (15 min) [Using Azure DevOps to setup a CI/CD pipeline and deploy to Kubernetes](https://cloudblogs.microsoft.com/opensource/2018/11/27/tutorial-azure-devops-setup-cicd-pipeline-kubernetes-docker-helm/)

* Video (25 min): [CI-CD for Azure Kubernetes Service AKS using Azure DevOps](https://www.youtube.com/watch?v=K4uNl6JA7g8)

## Extra: Pulumi

Skåpa en Pumumi CI / CD pipeline som konfigurera upp din ACI / App Service

Hints:

* Artikel: [CI/CD Made Easy with Pulumi and Azure Pipelines](https://www.pulumi.com/blog/cd-made-easy-with-pulumi-and-azure-pipelines/)