#book #team-org #micro-service #platform #conway-law
[epub](/Data/Books/Team_Topologies_Organizing_Business_and_Technology_Teams_for_Fast_Flow_by_Matthew_Skelton_Manuel_Pais_[Skelton,_Matthew]_(z-lib.org)(1))
[status::read]
# Book - Team Topologies
## PART I Teams As the Means of Delivery
### 1 - The Problem with Org Charts
  Conway’s law suggests major gains from designing software architectures and team interactions together, since they are similar forces.
  Team Topologies clarifies team purpose and responsibilities, increasing the effectiveness of their interrelationships.
  Team Topologies takes a humanistic approach to building software systems while setting up organizations for strategic adaptability
  
  Every organization has:
  Formal structure (the org chart)—facilitates compliance
  Informal structure—the “realm of influence” between individuals
  Value creation structure—how work actually gets done based on inter-personal and inter-team reputation
  
  Pflaeging suggests that the key to successful knowledge work organizations is in the interactions between the informal structure and the value creation structure (that is, the interactions between people and teams). Other authors have proposed similar characterizations, such as Frédéric Laloux in Reinventing Organizations or Brian Robertson’s Holacracy approach.
  
  Org chart for compliance, informal comm for delivery and value org
### 2 - Conway’s Law and Why It Matters
  Organizations are constrained to produce designs that reflect communication paths.
  The design of the organization constrains the “solution search space,” limiting possible software designs.
  Requiring everyone to communicate with everyone else is a recipe for a mess.
  Choose software architectures that encourage team-scoped flow.
  Limiting communication paths to well-defined team interactions produces modular, decoupled systems
  
  It creates an imperative to keep asking: “Is there a better design that is not available to us because of our organization?”
  —Mel Conway, Toward Simplifying Application Development, in a Dozen Lessons
  
  This quote from Ruth Malan provides what could be seen as the modern version of Conway’s law: “If the architecture of the system and the architecture of the organization are at odds, the architecture of the organization wins."
### 3 - Team-First Thinking
  The team is the most effective means of software delivery, not individuals.
  Limit the size of multi-team groupings within the organization based on Dunbar’s number.
  Restrict team responsibilities to match the maximum team cognitive load.
  Establish clear boundaries of responsibility for teams.
  Change the team working environment to help teams succeed. 
  
  
  As Michael Nygard says: “Team assignments are the first draft of the architecture.”
## PART II Team Topologies that Work for Flow
### 4 - Static Team Topologies
  Ad hoc or constantly changing team design slows down software delivery.
  There is no single definitive team topology but several inadequate topologies for any one organization.
  Technical and cultural maturity, org scale, and engineering discipline are critical aspects when considering which topology to adopt.
  In particular, the feature-team/product-team pattern is powerful but only works with a supportive surrounding environment.
  Splitting a team’s responsibilities can break down silos and empower other teams. 
  
  Loose coupling—components do not hold strong dependencies on other components
  High cohesion—components have clearly bounded responsibilities, and their internal elements are strongly related
  Clear and appropriate version compatibility
  Clear and appropriate cross-team testing
  
  To put this in the strongest way, regular reorganizations for the sake of management convenience or reducing headcount actively destroy the ability of organizations to build and operate software systems effectively. Reorganizations that ignore Conway’s law, team cognitive load, and related dynamics risk acting like open heart surgery performed by a child: highly destructive.
  
  Fast flow requires restricting communication between teams. Team collaboration is important for gray areas of development, where discovery and expertise is needed to make progress. But in areas where execution prevails—not discovery—communication becomes an unnecessary overhead
  
  Disbanding high-performing teams is worse than vandalism: it is corporate psychopathy.
  —Allan Kelly, Project Myopia
  
  The Tuckman model describes how teams perform in four stages:
  Forming: assembling for the first time
  Storming: working through initial differences in personality and ways of working
  Norming: evolving standard ways of working together
  Performing: reaching a state of high effectiveness
  
  In their 2012 paper, “A Taxonomy of Dependencies in Agile Software Development,” Diane Strode and Sid Huff propose three different categories of dependency: knowledge,task, and resource dependencies. Such a taxonomy can help pinpoint dependencies between teams and the potential constraints to the flow of work ahead of time.
