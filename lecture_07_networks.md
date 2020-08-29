# Nätverk i molnet

Lektion 7 av 12, måndag den 21:a september 2020

![Draft](/assets/images/draft.png)

Målet med denna lektion är lära hur man i molnet (med utgångspunkt i Azure) kan bygga upp virtuella nätverk, så att man där igenom kan bygga komplexa lösningar och öka säkerheten.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* x

Lunch 12:00 till 13:00

* x

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

Virtual networks are necessary to support communications between virtual machines. You can define subnets, custom IP address, DNS settings, security filtering, and load balancing.By using a VPN gateway or an ExpressRoute circuit, you can connect Azure virtual networks to your on-premises networks.

1. Azure Networking
   1. https://azure.microsoft.com/en-us/services/virtual-network/
   2. https://en.wikipedia.org/wiki/Virtual_private_cloud
   3. https://medium.com/awesome-azure/azure-vs-aws-difference-between-azure-virtual-network-vnet-and-aws-virtual-private-cloud-vpc-2e8debc3290e
   4. https://www.ibm.com/cloud/learn/vpc
2. Teoretisk Sikkerhed
   1. HTTPS
   2. Firewalls
      1. https://medium.com/swlh/understanding-firewall-types-4a2869deb687
      2. https://medium.com/@neil.wilston123/firewall-in-network-security-2a98795fcac1
   3. VPN
      1. https://medium.com/@zicodeng/how-vpn-works-b7549dcc6ce4
3. Servicebus
   1. Don't use syncronius calls
   2. Use messeging

## 





# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

* TBD
* TBD

# Exemplar och övningar. 

Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen

Use IaC to set up at least two servers on a virtual network, only one of the having a public ip