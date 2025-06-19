# MyCSharpStudies

Theses projects are suggestions from ChatGPT based on chapter titles. 
Most of them are somehow connected to tabletop roleplaying games.

## Book 1 - C# 13 and .NET 9 – Modern Cross-Platform Development Fundamentals

### Chapter 1: Hello, C#! Welcome, .NET!
Project: Hello RPG World
- Console app that prints a welcome message.
- User enters their name and chooses a character class.
- Select class via menu.
- Extra: ASCII art logo.

### Chapter 2: Speaking C#
Project: BMI Calculator
- Read weight and height.
- Calculate and display BMI.
- Show weight category.
- Extra: Option to choose between kg/cm and lb/inch.

### Chapter 3: Controlling Flow, Converting Types, and Handling Exceptions
Project: Character Generator
- Menu for race and class.
- Randomly generate stats.
- Bonuses depending on class.
- Error handling for input.

### Chapter 4: Writing, Debugging, and Testing Functions
Project: Quest System
- Functions to create, view, and complete quests.
- List of quests.
- Count completed quests.

### Chapter 5: Building Your Own Types with OOP
Project: Character and Enemy Classes
- Classes for Hero and Enemy.
- Properties and methods.
- Extra: Battle simulator.

### Chapter 6: Implementing Interfaces and Inheriting Classes
Project: NPC Interaction
- Interface IInteractable.
- Classes for Merchant, Guard, Villager.
- Call Interact via polymorphism.

### Chapter 7: Packaging and Distributing .NET Types
Project: Utilities Library
- Create a library with DiceRoll, RandomNumber.
- Use in another project.

### Chapter 8: Working with Common .NET Types
Project: In-Game Calendar
- Display and manipulate dates.
- Weather system connected to dates.

### Chapter 9: Working with Files, Streams, and Serialization
Project: Save/Load Characters
- Save characters as JSON.
- Read and display them.
- Auto-save feature.

### Chapter 10: Working with Data Using Entity Framework Core
Project: QuestLog with EF Core
- Database for quests.
- Add, delete, list via menu.

### Chapter 11: Querying and Manipulating Data Using LINQ
Project: Character Directory
- List of characters.
- LINQ filter, e.g., wizards with strength >50.
- Group by class.

### Chapter 12: Introducing Modern Web Development Using .NET
Project: Mini Web API
- ASP.NET Core API that returns quests.
- Add an endpoint to create quests.

### Chapter 13: Building Websites Using ASP.NET Core
Project: Quest Tracker Web App
- View, add, delete quests via a webpage.
- Styling with Bootstrap.

### Chapter 14: Building Interactive Web Components Using Blazor
Project: Quest Tracker in Blazor
- Blazor app for real-time quests.
- Progress bar for status.

### Chapter 15: Building and Consuming Web Services
Project: QuestHub Service
- Web API for quests.
- Console client via HttpClient.
- Random quest generator.

---

## Book 2 - Real World Web Development with .NET 9

### Chapter 1: Introducing Web Development Using Controllers
Project: QuestAPI Controller
- ASP.NET Core WebAPI with a QuestController.
- CRUD endpoints for quests.

### Chapter 2: Building Websites Using ASP.NET Core MVC
Project: Quest MVC Site
- ASP.NET MVC project for quests.
- Razor Pages for listing and creating quests.

### Chapter 3: Model Binding, Validation, and Data Using EF Core
Project: Quest Form
- Form to create a quest.
- Model validation.
- Data saved using EF Core.

### Chapter 4: Building and Localizing Web User Interfaces
Project: MultiLanguageQuest
- Web app with language selection (Swedish/English).
- Localized text for quests and menus.

### Chapter 5: Authentication and Authorization
Project: Quest Auth
- Add login with Identity.
- Roles: Admin, User.
- Only Admin can delete quests.

### Chapter 6: Performance Optimization Using Caching
Project: QuestCache
- Cache quests using MemoryCache.
- Simulate quest expiry through cache expiration.

### Chapter 7: Web User Interface Testing Using Playwright
Project: QuestUITests
- Create Playwright tests for the quest page.
- Test forms and listings.

### Chapter 8: Configuring and Containerizing ASP.NET Core Projects
Project: QuestContainer
- Dockerfile for the quest API.
- Run API in a container.

### Chapter 9: Building Web Services Using ASP.NET Core Web API
Project: QuestAPI Pro
- API with quests and characters.
- Related endpoints.

### Chapter 10: Building Web Services Using ASP.NET Core OData
Project: QuestOData
- Add OData to the quest API.
- Filter and sort quests via URL.

### Chapter 11: Building Web Services Using FastEndpoints
Project: QuestFastAPI
- Build the same API using FastEndpoints.
- Compare coding style with traditional API.

### Chapter 12: Web Service Integration Testing
Project: QuestIntegrationTests
- Integration tests with WebApplicationFactory.

### Chapter 13: Web Content Management Using Umbraco
Project: QuestCMS
- Install Umbraco.
- Create a content type for quests.

