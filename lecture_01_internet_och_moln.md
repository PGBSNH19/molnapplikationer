# Röda tråd: Internet och moln

Lektion 1 av 12, måndag den 30:e augusti 2020, online

Målet med denna lektion är komma igång igen efter sommaren.
Denna lektion är en uppstarts lektion, och introducera övergripande dom ämnen som dom kommande 12 lektioner kommer att bygga på. Det primäre mål i denne lektion är att bygga på eran kunskap från webutveckling backend, och börja prata om vad molnet är, vi kommer specifikt att jobba med **Azure**. 

>  Inget i molnet har ett värde för någon annan än den som använder det

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 Välkommen till Utveckling av moln baserade applikationer
* 9:00 Presentation av dagens teori: Internet och moln
* 10:00 Indelning av grupper
* 10:15 Buddy övnning + diskussion av dagens ämnen
* 11:15 Presentation av diskussion

Lunch 12:00 till 13:00

* 13:00 Programmeringsövning i grupp
* 16:00 Avslutning och frågor i klassen
* 16:30 Slut på lektion
	* Landing card

# Lektionsteori

*Detta är material (artiklar, videoer, blogs etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

[What Are Network Protocols?](https://www.lifewire.com/definition-of-protocol-network-817949)

Comic zine: [Networking! ACK!](https://jvns.ca/networking-zine.pdf) - by Julia Evans 

## DNS

En protokoll som gör att man kan använda enkla namn till att kontakta en server

* [What is a domain name?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)

## TCP/IP

En mycket använt protokoll, som är basen för webtrafik

* [The TCP/IP Reference Model](https://www.studytonight.com/computer-networks/tcp-ip-reference-model)
* [Network+/Standards/TCP/IP Model/Introduction](https://en.wikiversity.org/wiki/Network%2B/Standards/TCP/IP_Model/Introduction)

## HTTP

Den protokoll som webbläsare användare till att prata med webserveren, via TCP 

* [HTTP introduction](https://www.httpwatch.com/httpgallery/introduction/)
* [Introduction to HTTPS](https://https.cio.gov/faq/)
* [Introduction to HTTP/2](https://developers.google.com/web/fundamentals/performance/http2/)

## Cloud

> The cloud is hosting, made elastic with and API wrapped around it combined with flexible billing

* Video (5 min): [What are the Business Benefits of Cloud Computing, IaaS, PaaS and SaaS?](https://www.youtube.com/watch?v=whkyRvugqlM)
* [Different Types of Cloud Computing Service Models](https://www.bluepiit.com/blog/different-types-of-cloud-computing-service-models/)
  * [What is IaaS vs SaaS vs PaaS and XaaS: what’s the difference](https://medium.com/@vanshvarshney_/what-is-iaas-vs-saas-vs-paas-and-xaas-whats-the-difference-examples-ceadeee146e6)
* [Top cloud providers in 2020: AWS, Microsoft Azure, and Google Cloud, hybrid, SaaS players](https://www.zdnet.com/article/the-top-cloud-providers-of-2020-aws-microsoft-azure-google-cloud-hybrid-saas/)
* [Cloud Services Terminology Guide: Comparing AWS vs Azure vs Google](https://www.cloudhealthtech.com/blog/cloud-comparison-guide-glossary-aws-azure-gcp)

## Azure

* Video (40 min): [Five Azure services every developer should know](https://channel9.msdn.com/Events/Connect/Microsoft-Connect--2018/T190)
* 
* [Get started with Azure CLI](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli?view=azure-cli-latest)
* Video (9 min): [How to configure a new virtual machine with the Azure Portal](https://www.youtube.com/watch?v=z5J5MQkbqvE)
* Video (7 min): [How to create a virtual machine in Azure](

# Bakgrunds litteratur
*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## TCP/IP
* [Difference Between IPv4 and IPv6](https://techdifferences.com/difference-between-ipv4-and-ipv6.html)
* [IPv6 Addoption](https://www.akamai.com/uk/en/about/our-thinking/state-of-the-internet-report/state-of-the-internet-ipv6-adoption-visualization.jsp) - hur går det med att byta till IP6

## HTTP
* [Introduction to HTTP basics](http://www.ntu.edu.sg/home/ehchua/programming/webprogramming/http_basics.html)
* RFC 2616: [Hypertext Transfer Protocol -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)

### HTTP/2

* [HTTP/2](https://hpbn.co/http2/)

* RFC 7540: [Hypertext Transfer Protocol Version 2 (HTTP/2)](https://tools.ietf.org/html/rfc7540)

## DNS
* [An Introduction to DNS Terminology, Components, and Concepts](https://www.digitalocean.com/community/tutorials/an-introduction-to-dns-terminology-components-and-concepts)
* Video (31 min): [DNS introduction](https://www.youtube.com/watch?v=dl-C6cBoRg4)
  This video shows you practical examples of DNS in real time and includes Wireshark captures showing you actual DNS query and answer messages

## Cloud

* [Cloud computing](https://www.explainthatstuff.com/cloud-computing-introduction.html)
* Wikipedia: [Cloud computing](https://en.wikipedia.org/wiki/Cloud_computing)
* [Is the cloud really just someone else's computer?](https://www.techrepublic.com/article/is-the-cloud-really-just-someone-elses-computer/)
* [Stop saying the cloud is just someone else's computer - because it's not](https://www.zdnet.com/article/stop-saying-the-cloud-is-just-someone-elses-computer-because-its-not/)
* [Humor] [Silicon Valley - John's Work Routine (Season 1-5)](https://www.youtube.com/watch?v=rdYtuMnlu1I)

## The Internet

Link till [The end of the internet](http://hmpg.net/)

[How big is the internet?](https://starry.com/blog/inside-the-internet/how-big-is-the-internet)

## Azure

* [Get started guide for Azure IT operators](https://docsmsftpdfs.blob.core.windows.net/guides/azure/azure-ops-guide.pdf)

# Övning med buddy
## Telnet en webbserver

Det är möjligt att manuellt förbinda sig till en webbserver, och denna övning visar vad en webbläsare gör bakom det fina skalet.

Först måsta man se till att ha programvaran [Telnet](https://en.wikipedia.org/wiki/Telnet) aktiverat i Windows (borde vara aktiverat i Linux som standard). [Windows 10: Enabling Telnet Client](https://social.technet.microsoft.com/wiki/contents/articles/38433.windows-10-enabling-telnet-client.aspx)

Det är möjligt att testa detta med vilken som helst webbserver på nätet, StackOverflow är bara ett exempel:

Starta en kommandoprompt eller powershell, detta exempel kommer att starta telnet klienten och öppna en förbindelse till servern stackoverflow.com via port 80.
Skriv:

```
telnet stackoverflow.com 80
```

Skärmen blir blank, det betyder att du har förbindelse till servern och att du nu kan skicka kommandon till webserven, skriv så (du ser inte vad du skriver):
```
GET /questions HTTP/1.0
Host: stackoverflow.com
```
Och tryck *enter* två gångar (två tomma rader). Du borde nu få ett svar från servern (högst sannolikt ett HTTP status 301, **varför**?).

Testa med en websida efter eget val, och eventuellt att ändra på input till servern.

# Buddy diskussion

Ta fram prisen per månad för en virtuell server per, hos olika moln operatör.

* Azure: [Pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator)
* AWS: [Calculator](https://calculator.aws/)
* etc

Sammanhåll prisen med en eller fler hosting företag (svenska, nordiska eller inom EU).

Tanken är att servern ska köra en simple websida med en enkel databas, alt installerat på samma server. Kanske krävs 2 CPUs, 8GB RAM och 10 GB disk på en Linux server i Europa

Vad är för och nackdelar med cloud vs hosting?

# Mini-projekt i grupp

## Programmera en simple webbserver

Det är möjligt at .NET och .NET Core väldigt enkelt att programmera en egen webbserver. Denna övning handlar om att ta koden i exemplet under och lägga in det i en konsol applikation (och få det att bygga och funka).

[HttpListener Class](https://docs.microsoft.com/en-us/dotnet/api/system.net.httplistener?view=netcore-2.2)

När programmet är klart kan ni starta det med kommandon (beroende på hur ni har lagt upp projektet):
```
MinWebbserver.exe http://localhost:3000/
```
Nu kör webbservern lokalt på eran dator, och ni kan nu tillgå den med en vanlig webbläsare eller telnet :)
```
telnet localhost 3000
```

Ni borde få ett svar med:
```
GET / HTTP/1.0
Host: localhost
```

Testa eventuellt att bygga ut webbservern så att den kan svara på olika anrop eller läsa en fil från disk.

# Individuell uppgift

Detta är en förberedelse inför [lektion 2](lecture_02_iac_och_vm.md)

## Azure

Create an account at Azure and install the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows)

Browse around to get a feeling of the possibilities in Azure, but besides this you don't need to do anything.