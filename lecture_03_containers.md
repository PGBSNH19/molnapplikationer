# Containrar

Lektion 3 av 12, måndag den 7:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 95% klar
* Lektionsteori: 95% klar
* Bakgrunds litteratur: 75% klar
* Uppgifter: 60% klar

Målet med denna lektion är ge en introduktion till ämnet containrar. Där finns fler olika container system, men vi kommer att fokusera på **Docker**.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Klassråd m. Helen
* 8:45 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Uppsamling från förra lektion (Internet och moln)
  * <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:30 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Presentation av dagens teori: Containrar + Docker
* 10:00 <img style="margin-right:0.5em;" src="assets\images\discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets\images\teams18.png"/> Presentation av dagens teori: Orchestration + Kubernetes
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

## Orchestration

* Artikel (15 min), New Relic: [What Is Container Orchestration?](https://blog.newrelic.com/engineering/container-orchestration-explained/)
* Video (62 min) [Cloud Native .NET - Mark Rendle](https://www.youtube.com/watch?v=77Dk3vjVa9k)

### Kubernetes

* Video (6 min): [How Kubernetes works](https://www.youtube.com/watch?v=daVUONZqn88)

**Total**:

- Artiklar  3 stk, total 33 min
- Video: 7 stk, total 96 min
- Total: 129 min

# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Containrar

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span> [5 Container Alternatives to Docker](https://containerjournal.com/topics/container-ecosystems/5-container-alternatives-to-docker/)

<span style="color:#7EAE42; font-weight: bolder; margin-right:0.5em;">&#9711;</span> Wikipedia: [OS-level virtualization](https://en.wikipedia.org/wiki/OS-level_virtualization)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>[Introducing GitHub Container Registry](https://github.blog/2020-09-01-introducing-github-container-registry/)

### Docker

<span style="color:#7EAE42; font-weight: bolder; margin-right:0.5em;">&#9711;</span>Wikipedia [Docker (software)](https://en.wikipedia.org/wiki/Docker_(software))

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span> [Docker Desktop WSL 2 backend](https://docs.docker.com/docker-for-windows/wsl/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>[2018 Docker usage report](https://sysdig.com/blog/2018-docker-usage-report/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> ["Distroless" Docker Images](https://github.com/GoogleContainerTools/distroless)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Github: [DotNet Docker](https://github.com/dotnet/dotnet-docker)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> [Comparison: AWS Fargate vs. Google Cloud Run vs. Azure Container Instances](https://thenewstack.io/comparison-aws-fargate-vs-google-cloud-run-vs-azure-container-instances/)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (9 min) [Virtual Machines vs Docker Containers - Dive Into Docker](https://www.youtube.com/watch?v=TvnZTi_gaNc)

## Orchestration

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[Azure Container Orchestration 101: Azure Web Apps vs ACI vs AKS](https://www.dragonspears.com/blog/azure-container-orchestration-101-azure-web-apps-vs-aci-vs-aks)

### Kubernetes

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Online kurs (60 min): [Kubernetes 101](https://www.ibm.com/cloud/architecture/content/course/kubernetes-101/kubernetes-101)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>[What is Kubernetes?](https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>[Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (8 min): [Technically Speaking: Clayton Coleman on the History of Kubernetes](https://www.youtube.com/watch?v=zUJTGqWZtq0)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (7 min): [A conversation with Brendan Burns: What is Kubernetes?](https://www.youtube.com/watch?v=q1PcAawa4Bg)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (55 min) [Introduction to Microservices, Docker, and Kubernetes](https://www.youtube.com/watch?v=1xo-0gCVhTU)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span> Video (7 min): [How Kubernetes deployments work](https://www.youtube.com/watch?v=mNK14yXIZF4)

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>e-bok: [The Kubernetes Book](https://leanpub.com/thekubernetesbook)

# Buddy uppgifter

## Dagens blogg

Dagens blogg ska innehålla:

Skriv en tutorial i stil med dissa ([1](https://softchris.github.io/pages/dotnet-dockerize.html) eller [2](https://morioh.com/p/5414a74be39d) ), men vart i stället ta utgångspunkt i dissa övningar, lägg gärna till litet teori (vad är en container etc).

* Vad har in installerat
* Hur har ni fått applikationen att kör i en container
* Vad innehåller ern Docker Compose
* Hur fick ni upp Containeren i Azure Container Instance
* Hur fick den den att funka i AKS

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

## Övning 1: Hello World i Docker

**Mål med denna övning**: Bygg en conatiner som kan hålla Hello World webb applikationen (samma om vi använda i förra lektion). Och få applikationen att köra i Docker, så att du kan komma åt den med webbläsare: localhost:80.

1. Installera Docker på din dator: [Get Docker](https://docs.docker.com/get-docker/)
2. Starta om din dator
3. Klona ner ["Hello world" .NET Core webb applikationen](https://github.com/skjohansen/SimpleWebHalloWorld) 
4. Lägg till en "Dockerfile"
   1. Tutorial: [Getting Started With ASP.NET Core & Docker](https://morioh.com/p/5414a74be39d) 
   2. Tutorial: [How YOU can Dockerize a .Net Core app](https://softchris.github.io/pages/dotnet-dockerize.html)
5. Bygg din container
6. Kör din container

Hints:

* Ni kan behöva att se över port mapningen
* Ni kan behöva att byta base-image i förhållande till tutorials

## Övning 2: Hello World med Docker Compose

Gör en Docker container som innehåller en Hello World webb applikation få den att köra med Docker Compose

[Get started with Docker Compose](https://docs.docker.com/compose/gettingstarted/)

[Introduction to Docker Compose](https://www.baeldung.com/docker-compose)

[A Practical Introduction to Docker Compose](https://hackernoon.com/practical-introduction-to-docker-compose-d34e79c4c2b6)

[Play with Docker](https://labs.play-with-docker.com/) - A simple, interactive and fun playground to learn Docker

## Övning 3: Azure Container Instance (ACI)

>  Deploy ert docker image till ACI med Pulumi

Artikel (3 min): [What is Azure Container Instances?](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)

* Tutorial (3 min): [Deploy a container instance in Azure using the Docker CLI](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart-docker-cli)
* Video (21 min): [Azure Container Instances Tutorial ; Serverless containers in cloud](https://www.youtube.com/watch?v=jAWLQFi4USk)

Tutorial: [Deploy to Azure Container Instance (ACI)](https://www.pulumi.com/docs/tutorials/azure/container-webserver/)

Video (11 min) [Create a .Net Core Docker Container and Deploy it to Azure](https://www.youtube.com/watch?v=q8nXv56gWms)

## Övning 4: Kubernetes + AKS

> Orcestra ern Docker container med AKS

Tutorial: [Azure Kubernetes Service (AKS) with Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/aks/)