# MyCSharpStudies

Suggested projects from ChatGPT

## Projektplan f�r C# 13 and .NET 9 � Modern Cross-Platform Development Fundamentals

### Kapitel 1: Hello, C#! Welcome, .NET!
Projekt: Hello RPG World
    � Konsolapp som skriver ut en v�lkomsttext.
    � Anv�ndaren anger sitt namn och v�ljer karakt�rsklass.
    � V�lj klass via meny.
    � Extra: ASCII-art-logotyp.

### Kapitel 2: Speaking C#
Projekt: BMI-kalkylator
    � L�s vikt och l�ngd.
    � R�kna och visa BMI.
    � Visa viktkategori.
    � Extra: Val mellan kg/cm och lb/inch.

### Kapitel 3: Controlling Flow, Converting Types, and Handling Exceptions
Projekt: Karakt�rsgenerator
    � Meny f�r ras och klass.
    � Slumpa stats.
    � Bonusar beroende p� klass.
    � Felhantering vid inmatning.

### Kapitel 4: Writing, Debugging, and Testing Functions
Projekt: Quest-system
    � Funktioner f�r skapa, visa, avsluta quests.
    � Lista med quests.
    � R�kna klara quests.

### Kapitel 5: Building Your Own Types with OOP
Projekt: Karakt�rs- och Fiende-klasser
    � Klasser f�r Hero och Enemy.
    � Egenskaper och metoder.
    � Extra: Stridssimulator.
Kapitel 6: Implementing Interfaces and Inheriting Classes
Projekt: NPC-interaktion
    � Interface IInteractable.
    � Klasser Merchant, Guard, Villager.
    � Anropa Interact via polymorfism.
Kapitel 7: Packaging and Distributing .NET Types
Projekt: Utilities-bibliotek
    � Skapa bibliotek med DiceRoll, RandomNumber.
    � Anv�nd i annat projekt.
Kapitel 8: Working with Common .NET Types
Projekt: In-Game Kalender
    � Visa och manipulera datum.
    � V�dersystem kopplat till datum.
Kapitel 9: Working with Files, Streams, and Serialization
Projekt: Spara/L�sa Karakt�rer
    � Spara karakt�rer som JSON.
    � L�s och visa dem.
    � Autosave-funktion.
Kapitel 10: Working with Data Using Entity Framework Core
Projekt: QuestLog med EF Core
    � Databas f�r quests.
    � L�gg till, ta bort, lista via meny.
Kapitel 11: Querying and Manipulating Data Using LINQ
Projekt: Karakt�rsf�rteckning
    � Lista med karakt�rer.
    � LINQ-filter f�r t.ex. magiker med >50 styrka.
    � Gruppera efter klass.
Kapitel 12: Introducing Modern Web Development Using .NET
Projekt: Mini Web-API
    � ASP.NET Core API som returnerar quests.
    � L�gg till endpoint f�r att skapa quests.
Kapitel 13: Building Websites Using ASP.NET Core
Projekt: Quest Tracker Web App
    � Se, l�gg till, ta bort quests via webbsida.
    � Styling med Bootstrap.
Kapitel 14: Building Interactive Web Components Using Blazor
Projekt: Quest Tracker i Blazor
    � Blazor-app f�r quests i realtid.
    � Progress bar f�r status.
Kapitel 15: Building and Consuming Web Services
Projekt: QuestHub Service
    � WebAPI f�r quests.
    � Konsolklient via HttpClient.
    � Slumpgenerator f�r nya quests.























Projektplan f�r Real World Web Development with .NET 9
Kapitel 1: Introducing Web Development Using Controllers
Projekt: QuestAPI Controller
    � ASP.NET Core WebAPI med en QuestController.
    � CRUD-endpoints f�r quests.
Kapitel 2: Building Websites Using ASP.NET Core MVC
Projekt: Quest MVC-sajt
    � ASP.NET MVC-projekt f�r quests.
    � Razor Pages f�r listning och skapande.
