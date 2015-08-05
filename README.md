# Phillip Wong

> Software developer, professionally for over 6 years, after several years of academia. I enjoy crafting quality, thoughtful software that work towards solving interesting problems. I am currently living and working in Vancouver, BC.

## Experience

_In addition to my professional experience below, I also have a small number of personal and open source projects which can be found at https://github.com/plmwong_

### PayByPhone Technologies Inc. — Senior Software Engineer
_July 2013 — current &nbsp; | &nbsp; Vancouver, Canada_

Working within a small agile team, primarily responsible for the development and continuous delivery for the Enforcement and Rates/Restrictions domains.

#### Key Projects

##### PayByPhone — Global Rates Engine (GRE) — current
_« In progress: .NET 4.5 C#, MVC Web API, Amazon Web Services, PostgreSQL »_

* Brand new rates management and calculation engine to simplify and unify the separate North American and European rates models/engines/services and lower existing maintenance and running costs.
* Taking a 'technical domain lead' role for this project, with the additional responsibilities of ensuring that stories are well-defined and prepared for the team to discuss, as well as being the primary code reviewer.

##### PayByPhone — Paris Personalised-Parking
_« .NET 4.5 C#, MVC Web API, Oracle PL/SQL »_

* Delivered on new personalised-parking features, which enables cities to charge different parking rates depending on a customer's eligibility. Also designed and helped deliver the GPS-enabled Enforcement API to allow patrollers to query parking data based on their physical location. These were both launched first in the Paris market, and are being rolled out across other french cities.
* To increase the repeatability and speed of our database deployments, I created 'soothsayer' (https://github.com/paybyphone/soothsayer), a command-line tool for supporting Oracle database migrations using PL/SQL scripts.

##### PayByPhone — Rapid Enforcement Query Service (REQS)
_« .NET 4.5 C#, ServiceStack, Redis, ØMQ, Oracle PL/SQL, Event Sourcing, Selenium »_

* Created REQS, a new high performance Rest API for patrollers to query, using a event-sourcing architecture and Redis as an isolated high performance memory store.
* Designed and implemented the key and data structures for storing, indexing and expiring parking sessions within Redis, focussed on easy and fast querying.
* Created and now maintainer of log4net.Raygun (https://github.com/plmwong/log4net-raygun), a log4net appender for sending error exception data and related info to the raygun.io service from applications.

### Intergen — Software Developer in Enterprise Applications
_January 2009 — April 2013 &nbsp; | &nbsp; Wellington, New Zealand_

Primarily using Microsoft technologies, worked on a number of projects for a variety of different clients. Worked in the full gamut of the software development cycle, including gathering user requirements and working with domain experts, designing technical solutions, implementation/delivery, testing and deployment.

Also acted in a team lead role on a couple of smaller team (3 - 5 person) projects.

#### Key Projects

##### Kiwibank — InTouch Upgrade / Anti-Money Laundering Compliance
_« .NET 4.0 C#, WCF Services, Domain Driven Design, PostSharp AOP, CQRS, WPF, Prism, MVVM, AutoMapper »_

* Worked in a team of 10-12 developers to build a ground up replacement for Kiwibank’s existing customer and account management front-end desktop client, using WPF on top of a set of WCF services.
* Took an ownership role in the design and framework development of the domain layer and application services using a Domain Driven Design (DDD) and basic CQRS approach.
* Designed the framework used for domain object validation, which used a specification pattern and extension methods to create a fluent-style validation language that could be more readily shown to, read and understood when collaborating and verifying with the business analysts.

##### Tertiary Education Commission — Industry Training Register
_« .NET 3.5 C#, WCF Services, x.509 certificate security, SQL Server 2008, XSD design, soapUI web service testing »_

* Helped in the design and delivery of this education sector web service, which captures learner event information (e.g. enrolments, course completions) from the Industry Training sector (~40 external providers, ~10,000 messages/day). This new capability for capturing accurate and up-to-date student information has saved the TEC millions of dollars in funding.
* Team lead on a follow-up project to resolve user issues, and provide extra functions; in consultation with Industry Training providers and the Data Warehouse team. Personally improved the performance of daily jobs by 70% using indexes and optimizing database repository code.
* Prototyped the asynchronous messaging architecture and implemented x.509 message security through a custom WCF binding.
* Constructed the framework for running automated end-to-end web service tests using soapUI, allowing for a full regression suite of full functional tests to run nightly.
* Implemented key integration with external data source dependencies by creating proxy WCF services, which translated requests / responses with these third-party web services and presented a simpler, common interface internally.

##### Sproket Markets — PartsTrader US Pilot
_« .NET 4.0 C#, ASP.NET MVC3, WCF Services, jQuery, Entity Framework 4, SQL Server 2008 »_

* Implemented 6-8 screens for the pilot of this online car parts tendering system (commissioned by State Farm Insurance), designed to bring more competition and transparency to the auto repair market.
* Worked alongside another developer to stabilise the registration process for the initial go-live release.

##### Tertiary Education Commission — Invest in a Plan
_« .NET 3.5 C#, ASP.NET Webforms, Sharepoint 2007, WCF Services, SQL Server, SSRS, LINQ to SQL, MSBuild »_

* Lead Developer for a small team to implement business changes/enhancements to the Invest in a Plan set of web applications and web services, which are used by ~400 tertiary organizations and ~20 internal TEC staff to submit and review their investment plans, determining their level of government funding.
* Created the administration dashboard for managing funds and plans for providers from year to year, which has been used for 3 years now without any changes or fixes being required.

## Technical Skills

* `C#` `.NET` `VB.NET` `Java` `C++`
* `MVC` `ASP.NET` `javascript` `AngularJS` `jQuery` `IIS`
* `Test Driven Development` `Unit Testing` `NUnit` `IoC` `Dependency Injection`
* `Domain Driven Design` `CQRS` `Eventing` `Serice Oriented Architecture`
* `Web Services` `RESTful` `SOAP` `Web API` `ServiceStack`
* `Redis` `SQL` `Oracle` `SQL Server`
* `Git` `TFS`
* `Agile` `Scrum` `Kanban`

## Education

### MSc in Computer Science (Artificial Intelligence), with Distinction
_2006 — 2008_

* Worked as a Research Assistant, performing experiments and analysis, working primarily with C++.
* Victoria University of Wellington Masters Scholarship 2007
* Awarded Hunter Scholar Prize for PhD Studies, 2008
* Awarded Tertiary Education Commission Top Achiever Doctoral Scholarship, 2008.
* List of Publications:
http://www.cs.bham.ac.uk/~wbl/biblio/gp-html/PhillipWong.html

### BSc with First Class Honours in Mathematics and Computer Science
_2002 — 2005_

* Translated GPA 3.92
