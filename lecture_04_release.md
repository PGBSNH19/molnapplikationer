# Automatiserat release

Lektion 4 av 12, onsdag den 9:e september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 0% klar
* Lektionsteori: 30% klar
* Bakgrunds litteratur: 30% klar
* Uppgifter: 40% klar

Målet med denna lektion är att lära hur man kan automatisera sina bygg och release (med utgångspunkt i Azure DevOps). 

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* x

Lunch 12:00 till 13:00

* x

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Continuous Integration

* Video (6 min) [What is Continuous Integration?](https://www.youtube.com/watch?v=1er2cjUq1UI)
* Extreme Programming Practice: [Continuous Integration](https://explainagile.com/agile/xp-extreme-programming/practices/continuous-integration/)

## Continuous Deployment / Delivery

[What is Software Deployment](https://www.goodfirms.co/glossary/software-deployment/)

Video (6 min): [Continuous Deployment vs Continuous Delivery](https://www.youtube.com/watch?v=LNLKZ4Rvk8w)

## DevOps

* Video (6 min): [What is DevOps?](https://www.youtube.com/watch?v=UbtB4sMaaNM)
* [A beginner's guide to building DevOps pipelines with open source tools](https://opensource.com/article/19/4/devops-pipeline)

## Azure DevOps

### Pipelines

[What is Azure Pipelines?](https://docs.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines?view=azure-devops)

### Deployment

* Artikel (15 min) [Tutorial: Using Azure DevOps to setup a CI/CD pipeline and deploy to Kubernetes](https://cloudblogs.microsoft.com/opensource/2018/11/27/tutorial-azure-devops-setup-cicd-pipeline-kubernetes-docker-helm/)

* Video (25 min): [CI-CD for Azure Kubernetes Service AKS using Azure DevOps](https://www.youtube.com/watch?v=K4uNl6JA7g8)

# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

* <span style="color:#7EAE42; font-weight: 900;">&xcirc;</span> [2019 State of DevOps Report](https://puppet.com/resources/report/state-of-devops-report/)
  * Accelerate [State of DevOps 2019](https://services.google.com/fh/files/misc/state-of-devops-2019.pdf)
* [How to create and configure Azure DevOps Pipelines Agent](https://itnext.io/how-to-create-and-configure-azure-devops-pipelines-agent-88848763f109)
* [Continuous integration and deployment](https://docs.microsoft.com/en-us/aspnet/core/azure/devops/cicd?view=aspnetcore-3.1)
* Microsoft [DevOps build and deploy image](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/build-image?view=azure-devops)
* [Deploy to an Azure Web App for Containers](https://docs.microsoft.com/en-us/azure/devops/pipelines/apps/cd/deploy-docker-webapp?view=azure-devops&tabs=dotnet-core)
* https://www.youtube.com/watch?v=L1Ra1qXv79k

# Exemplar och övningar

*Detta är övningar som du äntligen gör själv, i grupp eller tillsammans med hela klassen*

Se till att ni har ett webb projekt med som definarat med en Docker container och som kan köras i AKS

## CI pipeline

1. Konfigurera en bygg-pipeline i Azure for ett Github projekt.

2. Konfigurera så att alla enhets tests körs som en del av byggen

3. Konfigurera byggen så att den köras till vi varje push till github

4. Sätt en build-sticker på ert Github projekt

   

## CD pipeline

1. Push din container (output av fin CI pipeline) till Azure Container Registry eller Github Container Registry
   1. [Build and push to Azure Container Registry](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/containers/acr-template?view=azure-devops)
   2. [Getting started with GitHub Container Registry](https://docs.github.com/en/packages/getting-started-with-github-container-registry)
2. Skåpa en release pipeline som deployer din webb app till Azure AKS

* [CI/CD Made Easy with Pulumi and Azure Pipelines](https://www.pulumi.com/blog/cd-made-easy-with-pulumi-and-azure-pipelines/)
* [Deploying your first Kubernetes app with Azure DevOps](https://info.acloud.guru/resources/deploy-kubernetes-app-with-azure-devops)

https://www.youtube.com/watch?v=O5aXcmKc1HU