Kapitel 3: Model Binding, Validation, and Data Using EF Core
Projekt: Quest Form
    � Formul�r f�r att skapa quest.
    � Modellvalidering.
    � Data sparas med EF Core.
Kapitel 4: Building and Localizing Web User Interfaces
Projekt: FlerSpr�kQuest
    � Webbapp med spr�kval (svenska/engelska).
    � Lokaliserad text f�r quests och menyer.

Kapitel 5: Authentication and Authorization
Projekt: Quest Auth
    � L�gg till inloggning med Identity.
    � Roller: Admin, User.
    � Endast Admin kan ta bort quests.
Kapitel 6: Performance Optimization Using Caching
Projekt: QuestCache
    � Cacha quests med MemoryCache.
    � Utg�nget cache-minne simulerar quest expiry.
Kapitel 7: Web User Interface Testing Using Playwright
Projekt: QuestUITests
    � Skapa Playwright-tester f�r quest-sidan.
    � Testa formul�r och listningar.
Kapitel 8: Configuring and Containerizing ASP.NET Core Projects
Projekt: QuestContainer
    � Dockerfile f�r quest-API.
    � Starta API i container.
Kapitel 9: Building Web Services Using ASP.NET Core Web API
Projekt: QuestAPI Pro
    � API med quests och karakt�rer.
    � Relaterade endpoints.
Kapitel 10: Building Web Services Using ASP.NET Core OData
Projekt: QuestOData
    � L�gg till OData f�r quest-API.
    � Filtrera och sortera quests via URL.
Kapitel 11: Building Web Services Using FastEndpoints
Projekt: QuestFastAPI
    � Bygg samma API med FastEndpoints.
    � J�mf�r kodstil mot traditionellt API.
Kapitel 12: Web Service Integration Testing
Projekt: QuestIntegrationTests
    � Integrationstester med WebApplicationFactory.
Kapitel 13: Web Content Management Using Umbraco
Projekt: QuestCMS
    � Installera Umbraco.
    � Skapa content-typ f�r quests.
Kapitel 14: Customizing and Extending Umbraco
Projekt: QuestCMS Customization
    � Skapa egna property editors.
    � Anpassa admin-gr�nssnittet.

Projektplan f�r Apps and Services with .NET 8
Kapitel 1: Introducing Apps and Services with .NET
Projekt: ServiceLauncher
    � Konsolapp som startar olika tj�nster.
    � Exempel: quest-service, combat-service.
Kapitel 2: Managing Relational Data Using SQL Server
Projekt: QuestSQL
    � Skapa databas f�r quests.
    � Koppla via EF Core.
Kapitel 3: Building Entity Models for SQL Server Using EF Core
Projekt: QuestEntities
    � Modellera Quest, Character, Item.
    � Relationer och migrering.
Kapitel 4: Managing NoSQL Data Using Azure Cosmos DB
Projekt: QuestNoSQL
    � Spara quest-data i Cosmos DB.
    � L�s/skriv via SDK.
Kapitel 5: Multitasking and Concurrency
Projekt: Async Quest Engine
    � K�r flera quests parallellt.
    � Simulera v�ntetider.
Kapitel 6: Using Popular Third-Party Libraries
Projekt: QuestTools
    � Anv�nd Newtonsoft.Json, Serilog.
    � Spara logg och serialisera quests.
Kapitel 7: Handling Dates, Times, and Internationalization
Projekt: QuestClock
    � Hantera quest deadlines.
    � Visa tider i olika tidszoner.
Kapitel 8: Building and Securing Web Services Using Minimal APIs
Projekt: MinimalQuestAPI
    � Skapa Minimal API f�r quests.
    � JWT-skyddad endpoint.
Kapitel 9: Caching, Queuing, and Resilient Background Services
Projekt: QuestBackgroundWorker
    � Bakgrundstj�nst f�r quests.
    � Queue f�r inkommande quest-requests.
