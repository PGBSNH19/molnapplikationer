# Virtuelle maskiner och infrastruktur som kod

Lektion 2 av 12, onsdag den 2:a september 2020

Målet med denna lektion är komma på gång att använda virtuella maskiner och infrastructure as code (IaC).

Där finns fler olika IaC system, men vi kommer att fokusera på det system som hettar **Pulumi**.

Ni kommer att jobba med virtuelle Linux maskiner, så om du är osäker på Linux kolla bakgrunds litteraturen. Anledningen till detta är att Linux typ är standard OS i molnen.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 Uppsamling från förra lektion (Internet och moln)
  * Bording card
* 9:00 Presentation av dagens teori: Virtuelle maskiner och infrastruktur som kod
* 9:30 [Buddy uppgifter](#Buddy uppgifter) + blogg review

Lunch 12:00 till 13:00

* 13:00 Status på buddy uppgifterna
* 13:30 [Grupp övningar](#Grupp övningar) 
* 16:00 Avslutning och frågor i klassen
* 16:30 Slut på lektion
  * Landing card

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Virtual machines

* Beginner Geek: [How to Create and Use Virtual Machines](https://www.howtogeek.com/196060/beginner-geek-how-to-create-and-use-virtual-machines/)

## Infrastructure as Code

* Video (4 min): [Infrastructure as code](https://www.youtube.com/watch?v=z-caqPtEw58)
* Definition of [infrastructure as code](https://searchitoperations.techtarget.com/definition/Infrastructure-as-Code-IAC)

### Pulumi

* Video (32 min): [Managing any Cloud with .NET](https://www.youtube.com/watch?v=hXhZiHtT8f0)
* Video (11 min): On.NET [Getting started with cloud deployments with Pulumi and .NET](https://www.youtube.com/watch?v=sig68daTG-0) 
* Pulumi: [Get Started with Azure](https://www.pulumi.com/docs/get-started/azure/)

# Bakgrunds litteratur

*Detta är litteratur som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Virtual machines

* Wikipedia: [Virtual machine](https://en.wikipedia.org/wiki/Virtual_machine)

## Infrastructure as Code

* [What is Azure Resource Manager?](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview)
* Martin Fowler: [Blue Green Deployment](https://martinfowler.com/bliki/BlueGreenDeployment.html)
* [5 Blue/Green Deployment Best Practices to Improve Your Releases](https://blog.inedo.com/blue-green-deployment-best-practices)

## Pulumi

[Use Pulumi to Create and Provision an Azure VM for IoT Edge (Node.js)](https://geoffhudik.com/tech/2020/05/03/use-pulumi-to-create-and-provision-an-azure-vm-for-iot-edge/)

## Terraform

Annat ramverk till att göra IaC

- [Pulumi vs. Terraform](https://www.pulumi.com/docs/intro/vs/terraform/)

- [How Pulumi Compares to Terraform for Infrastructure as Code](https://blog.kylegalbraith.com/2018/12/21/how-pulumi-compares-to-terraform-for-infrastructure-as-code/)

- [Using Terraform in Azure DevOps Pipelines PART 2](https://www.youtube.com/watch?v=x631jUw1J04)

## Linux

*Getting started with Linux*

* [Linux: A Survival Guide for Beginners](https://medium.com/better-programming/linux-survival-guide-for-beginners-c18bfd982036)
* [Windows Subsystem for Linux Installation Guide for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
  * [Upgrading to WSL 2](https://medium.com/@callback.insanity/upgrading-to-wsl-2-9883688fcfa5)
  * [Trying the New WSL 2](https://scotch.io/bar-talk/trying-the-new-wsl-2-its-fast-windows-subsystem-for-linux)
* Ryans Tutorials: [Linux Tutorial](https://ryanstutorials.net/linuxtutorial/)
* [Get started with VS Code using C# and .NET Core on Ubuntu](https://channel9.msdn.com/Blogs/dotnet/Get-started-with-VS-Code-Csharp-dotnet-Core-Ubuntu)
  * [Install .NET Core SDK or .NET Core Runtime on Ubuntu](https://docs.microsoft.com/da-dk/dotnet/core/install/linux-ubuntu)
* Create an SSH key
  * [Powershell](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement)
  * [Linux](https://confluence.atlassian.com/bitbucketserver/creating-ssh-keys-776639788.html)

# Buddy uppgifter

## Dagens blogg

Dagens blogg ska innehålla:

* Eran SWAT analys
* En övergripande beskrivningen av hur ni fick en Virtuell maskin att köra med Azure CLI
* En detaljerat beskrivning av eran Pulumi lösning
* Beskriv en lösning till hur man kan har kod versions kontroll utan att man behöver att checka-in hemliga informationer som API-keys och passwords
* Kolla vilka resurser som skåpas i Azure när man gör en virtuell maskin, vad är skillnad på dom olika typer. 

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

## Diskussion

Gör en [SWAT analys](https://blogg.pwc.se/foretagarbloggen/guide-till-en-vinnande-swot-analys) på en virtuell maskin mot en fysik maskin, ha följande i åtanke:

* Hastighet
* Säkerhet
* Stabilitet
* Kostnad

## Få en virtuell maskin att köra lokalt på eran dator

Ladda ner ett VM image, t.ex. en Ubuntu från [osboxes.org](https://www.osboxes.org/ubuntu/) samt en matchande hypervisor t.ex. Oracle [VirtualBox](https://www.virtualbox.org/).

* Skåpa en ny virtuell maskin i VirtualBox
* Lägg till den disk (VM image) som du precis har laddad ner
* Starta maskinen

Få en "Hello world" .NET Core webb applikation att köra på ert VM.

[Host ASP.NET Core on Linux with Nginx](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/linux-nginx?view=aspnetcore-3.1)

[Install .NET Core SDK or .NET Core Runtime on Ubuntu v18.04](https://docs.microsoft.com/da-dk/dotnet/core/install/linux-ubuntu#1804-)

* Installera båda SDK och Runtime

Klona test appilkationen

`git clone https://github.com/skjohansen/SimpleWebHalloWorld.git`

Starta den med .NET

`dotnet run`

## Azure virtual machine

Skåpa en virtuell maskin på dissa tre sätt, logg in och kör igång ["Hallo world" .NET Core webb applikationen](https://github.com/skjohansen/SimpleWebHalloWorld) att köra på ert VM.

1. Set up a virtual linux machine using the Azure Web Portal
   - Video (9 min): [How to configure a new virtual machine with the Azure Portal](https://www.youtube.com/watch?v=z5J5MQkbqvE)
   - Video (7 min): [How to create a virtual machine in Azure](https://www.youtube.com/watch?v=rOiSRkxtTeU)
   - Nice to have: [How to SSH into an Azure VM from Windows Terminal Menu](https://www.thomasmaurer.ch/2020/05/how-to-ssh-into-an-azure-vm-from-windows-terminal-menu/)
   - [Hosting ASP.NET Core Web Application On Azure Linux VM](https://midnightprogrammer.net/post/hosting-aspnet-core-web-application-on-azure-linux-vm/)
2. Install a linux virtual machine using the Azure CLI
   - [Create a Linux virtual machine with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli)
   - [Tutorial: Create and Manage Linux VMs with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-vm)
   - Video (7 min): [How to create a virtual machine in Azure](https://www.youtube.com/watch?v=rOiSRkxtTeU)
3. Create a virtual machine in Azure using Pulumi (använd C#/.NET)
   * [Web Server Using Azure Virtual Machine](https://github.com/pulumi/examples/tree/master/azure-cs-webserver), 

För Pulumi projektet se till att pusha det till github, ni får ett github classroom projekt ni ska använda, akta att ni inte checker in lösenord etc.

### Webb applikation

För att köra webb applikationen följ dissa steg

`git clone https://github.com/skjohansen/SimpleWebHalloWorld.git`

`dotnet run --urls http://0.0.0.0:5000` (0.0.0.0 gör att webbläsaren lystnare på alla IP adresser)

Testa med din webbläser på din egen dator om du kan öppna sidan: *http://x.x.x.x:5000* (ersätt x.x.x.x med ditt VMs IP) 

För att kunna komma åt port 5000 måste man [öppna för denna](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/nsg-quickstart-portal) på den virtuella maskin i Azure.

### Release build av applikation

Man kan också köra en riktig release build av webb applikation. För att kunna det måste man göra en `publish` och sen köra sen dll som genereras.

`dotnet publish --configuration Release`

gå till : SimpleWebHalloWorld/bin/Release/netcoreapp3.1/publish

`dotnet SimpleWebHalloWorld.dll --urls http://0.0.0.0:5000`

## 

## IaC och VM - avancerat

Skåpa ett script (Bash eller Powershell) som ser till att installera alt (primärt .NET Core) som behöves för att köra webb applikationen på servern.

Samt kör igång webb sitet

Kör scriptet som en del av ert Pulumi program

* Man kan göra detta via CustomData parametern (inte så snyggt, men borde funka)
* Ska man göra det helt rätt ska man använda [Dynamic Providers](https://www.pulumi.com/docs/intro/concepts/programming-model/#providers) (som där tyvärr inte finns C# stöd för än) - exempel på: [installation av PostgreSQL](https://www.pulumi.com/docs/intro/concepts/programming-model/#providers)

