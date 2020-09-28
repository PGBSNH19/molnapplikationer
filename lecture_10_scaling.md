# Skalning, upp och ut

*Lektion 10 av 12, torsdag den 1:a oktober 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 90% klar
* Lektionsteori: 20% klar
* Bakgrunds litteratur: 10% klar
* Uppgifter: 5% klar

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

* Load balancing (networking)
  * [What is Azure Load Balancer?](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
  * (Video 4 min) [How to create a load balancer](https://www.youtube.com/watch?v=-VMPzVoo5Nk)
* https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/redundancy
* https://docs.microsoft.com/en-us/azure/storage/common/geo-redundant-design
* https://blog.mycloudit.com/5-must-know-facts-about-microsoft-azure
* https://daydigital.com/cloud-management-best-practices
* https://www.networkworld.com/article/3238509/resiliency-in-the-age-of-cloud-services.html
* https://www.getfilecloud.com/blog/an-introduction-to-high-availability-architecture/

## Scaling out and up

* https://www.youtube.com/watch?v=Oy32KEeREVI
* https://blog.turbonomic.com/blog/on-technology/cloud-scalability-scale-vs-scale
* https://pagely.com/blog/scaling-up-vs-scaling-out/
* https://azure.github.io/AppService/2020/05/15/Robust-Apps-for-the-cloud.html

## Chaos engineering

* (5 min) https://docs.microsoft.com/en-us/azure/architecture/framework/resiliency/chaos-engineering
* Video (53 min) [Principles of Chaos Engineering](https://www.youtube.com/watch?v=6ilMZqKdMMU)

## Azure

mm

**Total** (0 min):

- Artiklar: 0 stk, total 0 min
- Video: 0 stk, total 0 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 7 (sida 90 till 105) - High availability and redundancy
* Kapitel 8 (sida 106 till 123) - Load-balancing applications
* Kapitel 9 (sida 124 till 140) - Applications that scales

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Chaos Engineering

* [Principles of chaos engineering](https://principlesofchaos.org/)
* https://anz-resources.awscloud.com/anz-webinars-on-demand-developer/applying-chaos-engineering-principles-for-building-fault-tolerant-applications
* (15 min) [Chaos Engineering — Part 1](https://medium.com/@adhorn/chaos-engineering-ab0cc9fbd12a) - **The art of breaking things purposefully**
* (9 min) [Chaos Engineering — Part 2](https://medium.com/@adhorn/chaos-engineering-part-2-b9c78a9f3dde) - Planning your first experiment
* (18 min) [Chaos Engineering — Part 3](https://medium.com/@adhorn/chaos-engineering-part-3-61579e41edd8) - Failure Injection — Tools and Methods.

Tools:

* Webpage: [Chaos monkey](https://netflix.github.io/chaosmonkey/)

* https://www.gremlin.com/get-started/?ref=docs

## Load balacer

https://doc.traefik.io/traefik/

## Azure 

https://docs.microsoft.com/en-us/azure/app-service/manage-scale-up

# Frivillia Buddy övningar

Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen

https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-load-balancer-standard-public-zone-redundant-portal