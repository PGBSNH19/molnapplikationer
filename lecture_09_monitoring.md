# Monitorering av moln applikationer

*Lektion 9 av 12, måndag den 28:e september 2020*

![Draft](/assets/images/draft.png)

**Draft status**:

* Lektionsplan: 90% klar
* Lektionsteori: 95% klar
* Bakgrunds litteratur: 50% klar
* Uppgifter: 20% klar

Målet med denna lektion är att lära hur man kan monitorera/övervaka en molnlösning (med utgångspunkt i Azure). Hur vet man om alt funkar som det ska, vad applikationen kostar och hur mycket last man har på sin applikation.

## Lektionsplan
Lektion från kl. 8:30 till kl. 16:30

* 8:30 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Klassråd (Helen) + Uppsamling från förra lektion (Webb applikationer i molnet)
  * <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Boarding card, PM på Discord
* 9:15 <img style="margin-right:0.5em;" src="assets/images/teams18.png"  alt="Teams"/> Presentation av dagens teori (Monitorering av moln applikationer ): 
  * Logging
  * Build measure learn
  * Monitoring i Azure
* 10:00 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/>[Buddy uppgifter](#Buddy uppgifter)

Lunch 12:00 till 13:00

* 13:00 <img style="margin-right:0.5em;" src="assets/images/teams18.png" alt="Teams"/>[SpacePark-standup](project_standup.md)
* 13:15 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> SpacePark-projekt
* 16:30 <img style="margin-right:0.5em;" src="assets/images/discord18.png" alt="Discord"/> Landing card, PM på Discord

# Lektionsteori
*Detta är material (artiklar, videoer, blogs, podcasts etc) som är den teoretiska bas för denna lektion, det antas att du har läst/set/lystnad detta innan lektionen starter.*

## Logging

* Artikel (23 min): [Logging Best Practices: The 13 You Should Know](https://www.scalyr.com/blog/the-10-commandments-of-logging/)
* Artikel (3 min), The Twelve Factor App: [Logs](https://12factor.net/logs)

## Build measure learn!

* Artikel (9 min): [The Build-Measure-Learn Feedback Loop](https://www.mindtools.com/pages/article/build-measure-learn.htm)

* Artikel (6 min): [What Is Telemetry?](https://stackify.com/telemetry-tutorial/) 

## Monitoring i Azure

* Artikel (9 min): [Azure Monitor overview](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)

**Total** (41 min):

- Artiklar: 5 stk, total 50 min
- Video: 0 stk, total 0 min

## Bok: Learn Azure In A Month of Lunches

*Detta är vilka delar av den frivilliga [bok (Learn Azure In A Month of Lunches)](info_learningmaterial.md) som är releavant för denna lektion*

* Kapitel 3.3 (Sida 42 till 44) - Viewing diagnosic logs (of App Service)
* Kapitel 9 (sida 175 till 188) - Monitoring and troubleshootings

# Bakgrundsmaterial

*Detta är material som är frivillig, och som kan kan används till at få en djupare insikt i dagens ämnen. Oftast förklara det bakgrunden till dagens lektionsteori, går mer på djupet med ämne eller han har en annan vinkel på det samma material.*

## Logging

Artikel: [DevOps Handbook Summary 2 of 4 - The Second Way](https://agilejazz.blogspot.com/p/the-devops-handbook-summary-2-of-4.html)

Artikel (16 min): [How The Build-Measure-Learn Cycle Really Works](https://www.cleverism.com/how-build-measure-learn-cycle-really-works/)

Artikel: [Container group and instance logging with Azure Monitor logs](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-log-analytics)

Artikel: [How Logging Made me a Better Developer](http://vasir.net/blog/development/how-logging-made-me-a-better-developer)

Artikel: [The 10 commandments of logging](http://www.masterzen.fr/2013/01/13/the-10-commandments-of-logging/)

Microsoft: [Logging](https://docs.microsoft.com/en-us/ef/core/miscellaneous/logging?tabs
=v3) - Entity Framework Core

## Monitoriering i Azure

[Start Monitoring Your ASP.NET Core Web Application](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/dotnetcore-quick-start)

[Azure Monitor data platform](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-platform)

[Monitor and debug](https://docs.microsoft.com/en-us/aspnet/core/azure/devops/monitoring?view=aspnetcore-3.1)

[Application Insights – Use case for TelemetryClient flush calls](https://devblogs.microsoft.com/premier-developer/application-insights-use-case-for-telemetryclient-flush-calls/)

[Application Insights API for custom events and metrics](https://docs.microsoft.com/en-us/azure/azure-monitor/app/api-custom-events-metrics)

Video (min): [Azure Application Insights Tutorial](https://www.youtube.com/watch?v=A0jAeGf2zUQ)

[App Metrics](https://www.app-metrics.io/)

## Andra monitorering system

[Prometheus ](https://prometheus.io/)

[InfluxDB](https://www.influxdata.com/) - open source time series database

Artikel (7 min): [StatsD](https://www.datadoghq.com/blog/statsd/)

# Buddy uppgifter

## Dagens blogg

* Skriv en blogg baserat på Övning  1

*OBS* Akta vad ni skriver i eran blogg, så att ni inte skriver lösenord etc.

Namnge dagens blogg *09.md*, ni får själv välja om ni vill ha en stor blogg som innehåller alla dagens övningar, eller om ni delar upp den i fler delar, i så fall ska ni namnge delarna som: *09a.md*, *09b.md* etc.

# Övning 1: Log i applikation

Bygg en consol applikation som loggar med strukturerat logging

Hints: 

* Logging med .NET

* https://cmatskas.com/application-logging-to-azure-using-serilog/

* https://ml-software.ch/posts/writing-to-azure-diagnostics-log-stream-using-serilog

* https://www.youtube.com/watch?v=iTRILNstmFI
* https://powerapps.microsoft.com/fr-fr/blog/log-telemetry-for-your-apps-using-azure-application-insights/

## Övning 1a: Logg till skärm

Console

1) till skärmen

## Övning 1b: Logg till molnet

Utök så att din applikation loggar till Azure Applicaion insights

# Övning 2: Webbapplikation

Få alla logs att skickas till Azure Application Insights