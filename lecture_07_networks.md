# Nätverk i molnet

*Lektion 7 av 12, måndag den 21:a september 2020*

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
*Detta är material (artiklar, videor, bloggs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

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
* Video (12 min): [Private Cloud Rules](https://www.youtube.com/watch?v=Tzqy8lW0bk4)

### Networking in Azure

* Artikel (6 min): [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)
* Artikel (5 min): [What is Azure Private Link?](https://docs.microsoft.com/da-dk/azure/private-link/private-link-overview)

**Total** (104 min):

- Artiklar: 8 stk, total 60 min
- Video: 3 stk, total 43 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 5 (sida 58 till 73) - Azure networking basics
* Kapitel 11 (sida 158 till 174) - Managing network traffic and routing
* Kapitel 21.2 (sida 322 till 325) - Azure messaging platforms

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Enterprise service bus

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (15 min), wikipedia: [Enterprise service bus](https://en.wikipedia.org/wiki/Enterprise_service_bus)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (40 min): [Microservices + Events + Docker = A Perfect Trio](https://www.youtube.com/watch?v=sSm2dRarhPo)

### Azure Queue Storage

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (22 min): [Azure Queue Storage Tutorial](https://www.youtube.com/watch?v=JQ6KhjU5Zsg)

## Virtual Network

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (8 min): [Azure VPN gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (11 min): [Virtual Private Cloud (VPC)](https://www.ibm.com/cloud/learn/vpc)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (23 min): [Integrate your app with an Azure virtual network](https://docs.microsoft.com/en-us/azure/app-service/web-sites-integrate-with-vnet)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (12 min): [Azure vs AWS — Difference between Azure Virtual Network (VNet) and AWS Virtual Private Cloud (VPC)](https://medium.com/awesome-azure/azure-vs-aws-difference-between-azure-virtual-network-vnet-and-aws-virtual-private-cloud-vpc-2e8debc3290e)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (12 min): [Use virtual network service endpoints and rules for servers in Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/vnet-service-endpoint-rule-overview)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [How to create a cloud-based virtual network in Microsoft Azure](https://www.techrepublic.com/article/how-to-create-a-cloud-based-virtual-network-in-microsoft-azure/)

### Private Link in azure / Private PaaS

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [Azure Private Link for Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/private-endpoint-overview)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (12 min): [Azure Virtual Network Service Endpoints](https://www.youtube.com/watch?v=gxsitRRgylI)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (11 min): [Azure Private Endpoint & Private Link](https://www.youtube.com/watch?v=vVDql7IKneg)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (16 min): [How to connect and deliver services privately on Azure with Azure Private Link ](https://www.youtube.com/watch?v=AZ0iFcyPDkc)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (31 min): [Private connectivity to Azure PaaS services using Private Link](https://www.youtube.com/watch?v=aVFV1_ZwAEY)

# Buddy uppgifter

## Dagens blogg

* Skriv en blogg baserat på Övning 2

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *07.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *07a.md*, *07b.md* etc.

# Övning 1: Service bus

Följ denna tutorial för att skåpa en konsol applikation som använder Azure Service Bus : [Get started with Service Bus queues](https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues)

Denna övning ska **inte** vara i eran blog.

# Övning 2: Private link

*Denna övning är av teoretisk karaktär. Och resultat ska ni beskriva i eran blogg*

Ni jobbar i ett företag som har en intern applikation som ni gärna vill modernisera, denna interna applikation använder tillgång till interna server och resurser, och jobbar med klassificerade data som inte får öppet skickas via nätat, och därför är det i följa din CTO inte möjligt att använda en PaaS moln-lösning.

Ett viktigt punkt i modernisering är att implementera en enterprise bus, och ni vill gärna använda er av Azure Service Bus, men tyvär säger eran CTO säger "nej", på grund av data inte får skickas öppet.

Skriv (i eran blogg) ett argument till eran CTO som förklara och övertyga hen om att ni med hjälp av ett Azure Private Link kan använda Azure Service Bus i eran interna applikation. Förklara begrepp som Virtual Private Cloud i eran förklaring.

Om ni lyckas att övertyga eran CTO till att tillåta att ni använder Azure Service Bus, kommer ni i framtiden att kunna använda andra Azure PaaS tjänster (vilket gör livet som utvecklare mycket bättre) :-)

**Hints**:

* [Connect an on-premises network to a Microsoft Azure virtual network](https://docs.microsoft.com/en-us/microsoft-365/enterprise/connect-an-on-premises-network-to-a-microsoft-azure-virtual-network?view=o365-worldwide)