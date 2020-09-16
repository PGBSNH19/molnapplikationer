# Nätverk i molnet

Lektion 7 av 12, måndag den 21:a september 2020

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 0% klar
* Lektionsteori: 0% klar
* Bakgrunds litteratur: 0% klar
* Uppgifter: 0% klar

Målet med denna lektion är lära hur man i molnet (med utgångspunkt i Azure) kan bygga upp virtuella nätverk, så att man där igenom kan bygga komplexa lösningar och öka säkerheten.

## Lektionsplan

Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Klassråd (Helen) + Uppsamling från förra lektion (Webb applikationer i molnet)
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Säkerhets mekanismer
  * Nätverk i molnet
  * Enterprise bus
* 10:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter)

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Samling: SpacePark-projekt
* 13:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

Virtual networks are necessary to support communications between virtual machines. You can define subnets, custom IP address, DNS settings, security filtering, and load balancing.By using a VPN gateway or an ExpressRoute circuit, you can connect Azure virtual networks to your on-premises networks.

1. Azure Networking
   1. https://azure.microsoft.com/en-us/services/virtual-network/
   2. https://en.wikipedia.org/wiki/Virtual_private_cloud
   3. https://medium.com/awesome-azure/azure-vs-aws-difference-between-azure-virtual-network-vnet-and-aws-virtual-private-cloud-vpc-2e8debc3290e
   4. https://www.ibm.com/cloud/learn/vpc
   5. vnet https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/connectivity-architecture-overview
2. Teoretisk Sikkerhed
   1. HTTPS
   2. Firewalls
      1. https://medium.com/swlh/understanding-firewall-types-4a2869deb687
      2. https://medium.com/@neil.wilston123/firewall-in-network-security-2a98795fcac1
   3. VPN
      1. https://medium.com/@zicodeng/how-vpn-works-b7549dcc6ce4
3. Enterprise bus
   1. Azure Servicebus
   2. https://en.wikipedia.org/wiki/Enterprise_service_bus
   3. https://medium.com/@xaviergeerinck/an-introduction-to-message-brokers-9bd203b4ebbd
   4. https://www.youtube.com/watch?v=FRzMPqViwuY
   5. Don't use syncronius calls
   6. Use messeging

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 5 (sida 58 till 73) - Azure networking basics
* Kapitel 11 (sida 158 till 174) - Managing network traffic and routing
* Kapitel 21.2 (sida 322 till 325) - Azure messaging platforms

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

* https://www.youtube.com/watch?v=JQ6KhjU5Zsg
* TBD

# Buddy uppgifter

## Dagens blogg

* Ge minst två pris ekempler på vad det koster att ha en webb applikation i Azure
* Skriv en tutorial vart ni tar utgångspunkt i övning 2

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *06.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *06a.md*, *06b.md* etc.

# Övning 1:

Use IaC to set up at least two servers on a virtual network, only one of the having a public ip