Kapitel 10: Building Serverless Nanoservices Using Azure Functions
Projekt: QuestFunctions
    � Azure Function som returnerar ett slumpat quest.
Kapitel 11: Broadcasting Real-Time Communication Using SignalR
Projekt: QuestSignalR
    � Realtidsnotiser vid quest-status.
Kapitel 12: Combining Data Sources Using GraphQL
Projekt: QuestGraphQL
    � Bygg GraphQL API f�r quests och NPCs.
Kapitel 13: Building Efficient Microservices Using gRPC
Projekt: QuestgRPC
    � gRPC-tj�nst f�r quest-info.
Kapitel 14: Building Web User Interfaces Using ASP.NET Core
Projekt: QuestWebUI
    � WebUI med quests.
    � Formul�r och quest-listor.
Kapitel 15: Building Web Components Using Blazor
Projekt: QuestBlazor
    � Interaktiv questhantering.
Kapitel 16: Building Mobile and Desktop Apps Using .NET MAUI
Projekt: QuestMAUI
    � Mobilapp f�r quests.

Projektplan f�r Tools and Skills for .NET 8
Kapitel 1: Introducing Tools and Skills for .NET
Projekt: Verktygsgenomg�ng
    � Sammanst�ll dina verktyg och skriv guide.
Kapitel 2: Making the Most of the Tools in Your Code Editor
Projekt: EditorWorkshop
    � Skapa egna snippets och templates.
Kapitel 3: Source Code Management Using Git
Projekt: QuestGitFlow
    � Full git-hantering av quest-system.
Kapitel 4: Debugging and Memory Troubleshooting
Projekt: QuestDebug
    � Medvetet skapa buggar och debugga dem.
Kapitel 5: Logging, Tracing, and Metrics for Observability
Projekt: QuestLogs
    � Logga quests med Serilog och AppInsights.
Kapitel 6: Documenting Your Code, APIs, and Services
Projekt: QuestDocs
    � Anv�nd XML-docs och Swagger.
Kapitel 7: Observing and Modifying Code Execution Dynamically
Projekt: QuestProfiler
    � Inspektera kod under k�rning.
Kapitel 8: Protecting Data and Apps Using Cryptography
Projekt: QuestSecurity
    � Kryptera quest-data.
Kapitel 9: Building an LLM-Based Chat Service
Projekt: QuestGPT
    � Chatbot f�r quest-hj�lp.
Kapitel 10: Dependency Injection, Containers, and Service Lifetime
Projekt: QuestDI
    � Tydlig DI-struktur f�r systemet.
Kapitel 11: Unit Testing and Mocking
Projekt: QuestTests
    � NUnit och Moq f�r quest-service.
Kapitel 12: Integration and Security Testing
Projekt: QuestIntegrationTestsPro
    � Testa s�kerhet och endpoint-fl�den.
Kapitel 13: Benchmarking Performance, Load, and Stress Testing
Projekt: QuestBenchmark
    � Benchmarkdotnet-tester.
Kapitel 14: Functional and End-to-End Testing of Websites and Services
Projekt: QuestE2ETests
    � Cypress eller Playwright.
Kapitel 15: Containerization Using Docker
Projekt: QuestDocker
    � Dockerize quest-API.
Kapitel 16: Cloud-Native Development Using .NET Aspire
Projekt: QuestCloud
    � Anv�nd .NET Aspire.
Kapitel 17: Design Patterns and Principles
Projekt: QuestPatterns
    � Implementera Repository, Factory, Singleton.
Kapitel 18: Software and Solution Architecture Foundations
Projekt: QuestArch
    � Rita UML och planera microservices.
Kapitel 19: Your Career, Teamwork, and Interviews
Projekt: Portfolio och Mock-intervjuer
    � S�tt ihop projektportfolio.
    � Tr�na kodintervjuer.