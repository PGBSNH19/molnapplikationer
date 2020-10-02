# Moln säkerhet

*Lektion 11 av 12, måndag den 5:e oktober 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 0% klar
* Lektionsteori: 0% klar
* Bakgrunds litteratur: 0% klar
* Uppgifter: 0% klar

Målet med denna lektion är att lära vilka säkerhetsmekanismer som finns i Azure och vad man speciellt ska vara uppmärksam på när man utvecklar moln applikationer.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Klassråd (Helen) + Uppsamling från förra lektion (Skalning, upp och ut)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori: 
  * Moln säkerhet
* 10:00 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter)

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/>[SpacePark-standup](project_standup.md)
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Cloud security

9 min: [DevOps Handbook Summary 4 of 4 - Security](http://agilejazz.blogspot.com/p/the-devops-handbook-summary-4-of-4.html)

Video (6 min): [Google Data Center Security: 6 Layers Deep](https://www.youtube.com/watch?v=kd33UVZhnAA)

Video (4 min): [Cloud Cybersecurity in Under 5 Minutes](https://www.youtube.com/watch?v=k2684fuzHLs)

## Azure cloud secuirty

Video (8 min), Azure Essentials: [Defense in depth security](https://www.youtube.com/watch?v=OTGMi0ksjXY)

## Azure Data security

https://medium.com/@nakivo/microsoft-office-365-data-safety-a-full-overview-of-the-shared-responsibility-model-62d52621c7de

https://docs.microsoft.com/en-us/azure/backup/backup-overview

11 min: [An Introduction to Cloud Backup: What, Why, and How](https://medium.com/@nakivo/an-introduction-to-cloud-backup-what-why-and-how-876e91a772bf)

7 min : [Azure Storage encryption for data at rest](https://docs.microsoft.com/en-us/azure/storage/common/storage-service-encryption)

## Azure access security















## Azure

Introduction to Azure security, 28 min, https://docs.microsoft.com/en-us/azure/security/fundamentals/overview

Install the SIEM Connector for Cloud App Security https://www.youtube.com/watch?v=0qAHaCLKTIk

Integrated Management and Security https://www.youtube.com/watch?v=rpOMEa7MBqk



What is Azure Databricks? https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks

Azure Databricks Secret Scopes Tutorial  ; Secure your notebook secrets https://www.youtube.com/watch?v=9VzBS4OiP_A

[Azure Key Vault Tutorial; Secure secrets, keys and certificates easily](https://www.youtube.com/watch?v=PgujSug1ZbI)

Secure development best practices on Azure, 4 min, https://docs.microsoft.com/en-us/azure/security/develop/secure-dev-overview

Azure Active Directory: Service Principal or Application? https://medium.com/@ihorkliushnikov/azure-active-directory-application-or-service-principal-b5a5e14f2a23

https://azure.microsoft.com/en-us/services/security-center/

https://damienbod.com/2020/07/20/using-key-vault-and-managed-identities-with-azure-functions/

https://devblogs.microsoft.com/dotnet/storing-and-using-secrets-in-azure/

https://daniel-krzyczkowski.github.io/How-to-inject-Azure-Key-Vault-secrets-in-the-Azure-DevOps-CICD-pipelines/

## CASB / AD

Azure role-based access control (RBAC)

https://docs.microsoft.com/sv-se/learn/modules/manage-subscription-access-azure-rbac/

Video: [Cloud Access Security Brokers (CASB) in 5 Minutes](https://www.youtube.com/watch?v=qhAC--N6b8w)

MSFT Azure AD Conditional Access vs CASB https://www.bitglass.com/blog/msft-azure-ad-conditional-access-vs-casb

Microsoft Cloud App Security (CASB) https://www.youtube.com/watch?v=wLsXZ9MzJxY

Azure Active Directory (AD, AAD) Tutorial ; Identity and Access Management Service https://www.youtube.com/watch?v=Ma7VAQE7ga4

Use Azure Active Directory authentication, 10 min,  https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-overview





**Total** (0 min):

- Artiklar: 0 stk, total 0 min
- Video: 0 stk, total 0 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 14 (sida 206 till 215) - Data encryption
* Kapitel 15 (sida 216 till 233) - Securing information with Azure Key Vault
* Kapitel 16 (sida 234 till 250) - Azure Security Center and updates

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Cloud security

Hacking challenge at DEFCON https://www.youtube.com/watch?v=fHhNWAKw0bY

Introducing Joseki: the open-source product to improve cloud infrastructure security https://medium.com/@ihorkliushnikov/introducing-joseki-the-open-source-product-to-improve-cloud-infrastructure-security-fb71d58f41bd

[Lesson 18: Application Isolation](https://devopsbootcamp.osuosl.org/application-isolation.html) 



## Threats

https://owasp.org/


OWASP Top Ten https://owasp.org/www-project-top-ten/

Video, 3min,: [Cloud Security: It's Tuesday, Carl](https://www.youtube.com/watch?v=NI-plwor2Xw)



[Top Cloud Computing Challenges you might face in 2020](https://medium.com/cloud-management-insider/top-cloud-computing-challenges-you-might-face-in-2020-5dcb56ddcc21)

## Compliance

Cloud Compliance: What you need to know https://www.michalsons.com/blog/cloud-compliance/22643

# Frivillia övningar 

Detta är övningar som du äntligen gör själv, i grupp eller i plenum tillsammans med hela klassen