# Containrar

Lektion 3 av 12, måndag den 7:e september 2020

Målet med denna lektion är ge en introduktion till ämnet containrar. Där finns fler olika container system, men vi kommer att fokusera på **Docker**.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Uppsamling från förra lektion (Virtuelle maskiner och infrastruktur som kod)
  * <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Presentation av dagens teori: 
  * Containrar + Docker
  * Orchestration + Kubernetes
* 10:00 <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Lunch samling
* 13:30 <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/> [Buddy uppgifter](#Buddy uppgifter) försatt
* 16:00 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Avslutning och frågor i klassen
  * <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter. Detta är inte prioriterat eftersom allt är viktigt*

## Containrar

* Artikel (6 min): [WTF is a container?](https://techcrunch.com/2016/10/16/wtf-is-a-container)
* Video (7 min): [Why you should care about containers](https://www.youtube.com/watch?v=EUitQ8DaZW8)

### Docker

* Artikel (12 min): [What exactly is Docker?](https://medium.com/swlh/what-exactly-is-docker-1dd62e1fde38)
* Video (3 min) [How to get started with Docker on local dev machine](https://www.youtube.com/watch?v=Kx7mOgdr3Ro)
* Docker Tooling in Visual Studio; Docker and **.NET Core** 101:
  * Video (9 min): [What is Docker, Why use it?](https://www.youtube.com/watch?v=vmnvOITMoIg&list=PLdo4fOcmZ0oUvXP_Pt2zOgk8dTWagGs_P) (1 of 3)
  * Video (6 min): [Docker Tooling in Visual Studio](https://www.youtube.com/watch?v=k2sskhYEPkI&list=PLdo4fOcmZ0oUvXP_Pt2zOgk8dTWagGs_P)  (2 of 3) 
  * Video (3 min): [Publishing your Containerized Web App](https://www.youtube.com/watch?v=d7D0h9i-QCw&list=PLdo4fOcmZ0oUvXP_Pt2zOgk8dTWagGs_P)  (3 of 3)

## Orkestrering (Orchestration)

* Artikel (15 min), New Relic: [What Is Container Orchestration?](https://blog.newrelic.com/engineering/container-orchestration-explained/)
* Video (62 min) [Cloud Native .NET - Mark Rendle](https://www.youtube.com/watch?v=77Dk3vjVa9k)

### Kubernetes

* Video (6 min): [How Kubernetes works](https://www.youtube.com/watch?v=daVUONZqn88)

**Total**:

- Artiklar  3 stk, total 33 min
- Video: 7 stk, total 96 min
- Total: 129 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 19 (sida 284 till 299) - Azure containers

# Bakgrundsmaterial

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Containrar

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Computer Stuff They Didn't Teach You : [Containers? So What? Docker 101 Explained](https://www.youtube.com/watch?v=0oEsMwSxBsk)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>[5 Container Alternatives to Docker](https://containerjournal.com/topics/container-ecosystems/5-container-alternatives-to-docker/)

<span style="color:#7EAE42; font-weight: bolder; margin-right:0.5em;">&#9711;</span>Wikipedia: [OS-level virtualization](https://en.wikipedia.org/wiki/OS-level_virtualization)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>[Introducing GitHub Container Registry](https://github.blog/2020-09-01-introducing-github-container-registry/)

### Docker

<span style="color:#7EAE42; font-weight: bolder; margin-right:0.5em;">&#9711;</span>Wikipedia [Docker (software)](https://en.wikipedia.org/wiki/Docker_(software))

<span style="color:#E78E35; font-weight: bolder; margin-right:0.5em;">&#9651;</span>[21 Days of Docker](https://github.com/100daysofdevops/21_Days_of_Docker), en bra samling av artiklar

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Online kurs: [Docker for beginners](https://docker-curriculum.com/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[A quick introduction to Docker tags](https://www.freecodecamp.org/news/an-introduction-to-docker-tags-9b5395636c2a/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[Docker Desktop WSL 2 backend](https://docs.docker.com/docker-for-windows/wsl/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>[2018 Docker usage report](https://sysdig.com/blog/2018-docker-usage-report/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> ["Distroless" Docker Images](https://github.com/GoogleContainerTools/distroless)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Github: [DotNet Docker](https://github.com/dotnet/dotnet-docker)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> [Comparison: AWS Fargate vs. Google Cloud Run vs. Azure Container Instances](https://thenewstack.io/comparison-aws-fargate-vs-google-cloud-run-vs-azure-container-instances/)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (9 min) [Virtual Machines vs Docker Containers - Dive Into Docker](https://www.youtube.com/watch?v=TvnZTi_gaNc)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> [Where are Docker Images Stored? Docker Container Paths Explained](https://www.freecodecamp.org/news/where-are-docker-images-stored-docker-container-paths-explained/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel: [Exploring a Docker Container’s Filesystem](https://www.baeldung.com/ops/docker-container-filesystem)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (13 min): [Azure Container Instances (ACI) under the hood](https://www.youtube.com/watch?v=giQLmxMKAKE)

Video (14 min): [Pros and cons of stable and unique tags in Docker image tagging](https://www.youtube.com/watch?v=qEIu-nb-Yc0)

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>Kurs (310 min): Microsoft Learn: [Administer containers in Azure](https://docs.microsoft.com/en-us/learn/paths/administer-containers-in-azure/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel: [Dockerless - series](https://mkdev.me/en/posts/dockerless-part-1-which-tools-to-replace-docker-with-and-why)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel: [Docker, FROM scratch](https://codeburst.io/docker-from-scratch-2a84552470c8)

## Orchestration

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[Azure Container Orchestration 101: Azure Web Apps vs ACI vs AKS](https://www.dragonspears.com/blog/azure-container-orchestration-101-azure-web-apps-vs-aci-vs-aks)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (32 min), Computer Stuff They Didn't Teach You: [Kubernetes and Container Orchestration 101](https://www.youtube.com/watch?v=3RTvoI-A7UQ)

### Kubernetes
<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Online kurs (60 min): [Kubernetes 101](https://www.ibm.com/cloud/architecture/content/course/kubernetes-101/kubernetes-101)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[What is Kubernetes?](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[A Kubernetes story: Phippy goes to the zoo](https://www.youtube.com/watch?v=R9-SOzep73w)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>[Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (8 min): [Technically Speaking: Clayton Coleman on the History of Kubernetes](https://www.youtube.com/watch?v=zUJTGqWZtq0)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (7 min): [A conversation with Brendan Burns: What is Kubernetes?](https://www.youtube.com/watch?v=q1PcAawa4Bg)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (55 min) [Introduction to Microservices, Docker, and Kubernetes](https://www.youtube.com/watch?v=1xo-0gCVhTU)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (7 min): [How Kubernetes deployments work](https://www.youtube.com/watch?v=mNK14yXIZF4)

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>e-bok: [The Kubernetes Book](https://leanpub.com/thekubernetesbook)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>[Helm](https://helm.sh/) - The package manager for Kubernetes

# Buddy uppgifter

## Dagens blogg

Dagens blogg ska innehålla:

Skriv en tutorial i stil med dissa ([1](https://softchris.github.io/pages/dotnet-dockerize.html) eller [2](https://morioh.com/p/5414a74be39d)), men vart i stället ta utgångspunkt i dissa övningar, lägg gärna till litet teori (vad är en container etc).

* Vad har in installerat
* Hur har ni fått applikationen att kör i en container
* Vad innehåller ern Docker Compose
* Hur fick ni upp Containeren i Azure Container Instance
* Hur fick den den att funka i AKS

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *03.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *03a.md*, *03b.md* etc.

# Övning 1: Bygg en container

Vi har nu en webb applikation som vi vill gör om till en container, och i första vända kunna köra lokalt på vår dator, men i senare övningar få den at köra i molnet.

## Övning 1a: Hello World i Docker

**Mål med denna övning**: Bygg en container som kan hålla Hello World webb applikationen (samma om vi använda i förra lektion). Och få applikationen att köra i Docker, så att du kan komma åt den med webbläsare: localhost:80.

1. Installera Docker på din dator: [Get Docker](https://docs.docker.com/get-docker/)
2. Starta om din dator
3. Klona ner ["Hello world" .NET Core webb applikationen](https://github.com/skjohansen/SimpleWebHalloWorld) 
4. Lägg till en "Dockerfile"
   * Tutorial: [Getting Started With ASP.NET Core & Docker](https://morioh.com/p/5414a74be39d) 
   * Tutorial: [How YOU can Dockerize a .Net Core app](https://softchris.github.io/pages/dotnet-dockerize.html)
5. Bygg din container
6. Kör din container

Hints:

* Ni kan behöva att se över port mapningen
* Ni kan behöva att byta base-image i förhållande till tutorials
* Mindre kod ändringar kan behövas

Blogg:

* Se till att beskriva dom olika delar av container filen

## Övning 1b: Hello World med Docker Compose

Ni har nu en Docker container som innehåller vår Hello World applikation

**Mål med denna övning**: Gör en Docker compose fil som kan köra din nya Hello World-Docker container 

1. Skåpa en `docker-compose.yml` fil som beskivar hur eran docker container ska köras
	* [Get started with Docker Compose](https://docs.docker.com/compose/gettingstarted/)
	* [A Practical Introduction to Docker Compose](https://hackernoon.com/practical-introduction-to-docker-compose-d34e79c4c2b6)
2. Starta eran applikation med `docker-compose up`

Docker Compose är speciellt smidigt för lokala utvecklingsmiljö vart man har behov av flera containers (services) jobbar ihop i en applikation. I detta exempel är där endast en service så där finns inte ett jätte behov av en compose fil, men så fort applikationen växer blir den relevant.

**OBS**: Ni kommer inte att använda denna compose fil mer i denna övning

# Övning 2: Publicera Hello World container image

Ni har nu en Docker container som innehåller vår Hello World applikation (och en Docker Compose definition).

**Mål med denna övning**: Är att skåpa ett Docker image och publicera det till "Github packages" eller "Azure container registry". Ni väljer själv vilken av dom två system ni vill använda.

Hints:

* [Docker + GitHub Package Registry](https://medium.com/@sujaypillai/docker-github-package-registry-9e805f16feab)
* [Configuring Docker for use with GitHub Packages](https://docs.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-docker-for-use-with-github-packages)
* [Create a private container registry using the Azure CLI](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-azure-cli)
* Video (11 min): [Create a .Net Core Docker Container and Deploy it to Azure](https://www.youtube.com/watch?v=q8nXv56gWms) (denna video innehåller också en demo på hur man konfigurera en webservice detta ska ni såklart det bort ifrån)
* Video (22 min): [How to Deploy Containers cheaply to Azure](https://www.youtube.com/watch?v=2hokqjFr22s) (denna video rör fler olika ämnen så ta enbart dom delar som är relevanta för denna övning)

**OBS**: Detta behövs för att kunna hosta ert image på en annan maskin eller server (man måste kunna komma åt imaget från internet).

Ni kan nu testa att köra ert image via [Play with Docker](https://labs.play-with-docker.com/), beskriv också detta i eran blogg.

* Starta en ny instans
* Pull ert image från Github Package eller Azure Conatainer Registry
* Kör ert image och testa det

# Övning 3: Deploy och kör Hello World containrar

Ni har nu skåpat ett Docker image som ligger tillgängligt på internet (äntlig på Github eller Azure), och denna övning handlar om att få vår container att köra någon stans i molnet.

Där finns många sätt at få den att köra i Azure och vi kommer att träna två ACI och AKS. Vart AKS är det mer avancerade variant. 

## Övning 3a: Azure Container Instance (ACI)

**Mål med denna övning**: är att deploy ert docker image till ACI. ACI använder man primärt till projekt vart containern ska leva i kort tid, och därför är det bra för vår experiment.

Artikel (3 min): [What is Azure Container Instances?](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)

Hints:

* Tutorial (6 min): [Deploy a container instance in Azure using the Azure CLI](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart)
* Tutorial (3 min): [Authenticate with Azure Container Registry from Azure Container Instances](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-auth-aci)
* Video (7 min) : [How to use Azure Container Instance (ACI)](https://www.youtube.com/watch?v=hvvWtsYCObU)
* Video (21 min): [Azure Container Instances Tutorial ; Serverless containers in cloud](https://www.youtube.com/watch?v=jAWLQFi4USk)
* Kurs (48 min): [Run Docker containers with Azure Container Instances](https://docs.microsoft.com/da-dk/learn/modules/run-docker-with-azure-container-instances/)

# Övning 4

## Övning 4a, Bygg ett API med Docker

* Skåpa ett web api, för att göra alt så enkelt som möjligt gör ett API som inte behöver någon data (databas, disk etc.)
* Se till att Hello World använder detta API (ett anrop räcker)
* Gör en container till det nya web api
  * En container ska enbart innehålla en applikation
* Testa den nya container för sig själv
* Ändra eran Docker compose så att den startar båda applikationer 

Hints:

* Tutorial (4 min): [Create a multi-container app with Docker Compose](https://docs.microsoft.com/en-us/visualstudio/containers/tutorial-multicontainer?view=vs-2019)
* Tutorial (22 min): [Building a .NET Core API, host it in Azure  Container Instances from a private Container Registry and enable HTTPS  using Application Gateway](https://zimmergren.net/azure-container-instances-dotnet-core-api-application-gateway-https/)

## Övning 4b, Publicera ert API image

Publicera containern med ert nya API

## Övning 4c, Deploy och kör eran applikation

Se till att båda eran Hello World sida och eran API ligger i ACI

# Extra övningar

Dissa är extra övningar ni kan göra om ni har tid över, de kan göras i den ordning ni känner för

## Extra till övning 3, ACI med Pulumi

Som ni kanske har känt kräver det mycket kommandon med CLI eller klick i portalen att få sina Docker images att köra i ACI

**Målet med denna övning** är att automatisera alla dissa kommandon/klick med Pulumi.

Hints:

* Pulumi tutorial: [Deploy to Azure Container Instance (ACI)](https://www.pulumi.com/docs/tutorials/azure/container-webserver/)

## Extra övning 5: Kubernetes och AKS

Ni har nu två containrar (Web + API), det är fortfarrent en liten applikation, men kan redan nu börja att få njuta av att använda Kubernetes till att "konfigurera" hela applikationen (API + web). 

**Mål med denna övning** är att ork­estr­era era Docker containrar med Kubernetes på AKS

Hints:

* Video (6 min): [Using Azure Container Instances w/Azure Container Registry, Azure Container Service and Kubernetes](https://www.youtube.com/watch?v=W6YmZPSqEsk)

* Video (57 min): [Kubernetes-Getting Started with Azure Container Service AKS](https://www.youtube.com/watch?v=dPJKGnEXQIM)

## Extra till övning 5, AKS med Pulumi

**Målet med denna övning** är att automatisera konfigurationen av AKS med Pulumi.

Hints:

* Tutorial: [Azure Kubernetes Service (AKS) with Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/aks/)



