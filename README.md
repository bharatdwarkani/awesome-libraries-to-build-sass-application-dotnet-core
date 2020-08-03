# Awesome curated collection of libraries to build Software as a Service (SaaS) Web application using ASP.NET Core

#### Architecture references 

* [**Microsoft Cloud Design Patterns**](https://docs.microsoft.com/en-us/azure/architecture/patterns/)  
* [**Awesome collection of Sample architecture projects and real time applications**](https://github.com/bharatdwarkani/awesome-dotnet-core-applications)
* [**Design Patterns for Humans**](https://github.com/kamranahmedse/design-patterns-for-humans) 
* [**ASP.NET Core Developer Roadmap**](https://github.com/MoienTajik/AspNetCore-Developer-Roadmap) 


#### Project templates / Frameworks
* [**Dotnet-Boxed**](https://github.com/Dotnet-Boxed/Templates) - Project templates with batteries included, providing the minimum amount of code required to get you going  
* [**Clean Architecture**](https://github.com/jasontaylordev/CleanArchitecture) - This is a solution template for creating a Single Page App (SPA) with Angular and ASP.NET Core following the principles of Clean Architecture.  
* [**starter-kit**](https://github.com/ngx-rocket/starter-kit) - Web project starter kit including modern tools and workflow based on angular-cli, best practices from the community, a scalable base template and a good learning base. 
* [**abp**](https://abp.io/) - ABP is a complete architecture and strong infrastructure to create modern web applications! Follows best practices and conventions to provide you a SOLID development experience.  
* [**fission**](https://github.com/fission/fission) - Fast and Simple Serverless Functions for Kubernetes   

Also, I suggest watching this [**video**](https://www.youtube.com/watch?v=5OtUm1BLmG0) on clean architecture by Jason Taylor.  

#### Multitenancy  

* [**Finbuckle.MultiTenant**](https://github.com/Finbuckle/Finbuckle.MultiTenant) - Finbuckle.MultiTenant is a multitenancy library for ASP.NET Core. It provides functionality for tenant resolution, per-tenant app configuration, and per-tenant data isolation.  
* [**cloudscribe**](https://github.com/cloudscribe/cloudscribe) - cloudscribe is a related set of projects and components for building cross platform web applications on ASP.NET Core. Get the big picture at cloudscribe.com  
* [**OrchardCore**](https://github.com/OrchardCMS/OrchardCore) - Orchard Core Framework: An application framework for building modular, multi-tenant applications on ASP.NET Core.  
* [**aspnetboilerplate**](https://aspnetboilerplate.com/Pages/Documents/Multi-Tenancy) - ASP.NET Boilerplate multitenancy libraries  
* [**saaskit**](https://github.com/saaskit/saaskit) - SaasKit is a .NET toolkit for building SaaS (Software As A Service) applications.  

You can also check out blog posts on multitenancy by [**Ben Foster**](https://benfoster.io/blog/tagged/saaskit) or [**Gunnar Peipman**](https://gunnarpeipman.com/series/multi-tenant-aspnet-core/). These blogs will help you in setting up multitenancy in your project.  

#### Logging / Monitoring

* [**Exceptionless**](https://exceptionless.com/) - It provides real-time error reporting for your JavaScript, Node, .NET Core, ASP.NET, Web API, WebForms, WPF, Console, and MVC apps.   
* [**Serilog**](https://github.com/serilog/serilog) - Serilog is a diagnostic logging library for .NET applications. It is easy to set up, has a clean API, and runs on all recent .NET platforms.  
* [**NLog**](https://github.com/NLog/NLog) -  NLog is a free logging platform for .NET with rich log routing and management capabilities. It makes it easy to produce and manage high-quality logs for your application regardless of its size or complexity.  
* [**Ben.Demystifier**](https://github.com/benaadams/Ben.Demystifier) - High performance understanding for stack traces (Make error logs more productive)  
* [**elmah.io**](https://elmah.io/) -  elmah.io is the easy error logging and uptime monitoring service for .NET. Take back control of your errors with support for all .NET web and logging frameworks.  
* [**prometheus-net**](https://github.com/prometheus-net/prometheus-net) - .NET Standard library to instrument apps for the Prometheus metrics and monitoring system  
* [**Audit.NET**](https://github.com/thepirat000/Audit.NET) - An extensible framework to audit executing operations in .NET and .NET Core.
* [**AuditLogging**](https://github.com/skoruba/AuditLogging) - Simple audit logging for .NET Core with EntityFramework Core  
* [**BenchmarkDotNet**](https://github.com/dotnet/BenchmarkDotNet) - Powerful .NET library for benchmarking
* [**MiniProfiler**](https://github.com/MiniProfiler/dotnet) - A simple but effective mini-profiler for ASP.NET (and Core) websites

#### Health checks  

* [**AspNetCore.Diagnostics.HealthChecks**](https://github.com/Xabaril/AspNetCore.Diagnostics.HealthChecks) -  ASP.NET Core Health Check packages for widely used services and platforms.

#### Autentication / Authorization
* [**IdentityServer4**](https://github.com/IdentityServer/IdentityServer4) - OpenID Connect and OAuth 2.0 Framework for ASP.NET Core  
* [**JPProject.IdentityServer4.AdminUI**](https://github.com/brunohbrito/JPProject.IdentityServer4.AdminUI) -  This is an Administrator Panel for IdentityServer4. It's available in 2 versions: Light and Full. See below the differences.  
* [**PermissionAccessControl2**](https://github.com/JonPSmith/PermissionAccessControl2) - An example application that contains an approach to feature and data authorization code.

#### Feature Management  
* [**FeatureManagement-Dotnet**](https://github.com/microsoft/FeatureManagement-Dotnet) -  Feature flags provide a way for ASP.NET Core applications to turn features on or off dynamically. 
* [**FeatureSwitch**](https://github.com/valdisiljuconoks/FeatureSwitch) - FeatureSwitch is library that should reduce amount of time and code required to implement feature switching in your projects.

#### Validation
* [**FluentValidation**](https://github.com/FluentValidation/FluentValidation) -  A small validation library for .NET that uses a fluent interface and lambda expressions for building validation rules.

#### Caching

* [**StackExchange.Redis**](https://github.com/StackExchange/StackExchange.Redis) -  StackExchange.Redis is a high performance general purpose redis client for .NET languages  
* [**CacheManager**](https://github.com/MichaCo/CacheManager) - is an open source caching abstraction layer for .NET written in C#. It supports various cache providers and implements many advanced features.  
* [**HttpCacheHeaders**](https://github.com/KevinDockx/HttpCacheHeaders) - ASP.NET Core middleware that adds HttpCache headers to responses (Cache-Control, Expires, ETag, Last-Modified), and implements cache expiration & validation models

#### API Gateway / Reverse Proxy  
* [**Ocelot**](https://github.com/ThreeMammals/Ocelot) - Ocelot is a .NET API Gateway.
* [**ProxyKit**](https://github.com/proxykit/ProxyKit) - toolkit to create code-first HTTP Reverse Proxies hosted in ASP.NET Core as middleware. 
* [**YARP**](https://github.com/microsoft/reverse-proxy) (preview) - A Reverse Proxy by microsoft 


#### Service Communication

* [**Polly**](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

#### Documentation  

* [**Swashbuckle.AspNetCore**](https://github.com/domaindrivendev/Swashbuckle.AspNetCore) - Swagger tooling for API's built with ASP.NET Core. Generate beautiful API documentation, including a UI to explore and test operations, directly from your routes, controllers and models.  
* [**redoc**](https://github.com/Redocly/redoc) - OpenAPI/Swagger-generated API Reference Documentation
* [**docsify-dotnet-core**](https://github.com/bharatdwarkani/docsify-dotnet-core) - a sample based on [docsify](https://github.com/docsifyjs/docsify) static help document generator based on markdown.

#### Schedulers

* [**quartznet**](https://github.com/quartznet/quartznet) - Quartz.NET is an opensource project aimed at creating a free-for-commercial use Job Scheduler, with enterprise features.
* [**Hangfire**](https://github.com/HangfireIO/Hangfire/) - Incredibly easy way to perform fire-and-forget, delayed and recurring jobs inside ASP.NET applications.  

#### Mail
* [**MailKit**](https://github.com/jstedfast/MailKit) - A cross-platform .NET library for IMAP, POP3, and SMTP.
* [**MimeKit**](https://github.com/jstedfast/MimeKit) - A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [**FluentEmail**](https://github.com/lukencode/FluentEmail) - .NET Core email sending

#### Unit or Integration Testing 
* [**xunit**](https://github.com/xunit/xunit) - xUnit.net is a free, open source, community-focused unit testing tool for the .NET Framework.
* [**moq**](https://github.com/moq/moq) - The most popular and friendly mocking framework for .NET
* [**NSubstitute**](https://nsubstitute.github.io/) - NSubstitute is designed as a friendly substitute for .NET mocking libraries.
* [**AutoFixture**](https://github.com/AutoFixture/AutoFixture  ) - It is an open source library for .NET designed to minimize the 'Arrange' phase of your unit tests
* [**fluentassertions**](https://github.com/fluentassertions/fluentassertions) - Fluent API for asserting the results of unit tests that targets
* [**snapshooter**](https://github.com/SwissLife-OSS/snapshooter) - Snapshooter is a snapshot WEB API testing tool for .NET Core and .NET Framework
* [**ApprovalTests.Net**](https://github.com/approvals/ApprovalTests.Net) - ApprovalTest verification library for .Net
* [**squadron**](https://github.com/SwissLife-OSS/squadron) - A testing framework for containerized and cloud services
* [**magnet**](https://github.com/SwissLife-OSS/magnet) - ApprovalTest verification library for .Net  
* [**Netling**](https://github.com/hallatore/Netling) - Netling is a load tester client for easy web testing.
* [**Respawn**](https://github.com/jbogard/Respawn) - Intelligent database cleaner for integration tests
* [**jest-dotnet**](https://github.com/tomasbruckner/jest-dotnet) - Simple snapshot testing with inspiration from amazing Jest library.


#### ORM
* [**Dapper**](https://github.com/StackExchange/Dapper) -  a simple object mapper for .Net by Stack Overflow
* [**RepoDb**](https://github.com/mikependon/RepoDb) -  A hybrid ORM library for .NET.  
* [**Dapper-Plus**](https://github.com/zzzprojects/Dapper-Plus) -  Dapper Plus - High-Efficient Bulk Actions (Insert, Update, Delete, and Merge) for .NET  
* [**sqlkata**](https://sqlkata.com/) - A fluent SQL query builder for C#  
* [**dynamic-linq-query-builder**](https://github.com/castle-it/dynamic-linq-query-builder) - A truly generic and dynamic linq query builder to compliment jQuery QueryBuilder and other dynamic linq query generation needs.
* [**Insight.Database**](https://github.com/jonwagner/Insight.Database) - Fast, lightweight .NET micro-ORM


#### Security
* [**NWebsec**](https://github.com/NWebsec/NWebsec) - Security libraries for ASP.NET
* [**CheatSheetSeries**](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/DotNet_Security_Cheat_Sheet.md) - Basic .NET security tips for developers.
* [**aspnetcore-security-headers**](https://github.com/juunas11/aspnetcore-security-headers) - Middleware for adding security headers to an ASP.NET Core application.
* [**AspNetCoreRateLimit**](https://github.com/stefanprodan/AspNetCoreRateLimit) - ASP.NET Core rate limiting middleware
* [**HtmlSanitizer**](https://github.com/mganss/HtmlSanitizer) - Cleans HTML to avoid XSS attacks  
* [**awesome-dotnet-security**](https://github.com/guardrailsio/awesome-dotnet-security) - Awesome .NET Security Resources


### Cryptography
* [**BCrypt.net**](https://github.com/neoKushan/BCrypt.Net-Core) - A .net Core port of BCrypt.net
* [**Portable.BouncyCastle**](https://github.com/novotnyllc/bc-csharp) - The Bouncy Castle Crypto package is a C# implementation of cryptographic algorithms and protocols

#### Misc
* [**EventStore**](https://github.com/EventStore/EventStore) - The open-source, functional database with Complex Event Processing in JavaScript.  
* [**MessagePack-CSharp**](https://github.com/neuecc/MessagePack-CSharp) - Extremely Fast MessagePack Serializer for C#  
* [**MediatR**](https://github.com/jbogard/MediatR) - Simple, unambitious mediator implementation in .NET  
* [**AutoMapper**](https://github.com/AutoMapper/AutoMapper) - AutoMapper is a simple little library built to solve a deceptively complex problem - getting rid of code that mapped one object to another.
* [**NSwag**](https://github.com/RicoSuter/NSwag) - The Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript.
* [**AutoWrapper**](https://github.com/proudmonkey/AutoWrapper) - A simple, yet customizable global exception handler and Http response wrapper for ASP.NET Core APIs.
* [**NRules**](https://github.com/NRules/NRules) - Rules engine for .NET, based on the Rete matching algorithm, with internal DSL in C#. 
* [**cake-build**](https://github.com/cake-build/cake) - Cake (C# Make) is a cross platform build automation system.  
* [**BundlerMinifier**](https://github.com/madskristensen/BundlerMinifier) - Visual Studio extension
* [**nodatime**](https://github.com/nodatime/nodatime) - A better date and time API for .NET
* [**CliWrap**](https://github.com/Tyrrrz/CliWrap) - CliWrap is a library for interacting with command line executables in a functional manner. It provides a convenient model for launching external processes, redirecting inputs and outputs, awaiting completion, and handling cancellation.
* [**FluentDocker**](https://github.com/mariotoffia/FluentDocker) - Commands, Services and Fluent API for docker, docker-compose & docker-machine, for win/mac/linux and native docker in c#
* [**FluentFTP**](https://github.com/robinrodricks/FluentFTP/) - An FTP and FTPS client for .NET & .NET Standard, optimized for speed.  
* [**reCAPTCHA**](https://github.com/PaulMiami/reCAPTCHA) - reCAPTCHA 2.0 for ASPNET Core
* [**Z.ExtensionMethods**](https://github.com/zzzprojects/Z.ExtensionMethods) - C# Extension Methods | Over 1000 extension methods
* [**html-agility-pack**](https://github.com/zzzprojects/html-agility-pack) - This is an agile HTML parser that builds a read/write DOM and supports plain XPATH or XSLT
* [**NServiceBus**](https://github.com/Particular/NServiceBus) - The most popular service bus for .NET
* [**YamlDotNet**](https://github.com/aaubry/YamlDotNet) -  YamlDotNet is a .NET library for YAML  
* [**protobuf-net**](https://github.com/protobuf-net/protobuf-net) - Protocol Buffers library for idiomatic .NET 
* [**TimeZoneConverter**](https://github.com/mj1856/TimeZoneConverter) - Lightweight libraries to convert between IANA, Windows, Rails, and POSIX time zones.
* [**ExtCore**](https://github.com/ExtCore/ExtCore) - ExtCore is a free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core.

For more such libraries check out [**awesome-dotnet-core**](https://github.com/thangchung/awesome-dotnet-core)

#### Code Quality - Static Analyzers
[**awesome-dotnet-core-static-analyzers**](https://github.com/bharatdwarkani/awesome-dotnet-core-static-analyzers) - Awesome collection of .NET Core Static Analyzers using the .NET Compiler Platform (Roslyn). Also includes a How to guide for using these analyzers and sample project with Cake Build Script to integrate in Continuous integration.

Visit my site [**Share Tech Links**](https://sharetechlinks.com/)  for curated list of tech related interesting blog links.

**Pull requests are welcome for including new items in this list.** 
















 








