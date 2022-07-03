# Methodology
## [Domain-Driven Design Starter Modelling Process](https://github.com/ddd-crew/ddd-starter-modelling-process)
- Steps Summary
	- ddd-starter-modelling-process.jpg
- 1 - Align
	- Business Model Canvas
	- [Impact Mapping](https://www.impactmapping.org/)
		- [Examples](https://www.impactmapping.org/example.html)
		- In a nutshell
		  Mindmap-ish:
		  Goals = Why
		  Measure
		  Actors = Who
		  Impact = How
		  Deliverable = What
- 2 - Discover
	- [Domain Storytelling](https://domainstorytelling.org/#dst-requirements)
	  Actor-centric
		- [Domain Story Modeler](https://github.com/WPS/domain-story-modeler)
		- [Online Modeler](https://www.wps.de/modeler/)
		- [DST Whiteboard Kit](https://domainstorytelling.org/images/DST_Whiteboard-Kit.pdf)
	- [Example Mapping](https://cucumber.io/blog/bdd/example-mapping-introduction/)
	- Event Storming
	- [User Story Mapping](file:///C:/data/MyPCM/User%20Story%20Mapping%20Notes.xmind)
- 3 - Decompose
	- [Context Maps](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps)
	  Sociotechnical architecture
		- [Context Map Cheat Sheet](https://github.com/ddd-crew/context-mapping)
		- [Remote Context Mapping Starter Kit for Miro](https://github.com/ddd-crew/context-mapping#remote-context-mapping-starter-kit-for-miro)
	- [Business Capability Mapping](https://www.slideshare.net/trondhr/from-capabilities-to-services-modelling-for-businessit-alignment-v2-ext?next_slideshow=1)
	- [DDD Heuristics](https://www.dddheuristics.com/)
	- Event Storming with Sub-Domains
	- [Independent Service Heuristics](https://github.com/TeamTopologies/Independent-Service-Heuristics)
- 4 - Connect
	- [Domain Message Flow Modeling](https://github.com/ddd-crew/domain-message-flow-modelling)
	- [Business Process Model and Notation](https://en.wikipedia.org/wiki/Business_Process_Model_and_Notation)
	- Process Modeling Event Storming
	- [UML Sequence Diagram](https://en.wikipedia.org/wiki/Sequence_diagram)
- 5 - Strategize
	- [Core Domain Charts](https://github.com/ddd-crew/core-domain-charts)
		- [Core Domain Patterns](https://medium.com/nick-tune-tech-strategy-blog/core-domain-patterns-941f89446af5)
	- Purpose Alignment Model
	- Wardley Mapping
- 6 - Organize
	- Context Map
	- Dynamic Reteaming
	- [Pioneers, Settlers & Town Planners](http://wardleypedia.org/mediawiki/index.php/Pioneers_settlers_town_planners)
	- [Team Topologies](file:///C:/data/MyPCM/Book%20-%20Team%20Topologies.xmind)
- 7 - Define
	- [Bounded Context Canvas](https://github.com/ddd-crew/bounded-context-canvas)
		- [Model Traits worksheet](https://github.com/ddd-crew/bounded-context-canvas/blob/master/resources/model-traits-worksheet.md)
	- C4 System Context Diagram
	- [Quality Storming](https://speakerdeck.com/mploed/quality-storming)
- 8 - Code
	- [Aggregate Design Canavas](https://github.com/ddd-crew/aggregate-design-canvas)
	- [C4 Component Diagrams](https://c4model.com/#ComponentDiagram)
	- Design-Level EventStorming
	- Event Modelling
	- Hexagonal Architecture
	- [Onion Architecture](https://jeffreypalermo.com/2008/07/the-onion-architecture-part-1/)
	- Mob Programming
	- [Model Exploration Whirlpool](https://domainlanguage.com/ddd/whirlpool/)
	- Unified Modeling Language
## [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/read_full)
# Concepts
## Strategic Design
- Ubiquitous Language
- Bounded Contexts
	- Subdomains
	- Context Mapping
- Distillation
## Tactical Design
- Onion / Hexagonal Architecture
	- Modules
	- Services
	- Domain
	- Infrastructure
- Aggregate
- Domain Events
- Entities
- Value Objects
- Repositories?
# Frameworks
[Axon](https://axoniq.io/)
Framework and server for event-driven microservices (Java)
[Wolkenkit](https://www.wolkenkit.io/)
# Learn
## Books (To Migrate)
- Domain Driven Design - Tackling Complexity in the Heart of Software
	- [Book](file:///C:/data/MyPCM/Books/Domain%20Driven%20Design%20-%20Tackling%20Complexity%20in%20the%20Heart%20of%20Software.pdf)
- Patterns, Principles and Practices of Domain-Driven Design
	- [Book](file:///C:/data/MyPCM/Books/Patterns,%20Principles%20and%20Practices%20of%20Domain-Driven%20Design%20-%201st%20Edition%20(2015).pdf)
- Domain-Driven Design Distilled by Vaughn Vernon
	- [Book](file:///C:/data/MyPCM/Books/Domain-Driven%20Design%20Distilled%20by%20Vaughn%20Vernon%20(z-lib.org).epub)
- Domain-Driven Design Using Naked Objects
	- [Book](file:///C:/data/MyPCM/Books/Domain-Driven%20Design%20Using%20Naked%20Objects%20by%20Dan%20Haywood%20(z-lib.org).pdf)
- Domain Modeling made Functional
	- [Book](file:///C:/data/MyPCM/Books/Domain%20Modeling%20made%20Functional.%20Tackle%20Software%20Complexity%20with%20Domain-driven%20Design%20and%20F%20by%20Scott%20Wlaschin%20(z-lib.org).pdf)
- Domain-Driven Design Quickly
	- [Book](file:///C:/data/MyPCM/Books/Domain-Driven%20Design%20Quickly%20by%20Abel%20Avram,%20Floyd%20Marinescu%20(z-lib.org).pdf)
- [What Is Domain-Driven Design](https://www.oreilly.com/library/view/what-is-domain-driven/9781492057802/)
- Implementing Domain-Driven Desigh
- [Domain Modeling Made Functional](https://fsharpforfunandprofit.com/books/#domain-modeling-made-functional-ebook-and-paper)
## Tutorials
- [Domain Driven Design Crash Course](https://vaadin.com/learn/tutorials/ddd)
- [.Net Architecture Guide - Tackle Business Complexity in a Microservice with DDD and CQRS Patterns](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/)
## People
- [Vaugh Vernon](https://vaughnvernon.co/)
	- [Twitter](https://twitter.com/VaughnVernon)
## Examples
- [Full Modular Monolith application with Domain-Driven Design approach.](https://github.com/kgrzybek/modular-monolith-with-ddd)
- [.Net Core eShopOnContainers](https://github.com/dotnet-architecture/eShopOnContainers)
- Old
	- [DDD Sample App](https://github.com/citerus/dddsample-core)
# Articles
[First rule of DDD is: let’s not talk about DDD](https://philippe.bourgau.net/first-rule-of-ddd-is-lets-not-talk-about-ddd/)
[Misadventures with Big Design Up Front](https://philippe.bourgau.net/misadventures-with-big-design-up-front/)
First article of series Event-Storming+DDD
[Design and Implementation of a DDD-Based Modular Monolith](https://www.infoq.com/news/2019/09/design-ddd-modular-monolith/)
[Managing Complexity in Complex Adaptive Systems with Domain-Driven Design](https://medium.com/nick-tune-tech-strategy-blog/managing-complexity-in-complex-adaptive-systems-with-domain-driven-design-eb79f0ca37bb)
[DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/)
Visualizing sociotechnical architectures with Context Maps ](https://speakerdeck.com/mploed/visualizing-sociotechnical-architectures-with-context-maps?slide=1)
[Strategic DDD Using The Bounded Context Canvas](https://drive.google.com/file/d/14pv2yJ2xBXyfg0IoGnh48O7B3rzxyXe6/view)
[Domain-Driven Design Techniques for Everyone](https://drive.google.com/file/d/1yEhLQ0Dz3znZSN2p3qXZexc5CQm_x149/view)
[Core Domain Patterns](https://medium.com/nick-tune-tech-strategy-blog/core-domain-patterns-941f89446af5)
# Event Storming
## Articles
- [Good guide for Business](https://www.boldare.com/blog/event-storming-guide/)
- [Event Storming lessons from Post-It haters](https://philippe.bourgau.net/event-storming-lessons-from-post-it-haters/)
- [How to use Event Storming to introduce Domain Driven Design](https://philippe.bourgau.net/how-to-use-event-storming-to-introduce-domain-driven-design/)
- [How to Capture the Outputs of an Event Storming Workshop?](https://philippe.bourgau.net/how-to-capture-the-outputs-of-an-event-storming-workshop/)
- [5 Views to Capture the Outputs of an Event Storming workshop](https://philippe.bourgau.net/5-views-to-capture-the-outputs-of-an-event-storming-workshop/)
- [How to max out DDD Big Picture Event Storming with other Workshops](https://philippe.bourgau.net/how-to-max-out-ddd-big-picture-event-storming-with-other-workshops/)
- [Modelling Reactive Systems with Event Storming and Domain-Driven Design](https://blog.redelastic.com/corporate-arts-crafts-modelling-reactive-systems-with-event-storming-73c6236f5dd7)
- [A facilitators recipe for Event Storming](https://medium.com/@springdo/a-facilitators-recipe-for-event-storming-941dcb38db0d)
	- Organization Notes
- [Remote Team Flow EventStorming for Retrospectives](https://medium.com/nick-tune-tech-strategy-blog/remote-team-flow-eventstorming-for-retrospectives-a8ea33cdb277)
- [EventStorming Modelling Patterns: Going Beyond the Superficial](https://eventstore.com/blog/event-storming-going-beyond-the-superficial)
- [Open Practices](https://openpracticelibrary.com/practice/event-storming/)
	- Related Practices
	  User Story Mapping is a great way to create an Agile delivery plan for a business process designed with Event Storming
	  Journey Mapping4 can provide a high level overview of the business process before using Event Storming to get into the details
	  Event Storming will identify key views for your user interface, which can jump start Site Mapping5 or Wireframing6
	  
[Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming)
[Glossary & Cheat Sheet](http://EventStorming Glossary & Cheat sheet)
# Resources
### [Virtual DDD](https://virtualddd.com/)

