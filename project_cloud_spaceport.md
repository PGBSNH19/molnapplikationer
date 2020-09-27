# SpacePark

```
Start: 2020-09-14
End - video presentation (stream): 2020-10-05 23:55
End - code (github): 2020-10-06 23:55
```

![Spacepark illustration](assets\images\spacepark.jpg)

When traveling across space you once in a while need to park you spaceship and take a break, you do that at a spaceport. Managing all these parking at the spaceport is a bit of a job, so a special software for this is needed, one product handling this is called SpacePark, and is a parking system as a service for spaceports.

You have previously build a first version of the this parking system, and it's now time to bring it to the masses, you need to get it out in the cloud and with a web UI.

## Your assignment

You are the developer team at **SpacePort Parking Systems AB** and your assignment is to develop an [service](https://medium.com/@AMZcoin/software-as-a-service-saas-distribution-model-4b7f727c844b) (a combination of frontend, backend and data) which register parking's and close the sparceport when it's full (and open when there is room, and only for spaceships  which fits in). 

All parking's should be registered in a database, which is created using Entity Framework Core and code first. All queries to the database should be done using Entity Frameworks fluent API. 

The twist to this is that this is an **exclusive** spaceport and ONLY famous space travelers which have been part of a Starwars movie can use the spaceport. The travelers should identify themselves when arriving, be able to pay before they can leave the parking lot and get an invoice in the end.

The travelers only use starships which have been part of a Starwars movie (see the endpoint /starships). They should be able to select their starship on arrival in the application.

# The solution

The main focus on this solution is the cloud parts, more than it's the application. (But the application is also important). The "cloud parts" includes CI / CD, deployment, hosting, costs, backup, security, scalability,  integration tests, monitoring.

## The cloud solution (the important part)

You are free to use IaaS offerings like virtual machines and PaaS offerings like App Service and Azure Functions, you just need to justify your choice based on cost, flexibility, vendor lock-in, stability, maintainability, scalability etc.

The database could be an Azure service like Azure SQL Server, Azure MariaDB or Azure CosmosDB (or maybe a combination of these).

Setting up the solution should be as automatized as possible using Containers, IaC (Pulumi) and scripts (preferable Powershell).

But it should be easy to develop, debug and test locally.

The application should be monitored in a way so it's easy to understand what is the state of the service.

## The application

You can choose to take the code from one of the [previous Spacepark projects](#Old spaceport repos), or start from scratch. 

Compared to the first version should this project also contain a web frontend. This could be any solution, some suggestions is:

* A static webpage, requesting the API using JavaScript, also called a [SPA](https://andrejgajdos.com/single-page-application-vs-multiple-page-application/)
* An ASP.NET core MVC application, requesting the API
* An ASP.NET Razor pages application, requesting the API

The API and the web frontend should be two different projects, they can be contained within the same solution (.sln), everything should be within the provided GitHub repo.

![Project overview](assets\images\spacepark-solution2.png)

You should use the Starwars Web API: [swapi.dev](https://swapi.dev/), to test if a visitor is part of a Starwars movie and lists of the Starwars you are not allowed to cache the data from the API, which mean that you will need to request the API each time you need to fetch data.

And remember to create unit tests, where possible.

## Technology stack

* All hosting should be within Microsoft Azure
* All projects should be .NET Core
* Code and [documentation](#Hand in) should be in GitHub
* Pipelines should be configured in Azure DevOps (sadly the free limit is 5 users per Azure Devops project)
* The following technologies **should** be used:
  * Docker Containers : [lecture 03](lecture_03_containers.md)
  * Azure DevOps pipeline (CI and/or CD) : [lecture 04](lecture_04_release.md)
  * At least on Azure DBaaS (SQL server, MariaDB or Cosmos DB) : [lecture 05](lecture_05_databases.md)
  * Logging : [lecture 09](lecture_09_monitoring.md)
* It would be **really nice** if you could use:
  * Azure Blob Storage : [lecture 08](lecture_08_data.md)
  * Azure Application Insights: [lecture 09](lecture_09_monitoring.md)
* The following technologies is **optional** to use (but a plus in the assessment):
  * Kubernetes
  * Private links : [lecture 07](lecture_07_networks.md)

## Hints

* Shut down all azure resources when not using them, to minimize the cost of the application
* Refactor all the time!!
* Write down your findings and learning, both positive and negative.
* Get help and inspiration from the other groups

### Starwars API hints

A recommendation (but no requirement) is to use the Nuget package [RestSharp](http://restsharp.org/) for querying the API. You will need to implement the classes to be used by the build-in ORM in RestSharp.

```csharp
var client = new RestClient("https://swapi.dev/api/");
var request = new RestRequest("people/", DataFormat.Json);
var peopleResponse = client.Get<Swreponse>(request);

Console.WriteLine(peopleResponse.Data.Count);
foreach (var p in peopleResponse.Data.Results)
{
    Console.WriteLine(p.Name);
}
```

All request to the Starwars API should (unlike the example above) be made asynchronous.



# Getting started

This project can of course be started in many ways. But the recommended approach is:

1.  **Plan** what you are going to do, try to identify all parts of the project as detailed as possible
2.  Start with getting the project up and running in Azure DevOps
3. Evaluate and **plan**
4.  Implement the backend, API and database
   * Make sure from first line of code setup a build pipeline
   * Start with CI extend with CD
5. Evaluate and **plan** more!
6.  Implement the web UI
   * Remember the pipelines
7. Evaluate!

# Hand in

Three important aspects of this project is documentation, automation and the code. In that order.

Hand in is done through your git repository, the repo should roughly put contain everything (please read: [What should be in version control… and what should not](https://hackernoon.com/what-should-be-in-version-control-d5f16e9a2bf2)).

**Documentation**

The description of the solution consist of both planning notes, thoughts behind your solution and description the inner working of the solution. All of this should be stored within a git repo. If you use other services provide a link, and some screenshots of the content.

If you are using any kind of external sources (both code and knowledge) make sure to mention this in the documentation.

All documentation should be written using markdown (.md), you are free to choose between writing in Swedish and English (but please make it consistent though the documentation).

**Automation**

Automate as much as possible through containers (Docker), IaC (Pulumi) and scripts.

Store the automation in the git repository.

**Code**

Everything should be kept within one git repository, hosted on GitHub.

Make use to split the code into several projects. You should have one or more solution files.

**Video**

You should produce a [video](video_presentation.md) presentation which describes the project.

# Grading

You grading is to high extend based on this project!

## Code and documentation

Make sure to commit (and push) often! Use your own account.

Do as many branches you wish, bur in the end is it ONLY the content of you **master** branch which counts!

## Elements in the grading

* Process (**important**); how did end up with the final result.
* Automation of service setup
* Pipelines for CI (**important**)
* Pipelines for CD
* Pricing estimates
* **ONE** link the the working application
  * It's ok, if the applications is stopped to save money, as long it can be started on demand
* Automated tests
  * Unit test, run them during CI
  * Integration test
  * Functional testing
* Video presentation of solution

Elements which which is marked as **important**, gives a higher weight in your grading. And you should focus on these in your video presentation.

# Old spaceport repos

This is the repos which where developed during project 3 in the [Dataåtkomst course](https://pgbsnh19.github.io/dataatkomst/)

* [Group 1](https://github.com/PGBSNH19/the-spaceport-grupp-1)
* [Group 2](https://github.com/PGBSNH19/the-spaceport-group-2)
* [Group 3](https://github.com/PGBSNH19/the-spaceport-grupp-3)
* [Group 4](https://github.com/PGBSNH19/the-spaceport-group-4)
* [Group 5](https://github.com/PGBSNH19/the-spaceport-grupp-5)
* [Group 6](https://github.com/PGBSNH19/the-spaceport-grupp-6)
* [Group 7](https://github.com/PGBSNH19/the-spaceport-grupp-7)
* [Group 8](https://github.com/PGBSNH19/the-spaceport-grupp-8)




