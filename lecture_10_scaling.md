# Skalning, upp och ut

*Lektion 10 av 12, torsdag den 1:a oktober 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 90% klar
* Lektionsteori: 80% klar
* Bakgrunds litteratur: 50% klar
* Uppgifter: 30% klar

Målet med denna lektion är att lära hur man kan få sin lösning till att skala antigen upp, ut eller båda och. Så att den klara av lasten. Detta hänger också ihop med vilken arkitektur man har valt på sin lösning.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 08:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Uppsamling från förra lektion (Monitorering av moln applikatione)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 09:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Skalning, upp och ut
* 09:30 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>Frivilliga Buddy övningar / SpacePark-projekt

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/>[SpacePark-standup](project_standup.md)
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Availability, Redudancy and Resiliency

* Artikel (13 min): [Overview of the reliability pillar](https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/overview)
* Artikel (18 min): [Use geo-redundancy to design highly available applications](https://docs.microsoft.com/en-us/azure/storage/common/geo-redundant-design)
* Artikel (7 min): [Cloud Management: 5 Best Practices to Ensure Cloud Success](https://daydigital.com/cloud-management-best-practices)

## Scaling out and up

* Artikel (11 min): [Scaling Up vs. Scaling Out: What’s the Difference?](https://pagely.com/blog/scaling-up-vs-scaling-out/)
* Video (19 min): [Scaling Up and Out With Microsoft® Azure](https://www.youtube.com/watch?v=Oy32KEeREVI)
* Artikel (11 min): [The Ultimate Guide to Running Healthy Apps in the Cloud](https://azure.github.io/AppService/2020/05/15/Robust-Apps-for-the-cloud.html)

## Chaos engineering

* Artikel (5 min): [Chaos Engineering](https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/chaos-engineering)
* Video (53 min) [Principles of Chaos Engineering](https://www.youtube.com/watch?v=6ilMZqKdMMU)

## Azure

* Artikel (3 min): [What is Azure Load Balancer?](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
* Video (5 min) [How to create a load balancer](https://www.youtube.com/watch?v=-VMPzVoo5Nk)
* Video (18 min): [Autoscale on Azure App Services](https://www.youtube.com/watch?v=7SlUWlzpTS4)

**Total** (163 min):

- Artiklar: 7 stk, total 68 min
- Video: 3 stk, total 95 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 7 (sida 90 till 105) - High availability and redundancy
* Kapitel 8 (sida 106 till 123) - Load-balancing applications
* Kapitel 9 (sida 124 till 140) - Applications that scales

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

Artikel (7 min): [Cloud Scalability: Scale Up vs Scale Out](https://blog.turbonomic.com/blog/on-technology/cloud-scalability-scale-vs-scale)

Artikel (2 min): [Make all things redundant](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/redundancy)

Artikel (9 min): [Resiliency in the age of cloud services](https://www.networkworld.com/article/3238509/resiliency-in-the-age-of-cloud-services.html)

Artikel (14 min): [An introduction to High Availability Architecture](https://www.getfilecloud.com/blog/an-introduction-to-high-availability-architecture/)

## Chaos Engineering

* Artikel (x min): [Principles of chaos engineering](https://principlesofchaos.org/)
* ?Video (x min): [Dev Connect - Applying chaos engineering principles for building fault-tolerant applications](https://anz-resources.awscloud.com/anz-webinars-on-demand-developer/applying-chaos-engineering-principles-for-building-fault-tolerant-applications)
* (15 min) [Chaos Engineering — Part 1](https://medium.com/@adhorn/chaos-engineering-ab0cc9fbd12a) - **The art of breaking things purposefully**
* (9 min) [Chaos Engineering — Part 2](https://medium.com/@adhorn/chaos-engineering-part-2-b9c78a9f3dde) - Planning your first experiment
* (18 min) [Chaos Engineering — Part 3](https://medium.com/@adhorn/chaos-engineering-part-3-61579e41edd8) - Failure Injection — Tools and Methods.

### Chaos tools

* Webpage: [Chaos monkey](https://netflix.github.io/chaosmonkey/)

* Webpage: [Gremlin](https://www.gremlin.com/get-started/?ref=docs)

## Load balacer

Webpage: [Traefik](https://doc.traefik.io/traefik/)

## Azure 

Artikel (4 min): [Changes to load test functionality in Visual Studio and cloud load testing in Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/test/load-test/overview?view=azure-devops)

Artikel (2 min): https://docs.microsoft.com/en-us/azure/app-service/manage-scale-up

# Frivillia Buddy övningar

Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen

## Övning 1: Load testing

Artikel (12 min): [Load testing with Azure Pipelines](https://k6.io/blog/integrating-load-testing-with-azure-pipelines)

## Övning 2: Load balance VMs across availability zones

[Tutorial: Load balance VMs across availability zones with a Standard Load Balancer using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-load-balancer-standard-public-zone-redundant-portal)