### 5 - The Four Fundamental Team Topologies
  The four fundamental team topologies simplify modern software team interactions.
  Mapping common industry team types to the fundamental topologies sets up organizations for success, removing gray areas of ownership and overloaded/underloaded teams.
  The main topology is (business) stream-aligned; all other topologies support this type.
  The other topologies are enabling, complicated-subsystems, and platform.
  The topologies are often “fractal” (self-similar) at large scale: teams of teams. 
  
  A stream-aligned team aims to produce a steady flow of feature delivery.
  A stream-aligned team is quick to course correct based on feedback from the latest changes.
  A stream-aligned team uses an experimental approach to product evolution, expecting to constantly learn and adapt.
  A stream-aligned team has minimal (ideally zero) hand-offs of work to other teams.
  A stream-aligned team is evaluated on the sustainable flow of change it produces (together with some supporting technicaland team-health metrics).
  A stream-aligned team must have time and space to address code quality changes (sometimes called “tech debt”) to ensure that changing the code remains safe and easy to do.
  A stream-aligned team proactively and regularly reaches out to the supporting fundamental-topologies teams (complicated subsystem, enabling, and platform).
  Members of a stream-aligned team feel they have achieved or are in the path to achieving “autonomy, mastery, and purpose,” the three key components of engaged knowledge workers, according to Daniel Pink.
  
  An enabling team seeks to understand the needs of stream-aligned teams, establishing regular checkpoints and jointly agreeing when more collaboration is needed.
  An enabling team stays ahead of the curve in keeping abreast of new approaches, tooling, and practices in their area of expertise, well before an actual need is expected from stream-aligned teams. In the past, this has been the mission of architecture or innovation teams, but the focusenabling other teams creates a better dynamic.
  An enabling team acts as a messenger of both good news (e.g., “There’s a new UI automation framework that can reduce our custom test code by 50%.”) and bad news (e.g., “Javascript framework X, which we’re using extensively, is no longer actively maintained.”). This helps with management of the technology life cycle.
  Occasionally, the enabling team might act as a proxy for external (or internal) services that are currently too difficult for stream-aligned teams to use directly.
  An enabling team promotes learning not only inside the enabling team but across stream-aligned teams, acting as a curator that facilitates appropriate knowledge sharing inside the organization (supporting what Tom DeMarco and Tim Lister call a “key learning function.”
  
  A complicated-subsystem team is mindful of the current stage of development of the subsystem and acts accordingly: high collaboration with stream-aligned teams during early exploration and development phases; reduced interaction and focus on the subsystem interface and feature evolution and usage during later stages, when the subsystem has stabilized.
  With a complicated-subsystem team, delivery speed and qualit for the subsystem is clearly higher than if/when the subsystem was being developed by a stream-aligned team (before the decision to split).
  The complicated-subsystem team correctly prioritizes and delivers upcoming work respecting the needs of the stream-aligned teams that use the complicated subsystem.
  
  A platform team uses strong collaboration with stream-aligned teams to understand their needs.
  A platform team relies on fast prototyping techniques and involves stream-aligned team members for fast feedback on what works and what does not.
  A platform team has a strong focus on usability and reliability for their services (treating the platform as a product), and regularly assesses if the services are still fit for purpose and usable.
  A platform team leads by example: using the services they provide internally (when applicable), partnering with stream-aligned teams and enabling teamand consuming lower level platforms (owned by other platform teams) whenever possible.
  A platform team understands that adoption of internal new services, like new technologies, is not immediate, but instead evolves along an adoption curve
  
  A well-designed and well-run platform using what Henrik Kniberg calls “customer-driven platform teams” can be a significant “force multiplier” for software delivery within organizations, but care needs to be taken to ensure that the platform always serves the needs of consuming applications and services, not the other way round.
  
  In all cases, we should aim for a thinnest viable platform (TVP) and avoid letting the platform dominate the discourse. As Allan Kelly says, “software developers love building platforms and, without strong product management input, will create a bigger platform than needed
  
  By aiming to reduce cognitive load on Dev teams, a good platform helps Dev teams focus on the germane (differentiating) aspects of a problem, increasing personal and team-level flow, and enabling the whole team to be more effective. As Kenichi Shibata of global publishing company Conde Nast International says, “The most important part of the platform is that it is built for developers.”
  
  The platform attempts to “get out of the way” of Dev teams, enabling them to build what they need with few pre-conceptions about how teams need to do that. A good test for DevEx is how easy it is to onboard a new Developer to the platform.
### 6 - Choose Team-First Boundaries
  Choose software boundaries using a team-first approach.
  Beware of hidden monoliths and coupling in the software-delivery chain.
  Use software boundaries defined by business-domain bounded contexts.
  Consider alternative software boundaries when necessary and suitable. 
  
  A Team-First Approach to Software Responsibilities and Boundaries:
  Hidden Monoliths and Coupling
  Application Monolith
  Joined-at-the-Database Monolith
  Monolithic Builds (Rebuild Everything)
  Monolithic (Coupled) Releases
  Monolithic Model (Single View of the World)
  Monolithic Thinking (Standardization)
  Monolithic Workplace (Open-Plan Office)
  Software Boundaries or “Fracture Planes”
  Fracture Plane: Business Domain Bounded Context
  Fracture Plane: Regulatory Compliance
  Fracture Plane: Change Cadence
  Fracture Plane: Team Location
  Fracture Plane: Risk
  Fracture Plane: Performance Isolation
  Fracture Plane: Technology
  Fracture Plane: User Personas
  Natural “Fracture Planes” for Your Specific Organization or Technologies
## PART II Team Topologies that Work for Flow
### 7 - Team Interaction Modes
  Choose specific team interaction modes to enhance software delivery.
  Choose between three team interaction modes—collaboration, X-as-a-Service, and facilitating—to help teams provide and evolve services to other teams.
  Collaboration can be a powerful driver for innovation but can also reduce flow.
  X-as-a-Service can help other teams deliver quickly but only if the boundary is suitable.
  Facilitating helps to avoid cross-team challenges and detects problems. 
  
  The Three Essential Team Interaction Modes
  Collaboration: working closely together with another team
  X-as-a-Service: consuming or providing something with minimal collaboration
  Facilitating: helping (or being helped by) another team to clear impediments
  
  Collaboration: two teams work closely together for a defined period to discover new patterns, approaches, and limitations. Responsibility is shared and boundaries blurred, but problems are solved rapidly and the organization learns quickly.
  X-as-a-Service: one team consumes something (such as a service or an API) provided “as a service” from another team. Responsibilities are clearly delineated and—if the boundary is effective—the consuming team can deliver rapidly. The team providing the service seeks to make their service as easy to consume as possible.
  Facilitating: one team helps another team to learn or adopt new approaches for a defined period of time. The team providing the facilitation aims to make the other team self-sufficient as soon as possible, while the team receiving the facilitation has an open-minded attitude to learning.
  Collaboration outside these 3 core interaction modes are wasteful and indicative of poorly chosen team responsibility boundaries and poorly understood team purposes
  
  Collaboration is expensive. Unnecessary collaboration is particularly expensive, especially as it can mask or hide deficiencies in underlying platforms or capabilities. Any ongoing collaboration activity must, therefore, be justified as valuable discovery, valuable capability building, or valuable deficiency-filling activity.
### 8 - Evolve Team Structures with Organizational Sensing
  Use different team topologies simultaneously for strategic advantage.
  Change team topologies and team interactions to accelerate adoption of new approaches.
  Differentiate between explore, exploit, sustain, retire phases using team topologies.
  Expect multiple, simultaneous team topologies to meet different needs.
  Recognize triggers for organization change.
  Treat operations as high-fidelity sensory input for self-steering. 
  
  Team Topologies:
  1. Conway's Law
  2. Team First
  3. 4 Fundamental Toplogies
  4. Tea Interaction Modes
  5. Team API
  6. Topology Evolution
  7. Organizational Sensing
## Conclusion: The Next-Generation Digital Operating Model
### Notes
Combine a team-first approach with Conway’s law, the four fundamental topologies, team interaction modes, topology evolution, and organizational sensing.
Get started: begin with the team, identify streams, identify the thinnest viable platform, identify capability gaps, and practice team interactions

Next Steps: How to Get Started with Team Topologies

1: Start with the Team

First, as an organization ask yourself: What does the team need in order to:
Act and operate as an effective team?
Own part of the software effectively?
Focus on meeting the needs of users?
Reduce unnecessary cognitive load?
Consume and provide software and information to other teams

2: Identify Suitable Streams of Change

Each organization needs to choose a set of change streams that act as “pipes” down which the most important changes flow. These streams are the main focus for flow within the organization, and all other work within the organization takes place to help flow within these streams (directly or indirectly). Exactly what is chosen for the streams depends very much on the nature of the organization, but some typical streams might be

3: Identify a Thinnest Viable Platform (TVP)

After you have identified the most relevant streams for your organization, identify the services needed to support a reliable, swift flow of change in those streams. In practice, these services will form the platform on which the streams depend, but as we noted in Chapter 5, a platform does not have to be a huge, expensive investment. On the contrary, a platform can be “just big enough” to meet the flow needs for the streams:

4: Identify Capability Gaps in Team Coaching, Mentoring, Service Management, and Documentation
Team coaching
Mentoring (especially of senior staff)
Service management (for all kinds of teams and areas, not just for production systems)
Well-written documentation
Process improvement

5: Share and Practice Different Interaction Modes and Explain Principles behind New Ways of Working
## [Official site](https://teamtopologies.com/)
## [DevOps Topologies](https://web.devopstopologies.com/)
