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
* 9:30 Grupp övning

Lunch 12:00 till 13:00

* 13:00 Programmeringsövning i grupp
* 16:00 Avslutning och frågor i klassen
* 16:30 Slut på lektion
  * Landing card

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Virtual machines

* Beginner Geek: [How to Create and Use Virtual Machines](https://www.howtogeek.com/196060/beginner-geek-how-to-create-and-use-virtual-machines/)
* 

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

## Pulumi

Use Pulumi to Create and Provision an Azure VM for IoT Edge (Node.js) https://geoffhudik.com/tech/2020/05/03/use-pulumi-to-create-and-provision-an-azure-vm-for-iot-edge/

## Terraform

Annat ramverk till att göra IaC

- [Pulumi vs. Terraform](https://www.pulumi.com/docs/intro/vs/terraform/)

- https://blog.kylegalbraith.com/2018/12/21/how-pulumi-compares-to-terraform-for-infrastructure-as-code/

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

### Dagens blogg

Dagens blogg ska innehålla:

* Eran SWAT analys
* En övergripande beskrivningen av hur ni fick en Virtuell maskin att köra med Azure CLI
* En detaljerat beskrivning av eran Pulumi lösning

### Diskussion

Gör en SWAT analys på en virtuell maskin mot en fysik maskin, ha följande i åtanke:

* Hastighet
* Säkerhet
* Stabilitet
* Kostnad

### Få en virtuell maskin att köra lokalt på eran dator

Ladda ner ett VM image, t.ex. en Ubuntu från [osboxes.org](https://www.osboxes.org/ubuntu/)

Få en "Hallo world" .NET Core webb applikation att köra på ert VM.

# Grupp övningar 

*Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen*

## Azure virtual machine

Få en "Hallo world" .NET Core webb applikation att köra på ert VM.

1. Set up a virtual linux machine using the Azure Web Portal
   - Video (9 min): [How to configure a new virtual machine with the Azure Portal](https://www.youtube.com/watch?v=z5J5MQkbqvE)
   - Video (7 min): [How to create a virtual machine in Azure](https://www.youtube.com/watch?v=rOiSRkxtTeU)
2. Install a linux virtual machine using the Azure CLI
   - [Create a Linux virtual machine with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli)
   - Video (7 min): [How to create a virtual machine in Azure](https://www.youtube.com/watch?v=rOiSRkxtTeU)
3. Create a virtual machine in Azure using Pulumi (använd C#/.NET)
   * [Web Server Using Azure Virtual Machine](https://github.com/pulumi/examples/tree/master/azure-ts-webserver), exemplet dock i Typescipt



