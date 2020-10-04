# Moln säkerhet

*Lektion 11 av 12, måndag den 5:e oktober 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 90% klar
* Lektionsteori: 100% klar
* Bakgrunds litteratur: 90% klar
* Uppgifter: 90% klar

Målet med denna lektion är att lära vilka säkerhetsmekanismer som finns i Azure och vad man speciellt ska vara uppmärksam på när man utvecklar moln applikationer.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Klassråd (Helen) + Uppsamling från förra lektion (Skalning, upp och ut)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Moln säkerhet
* 10:00 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>Frivilliga övningar / SpacePark-projekt

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/>[SpacePark-standup](project_standup.md)
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

Deadline

* 23:55 <img style="margin-right:0.5em;" src="assets/images/stream18.png" alt="Stream"/> Deadline för [video](https://pgbsnh19.github.io/molnapplikationer/video_presentation.html) på [stream](https://web.microsoftstream.com/channel/9c4a5233-5f83-4454-818e-035023491078)

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Secutity

* Video (6 min): [Hacking challenge at DEFCON](https://www.youtube.com/watch?v=fHhNWAKw0bY)

## Cloud security

* Artikel (9 min): [DevOps Handbook Summary 4 of 4 - Security](http://agilejazz.blogspot.com/p/the-devops-handbook-summary-4-of-4.html)
* Video (6 min): [Google Data Center Security: 6 Layers Deep](https://www.youtube.com/watch?v=kd33UVZhnAA)
* Video (4 min): [Cloud Cybersecurity in Under 5 Minutes](https://www.youtube.com/watch?v=k2684fuzHLs)

## Azure

* Artikel (28 min): [Introduction to Azure security](https://docs.microsoft.com/en-us/azure/security/fundamentals/overview)
* Artikel (4 min): [Secure development best practices on Azure](https://docs.microsoft.com/en-us/azure/security/develop/secure-dev-overview)

### Azure cloud security

* Video (8 min), Azure Essentials: [Defense in depth security](https://www.youtube.com/watch?v=OTGMi0ksjXY)

### Azure Data security

* Artikel (3 min): [What is the Azure Backup service?](https://docs.microsoft.com/en-us/azure/backup/backup-overview)
* Artikel (11 min): [An Introduction to Cloud Backup: What, Why, and How](https://medium.com/@nakivo/an-introduction-to-cloud-backup-what-why-and-how-876e91a772bf)
* Artikel (7 min): [Capsulized overview of Azure Key Vault](https://medium.com/walmartglobaltech/azure-key-vault-d380b77fc31b)



**Total** (86 min):

- Artiklar: 6 stk, total 62 min
- Video: 4 stk, total 24 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 14 (sida 206 till 215) - Data encryption
* Kapitel 15 (sida 216 till 233) - Securing information with Azure Key Vault
* Kapitel 16 (sida 234 till 250) - Azure Security Center and updates

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Application Security

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (5 min): [Hardening ASP.NET Core 3.1 Docker Images](https://medium.com/@michaeldimoudis/hardening-asp-net-core-3-1-docker-images-f0c2ede1667f)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [Lesson 18: Application Isolation](https://devopsbootcamp.osuosl.org/application-isolation.html) 

## Cloud security

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (5 min): [Introducing Joseki: the open-source product to improve cloud infrastructure security](https://medium.com/@ihorkliushnikov/introducing-joseki-the-open-source-product-to-improve-cloud-infrastructure-security-fb71d58f41bd)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (6 min): [Install the SIEM Connector for Cloud App Security](https://www.youtube.com/watch?v=0qAHaCLKTIk)

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>Website: [Azure Security Center](https://azure.microsoft.com/en-us/services/security-center/)

### Threats

<span style="color:#9F58B9; font-weight: 900; margin-right:0.5em;">&#12336;</span>Website: [OWASP](https://owasp.org/)

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Artikel (4 min): [OWASP Top Ten](https://owasp.org/www-project-top-ten/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (3 min): [Cloud Security: It's Tuesday, Carl](https://www.youtube.com/watch?v=NI-plwor2Xw)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (6 min): [Top Cloud Computing Challenges you might face in 2020](https://medium.com/cloud-management-insider/top-cloud-computing-challenges-you-might-face-in-2020-5dcb56ddcc21)

## Azure 

<span style="color:#E78E35; font-weight: 900; margin-right:0.5em;">&#9651;</span>Video (min 59): [Azure Security Basics](https://www.youtube.com/watch?v=YskZ3WcK2jM)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (min 13): [Azure Security Center; Azure Friday](https://www.youtube.com/watch?v=t6gp9k78XEw)

### Networking

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Kurs (43 min): [Skydda och isolera åtkomst till Azure-resurser med hjälp av nätverkssäkerhetsgrupper och tjänstslutpunkter](https://docs.microsoft.com/sv-se/learn/modules/secure-and-isolate-with-nsg-and-service-endpoints/) - [en](https://docs.microsoft.com/en-us/learn/modules/secure-and-isolate-with-nsg-and-service-endpoints)

### Data security

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (5 min): [Microsoft Office 365 Data Safety: A Full Overview of the Shared Responsibility Model](https://medium.com/@nakivo/microsoft-office-365-data-safety-a-full-overview-of-the-shared-responsibility-model-62d52621c7de)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [How to inject Azure Key Vault secrets in the Azure DevOps CI/CD pipelines](https://daniel-krzyczkowski.github.io/How-to-inject-Azure-Key-Vault-secrets-in-the-Azure-DevOps-CICD-pipelines/)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (19 min): [Azure Key Vault Tutorial; Secure secrets, keys and certificates easily](https://www.youtube.com/watch?v=PgujSug1ZbI)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (8 min): [Using Key Vault and Managed Identities with Azure Functions](https://damienbod.com/2020/07/20/using-key-vault-and-managed-identities-with-azure-functions/)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (7 min): [Azure Storage encryption for data at rest](https://docs.microsoft.com/en-us/azure/storage/common/storage-service-encryption)

### Azure access 

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Artikel (7 min): [MSFT Azure AD Conditional Access vs CASB](https://www.bitglass.com/blog/msft-azure-ad-conditional-access-vs-casb)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (41 min): [Microsoft Cloud App Security (CASB)](https://www.youtube.com/watch?v=wLsXZ9MzJxY)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Video (28 min): [Integrated Management and Security](https://www.youtube.com/watch?v=rpOMEa7MBqk)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (6 min): [Azure Active Directory: Service Principal or Application?](https://medium.com/@ihorkliushnikov/azure-active-directory-application-or-service-principal-b5a5e14f2a23)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (5 min): [Cloud Access Security Brokers (CASB) in 5 Minutes](https://www.youtube.com/watch?v=qhAC--N6b8w)

<span style="color:#5874B9; font-weight: 900; margin-right:0.5em;">&#9661;</span>Video (30 min): [Azure Active Directory (AD, AAD) Tutorial ; Identity and Access Management Service](https://www.youtube.com/watch?v=Ma7VAQE7ga4)

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (10 min): [Use Azure Active Directory authentication](https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-overview)

## Compliance

<span style="color:#7EAE42; font-weight: 900; margin-right:0.5em;">&#9711;</span>Artikel (7 min): [Cloud Compliance: What you need to know](https://www.michalsons.com/blog/cloud-compliance/22643)

# Frivillia övningar

## Role Based Access Controll

Gå igenom denna kurs (19 min): [Hantera åtkomst till en Azure-prenumeration med hjälp av rollbaserad åtkomstkontroll (RBAC) i Azure](https://docs.microsoft.com/sv-se/learn/modules/manage-subscription-access-azure-rbac/)

## Azure Backup

Gå igenom denna kurs (33 min): [Skydda dina virtuella datorer med hjälp av Azure Backup](https://docs.microsoft.com/sv-se/learn/modules/protect-virtual-machines-with-azure-backup)

## Azure Key Vault

Bygg en Azure fuction som använder data från en Azure Key Vault.

Hint:

*  [Storing and using secrets in Azure](https://devblogs.microsoft.com/dotnet/storing-and-using-secrets-in-azure/)