### Chapter 14: Customizing and Extending Umbraco
Project: QuestCMS Customization
- Create custom property editors.
- Customize the admin interface.

---

## Book 3 - Apps and Services with .NET 8

### Chapter 1: Introducing Apps and Services with .NET
Project: ServiceLauncher
- Console app that starts various services.
- Examples: quest-service, combat-service.

### Chapter 2: Managing Relational Data Using SQL Server
Project: QuestSQL
- Create a database for quests.
- Connect via EF Core.

### Chapter 3: Building Entity Models for SQL Server Using EF Core
Project: QuestEntities
- Model Quest, Character, Item.
- Define relationships and migrations.

### Chapter 4: Managing NoSQL Data Using Azure Cosmos DB
Project: QuestNoSQL
- Store quest data in Cosmos DB.
- Read/write via SDK.

### Chapter 5: Multitasking and Concurrency
Project: Async Quest Engine
- Run multiple quests in parallel.
- Simulate wait times.

### Chapter 6: Using Popular Third-Party Libraries
Project: QuestTools
- Use Newtonsoft.Json, Serilog.
- Save logs and serialize quests.

### Chapter 7: Handling Dates, Times, and Internationalization
Project: QuestClock
- Manage quest deadlines.
- Display times in different time zones.

### Chapter 8: Building and Securing Web Services Using Minimal APIs
Project: MinimalQuestAPI
- Create a Minimal API for quests.
- JWT-protected endpoint.

### Chapter 9: Caching, Queuing, and Resilient Background Services
Project: QuestBackgroundWorker
- Background service for quests.
- Queue for incoming quest requests.

### Chapter 10: Building Serverless Nanoservices Using Azure Functions
Project: QuestFunctions
- Azure Function that returns a random quest.

### Chapter 11: Broadcasting Real-Time Communication Using SignalR
Project: QuestSignalR
- Real-time notifications for quest status updates.

### Chapter 12: Combining Data Sources Using GraphQL
Project: QuestGraphQL
- Build a GraphQL API for quests and NPCs.

### Chapter 13: Building Efficient Microservices Using gRPC
Project: QuestgRPC
- gRPC service for quest information.

### Chapter 14: Building Web User Interfaces Using ASP.NET Core
Project: QuestWebUI
- Web UI for quests.
- Forms and quest lists.

### Chapter 15: Building Web Components Using Blazor
Project: QuestBlazor
- Interactive quest management interface.

### Chapter 16: Building Mobile and Desktop Apps Using .NET MAUI
Project: QuestMAUI
- Mobile app for quests.

---

## Book 4 - Tools and Skills for .NET 8

### Chapter 1: Introducing Tools and Skills for .NET
Project: Tools Overview
- Gather your tools and write a guide.

### Chapter 2: Making the Most of the Tools in Your Code Editor
Project: EditorWorkshop
- Create custom snippets and templates.

### Chapter 3: Source Code Management Using Git
Project: QuestGitFlow
- Full Git management for the quest system.

### Chapter 4: Debugging and Memory Troubleshooting
Project: QuestDebug
- Intentionally create bugs and debug them.

### Chapter 5: Logging, Tracing, and Metrics for Observability
Project: QuestLogs
- Log quests using Serilog and AppInsights.

### Chapter 6: Documenting Your Code, APIs, and Services
Project: QuestDocs
- Use XML documentation and Swagger.

### Chapter 7: Observing and Modifying Code Execution Dynamically
Project: QuestProfiler
- Inspect code during runtime.

### Chapter 8: Protecting Data and Apps Using Cryptography
Project: QuestSecurity
- Encrypt quest data.

### Chapter 9: Building an LLM-Based Chat Service
Project: QuestGPT
- Chatbot for quest assistance.

### Chapter 10: Dependency Injection, Containers, and Service Lifetime
Project: QuestDI
- Clear DI structure for the system.

### Chapter 11: Unit Testing and Mocking
Project: QuestTests
- Use NUnit and Moq for the quest service.

### Chapter 12: Integration and Security Testing
Project: QuestIntegrationTestsPro
- Test security and endpoint workflows.

### Chapter 13: Benchmarking Performance, Load, and Stress Testing
Project: QuestBenchmark
- BenchmarkDotNet performance tests.

### Chapter 14: Functional and End-to-End Testing of Websites and Services
Project: QuestE2ETests
- Use Cypress or Playwright.

### Chapter 15: Containerization Using Docker
Project: QuestDocker
- Dockerize the quest API.

### Chapter 16: Cloud-Native Development Using .NET Aspire
Project: QuestCloud
- Use .NET Aspire.

### Chapter 17: Design Patterns and Principles
Project: QuestPatterns
- Implement Repository, Factory, and Singleton patterns.

### Chapter 18: Software and Solution Architecture Foundations
Project: QuestArch
- Draw UML diagrams and plan microservices.

### Chapter 19: Your Career, Teamwork, and Interviews
Project: Portfolio and Mock Interviews
- Compile a project portfolio.
- Practice coding interviews.