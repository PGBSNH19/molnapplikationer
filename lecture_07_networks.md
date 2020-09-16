# Nätverk i molnet

*Lektion 7 av 12, måndag den 21:a september 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 80% klar
* Lektionsteori: 80% klar
* Bakgrunds litteratur: 40% klar
* Uppgifter: 0% klar

Målet med denna lektion är lära hur man i molnet (med utgångspunkt i Azure) kan bygga upp virtuella nätverk, så att man där igenom kan bygga komplexa lösningar och öka säkerheten.

## Lektionsplan

Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Klassråd (Helen) + Uppsamling från förra lektion (Webb applikationer i molnet)
  * <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Enterprise bus / Service bus
  * Nätverk 
  * Virtual Private Cloud 
* 10:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter)

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/teams18.png" alt="Teams"/> Samling: SpacePark-projekt
* 13:15 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="C:/Github/molnapplikationer/assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Enterprise bus / Service bus

> Don't use syncronius calls, use messeging

* Artikel (3 min): [An introduction to Message Brokers](https://medium.com/@xaviergeerinck/an-introduction-to-message-brokers-9bd203b4ebbd)
* Video (26 min): [Azure Service Bus from the ground up](https://www.youtube.com/watch?v=FRzMPqViwuY)

## Nätverk

* Artikel (18 min): [Networking 101: Ethernet, LANs, and How They Work](https://www.makeuseof.com/tag/networking-101-ethernet-lans-work/)
* Artikel (12 min): [How VPN Works?](https://medium.com/@zicodeng/how-vpn-works-b7549dcc6ce4)

* Artikel (8 min): [Understanding Firewall Types](https://medium.com/swlh/understanding-firewall-types-4a2869deb687)

* Artikel (4 min): [Firewall in Network Security](https://medium.com/@neil.wilston123/firewall-in-network-security-2a98795fcac1)

## Virtual Private Cloud

>  Virtual networks are necessary to support communications between virtual machines. You can define subnets, custom IP address, DNS settings, security filtering, and load balancing.By using a VPN gateway or an ExpressRoute circuit, you can connect Azure virtual networks to your on-premises networks.

* Artikel (4 min), Wikipedia: [Virtual private cloud](https://en.wikipedia.org/wiki/Virtual_private_cloud)
* Video (5 min): [What is a Virtual Private Cloud?](https://www.youtube.com/watch?v=NbkPRn1mqlU)

### Networking in Azure

* Artikel (6 min): [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
* Artikel (5 min): [What is Azure Private Link?](https://docs.microsoft.com/da-dk/azure/private-link/private-link-overview)

**Total** (91 min):

- Artiklar: 8 stk, total 60 min
- Video: 2 stk, total 31 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 5 (sida 58 till 73) - Azure networking basics
* Kapitel 11 (sida 158 till 174) - Managing network traffic and routing
* Kapitel 21.2 (sida 322 till 325) - Azure messaging platforms

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Enterprise service bus

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (15 min), wikipedia: [Enterprise service bus](https://en.wikipedia.org/wiki/Enterprise_service_bus)

### Azure Service Bus

### Azure Queue Storage

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (22 min): [Azure Queue Storage Tutorial](https://www.youtube.com/watch?v=JQ6KhjU5Zsg)

## Virtual Network

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (11 min): [Virtual Private Cloud (VPC)](https://www.ibm.com/cloud/learn/vpc)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (23 min): [Integrate your app with an Azure virtual network](https://docs.microsoft.com/en-us/azure/app-service/web-sites-integrate-with-vnet)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (12 min): [Azure vs AWS — Difference between Azure Virtual Network (VNet) and AWS Virtual Private Cloud (VPC)](https://medium.com/awesome-azure/azure-vs-aws-difference-between-azure-virtual-network-vnet-and-aws-virtual-private-cloud-vpc-2e8debc3290e)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artiekl (12 min): [Use virtual network service endpoints and rules for servers in Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/vnet-service-endpoint-rule-overview)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [How to create a cloud-based virtual network in Microsoft Azure](https://www.techrepublic.com/article/how-to-create-a-cloud-based-virtual-network-in-microsoft-azure/)

### Private Link in azure

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [Azure Private Link for Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/private-endpoint-overview)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (16 min): [How to connect and deliver services privately on Azure with Azure Private Link ](https://www.youtube.com/watch?v=AZ0iFcyPDkc)

# Buddy uppgifter

## Dagens blogg

* Ge minst två pris ekempler på vad det koster att ha en webb applikation i Azure
* Skriv en tutorial vart ni tar utgångspunkt i övning 1

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *07.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *07a.md*, *07b.md* etc.

# Övning 1: Private link

