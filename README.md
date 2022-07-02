                           Practice Exam   

Lesson4c: Requirements 3
1.	How do we communicate requirement? Key diagrams used?
1.1.	Activity diagram
1.2.	State machine diagram
1.3.	…
1.4.	Question: Which one of the following will NOT be useful for        Communicating Software requirements:
1.4.1.	Deployment diagram
1.4.2.	Activity diagram
1.4.3.	Component diagram
2.	Question: What are NFRs? Name some NFRs
2.1.	Performance
2.2.	Security
2.3.	Availability
2.4.	Usability
2.5.	Scalability
2.6.	…
3.	…

Lesson5: Analysis/Design
1.	What is Domain modeling?
1.1.	It is process of identifying business domain objects needed for software system and the relationship between them.
2.	Artifacts – What are the main artifacts created from performing Object-oriented analysis/design
2.1.	Class diagram
2.2.	Sequence diagram
2.3.	
3.	Domain-Driven Design – DDD – enables accurate/true representation of the business process in a model form
4.	Domain objects/entities – classes that represent the data in the system
5.	Value Objects – objects that serve sole purpose of carrying data; no identity; they typically immutable
6.	Service components – typical where business/application logic is implemented; usually contains business rules and computation.
7.	Data Access components – responsible fetching/persisting data to the backend database/data store
8.	…

Lesson6: Architecture
1.	What is Software Architecture? – higher-level structure of components that make-up a software system. 
2.	Architectural styles
2.1.	Layering (i.e. layered architecture) – SoC: Separation of Concerns, MVC: Model-View-Controller architectural pattern
2.2.	Component-based architecture
2.3.	OOD – Domain modeling
2.4.	Microservice architecture – is an architectural style that involves decomposing a large software solution into small, self-contained, independently deployable autonomous service.

a.	What is the main difference between Scrum and Kanban?
  Kanban:
i.	Similar to Agile/Scrum but without the Sprints
ii.	Never pass defective products
iii.	In Kanban we do not have a sprint, but we focus on the flow of stories
Scrum:  uses sprints to break down large projects in to smaller manageable projects

b.	 What is the main difference between Scrum and XP?
 XP has more focus on software development best practices, while Scrum has more focus on project management

c.	Agile vs scrum
Scrum is broken down into shorter sprints and smaller deliverables, while in Agile everything is delivered at the end of the project
d.	What is the main difference between Scrum and DevOps?
In Scrum we bring the business and software development together.
In DevOps we bring the business ,software development and operations together.
e.	Explain what use cases and user stories have in common.
    For both you start with the user
 They both give value to the user 
f.	Explain how use cases and user stories are different.
The scope of the user story is much smaller than the scope of a use case
g.	Give 4 reasons why RUP is not very efficient as a software development process
RUP is very document driven
- The iterations are very long
- Every team member has its own role and responsibilities
- RUP has a project manager instead of a self-managing team

Circle all statements that are true:
a. The Scrum master can change the priority of user stories in the product backlog at all
times
b. The daily standup meeting in Scrum is timeboxed at 15 minutes
c. The goal of the sprint retrospective is that upper management gets to see the progress of
the team
d. One task of the Product Owner is to assign tasks to the team members
e. An Epic is a large user story that needs to be split up at a certain time
f. All stories in the user story map contain acceptance criteria.
g. All stories in the user story map are as small as possible so that we can implement them
in a few days or less.
h. The user story map is our product backlog
i. The user story map is our sprint backlog
a.	j. We write at least one scenario for every user story

Give 4 reasons why it is not a good idea to write a large upfront requirements document that
contains all requirements of a system.
- The business does not know all requirement details upfront.
- About 45% of functionality in systems is never used
- Requirements change very often
- Large documents are never read, and are hard to review and understand
- You are never done with requirements
Explain the difference between an iteration in RUP and a sprint in Scrum.
The iteration in Scrum is finished when the use case(s) are finished. Functionality is fixed, time
is flexible

The sprint in Scrum is finished after 1-4 weeks (timeboxed). Time is fixed, functionality is
flexible






1. What is Software Engineering?

Software engineering is defined as a process of analyzing user requirements and then designing, building, and testing software application which will satisfy those requirements.
-----------------------------------------
2. Software Development methodologies: 

2-1 Waterfall : The waterfall methodology is a project management approach that emphasizes a linear progression from beginning to end of a project.
	Linear
	Different roles
	Document driven
	Customer is outside the project
	Large projects(time, nr. of people)
	Req. statements
Rational Unified Process (RUP) is an agile software development methodology. RUP splits the project life cycle into four phases.
	Iterations
	Different roles
	Document driven
	Customer is outside the project
	Large projects(time, nr. of people)
	Use cases
XP: Extreme Programming (XP) is an agile software development framework that aims to produce higher quality software, and higher 	quality of life for the development team.
	Iterations
	Cross-functional team
	face to face
	Customer inside project
	small projects
	user stories
Scrum : Agile scrum methodology is a project management system that relies on incremental development.
	Scrum team including roles :
		 Product owner
		 ScrumMaster
		 Team
	Ceremonies : 
		Sprint planning
		Sprint review
		Sprint retrospective
		Daily scrum meeting
		Product backlog refinement
	Artifacts :
 		Product backlog
		Sprint backlog
		Burndown charts
		Definition of done
                        Impediment list
	Advantages : 
		Increased productivity
		Improved project visibility
		Higher software quality
		Higher customer satisfaction
		Less risks
		Faster time-to-market
	challenges : 
		 The organizational culture needs to change
		 Scaling scrum
		 Scrum does not solve all your problems
		 The Product Owner role is difficult
		 Scrum does not always fit
Lean :Provide perfect value to the customer through a perfect value creation process that has the least amount of waste
	Eliminate Waste
	Amplify Learning
	Decide as late as possible
	Deliver as fast as possible
	Empower the team
Kanban : method is designed to meet minimal resistance. It encourages continuous small incremental and  evolutionary changes to the current process by implementing collaboration and feedback forms. 
	Scrum without fixed iterations(sprints)
DEVOPS : DevOps is a methodology meant to improve work throughout the software development lifecycle.
Close collaboration between developers and operations
	Streamlines the delivery process of software from business requirements to production
	Better communication
	Identical development and production environment
	Shared tools
	Automate everything
	Monitor everything
-----------------------------------------------
3. Question: What is the difference between RUP and Agile/Scrum? 
      While both Scrum and Rational Unified Process (RUP) follow the Agile       framework, 
      RUP involves more formal definition of scope, major milestones,    
      and specific dates (Scrum uses a project backlog instead of scope). 
      In addition, RUP involves four major phases of the project lifecycle 
     (inception, elaboration, construction, and transition), 
      whereas Scrum dictates that the whole “traditional lifecycle” fits into one iteration. 
--------------------------------------------------
4 -  What does RUP and Agile/Scrum have in common?
both Agile methods and UP are Iterative and Incremental Development (IID) methods
---------------------------------------------------
5 - Git is a free and open source distributed version control system 
    designed to handle everything from small to very large projects with speed and efficiency.
---------------------------------------------------
6- Git is a version control system that lets you manage and keep track of your source code history. Coordinate work on those files among multiple people
 GitHub is a cloud-based hosting service that lets you manage Git repositories
-----------------------------------------------------
7 - A software requirement can be of 3 types:
Functional requirements.
Non-functional requirements.
Domain requirements.
----------------------------------------------------
Agile requirments : 
1. Define document properties
2. Communicate the overall goals
5. User Stories
6. User interaction and design
----------------------------------------------------
User story. What is the standard format for specifying : 
A user story is usually written from the user's perspective
 and follows the format: “As [a user persona], 
I want [to perform this action] so that [I can accomplish this goal].”
---------------------------------------------------
2.	Characteristics of Good User Stories (INVEST); 
2.1.	Independent
2.2.	Negotiable
2.3.	Valuable
2.4.	Estimable
2.5.	Small
2.6.	Testable
---------------------------------------------------
The user story should have the following qualities:
Be complete enough to demonstrate user value.
Be user-centric.
Start with an epic.
Be short, simple, and clear.
Scenario;  With the regards to use-cases; what is a scenario? What is a flow?
A scenario is a single path through a use case. A flow is a set of scenarios that result in the same sort of outcome.
--------------------------------------------------------------
User story Map : 
User story mapping is a visual exercise that helps product managers 
and their development teams define the work that will create the most delightful user experience.
-----------------------------------------------------------
Acceptance Criteria : In Agile, acceptance criteria refer to a 
set of predefined requirements that must be met to mark a user story complete.
------------------------------------------------------------
Sppliting story :  Story splitting is the process of breaking 
one single user story into smaller stories. However, 
it's not about breaking it into component tasks, but rather 
complete stories or slices that still deliver value to the user.
-----------------------------------------------------------
User stories estimation
Story points represent the relative sizing of the user story.
 It is a unit of estimation used by Agile teams to estimate User Stories.
 When the product owner wants some features to be developed he/she desires
 to know how soon the team can complete the features and how many resources it will take to complete the work.
--------------------------------------------------------------
User stories estimation
Story points represent the relative sizing of the user story. 
It is a unit of estimation used by Agile teams to estimate User Stories. 
When the product owner wants some features to be developed he/she desires 
to know how soon the team can complete the features and how many resources it will take to complete the work.

1.1.	In Agile, we can Specify software system requirements using:
1.1.1.	Text or statement
1.1.2.	Context diagram:
No connections between external entities
The system is a black box
The context diagram helps you in communicating the
understanding of the system
1.1.3.	Use-cases:
                                      Use cases describe the sequential interaction between the
                                       user and the system to reach a certain goal.
                                      Use cases describe “what” the system does, not “how”.

1.1.4.	User stories:
 User stories are not meant to be complete
 User stories are high level descriptions of the
requirement to be built

Lesson4a/b: Requirements 2 – Agile practices for gathering/specifying requirements
1.	User story. What is the standard format for specifying:
1.1.	As a <role>
1.2.	I want to <goal>
1.3.	So that <outcome>
2.	Characteristics of Good User Stories (INVEST); 
2.1.	Independent
2.2.	Negotiable
2.3.	Valuable
2.4.	Estimable
2.5.	Small
2.6.	Testable
3.	User story map

-Visualize the workflow or value chain
 -Show the relationships of larger stories to their
child stories
 -Help confirm the completeness of your backlog
 -Provide a useful context for prioritization
Advantages:
Improves collaboration
Improves the backlog
Easy to create
 Visualizes the release backlog
 Validation with customers
 Shows the big picture
Helps with prioritization

4.	Main scenario

5.	What is an Acceptance Criteria?
Acceptance criteria define when the user story is done.
 They contain the details of the behaviour of the system
 They serve to record the decisions made in the
conversation
They are the input for testing the user story
6.	UI
7.	Splitting of User stories
User stories have to give business value to the user, so if it is too big it should be splitted.
Splitting user story patterns:
                 Workflow steps
                 Operations
                 CRUD:create ,read, update , delete
                 Business rule variation
                 Simple/complex
                 Variation in data
                 Effort
                 Interface variation
      Defer quality


------------------------------------------------------------------------------------------------------
Name some NFRs
Security
Reliability
Performance
Maintainability
 Scalability
                      usability
---------------------------------------------------------------------
Domain-driven design (DDD) is a software design approach focusing 
on modelling software to match a domain according to input from that domain's experts.
----------------------------------------------------
Domain Modeling is a way to describe and model real world entities
and the relationships between them, which collectively describe the problem domain space.
-------------------------------------------------------------------
Software architecture refers to the fundamental structures of a software system 
and the discipline of creating such structures and systems.
--------------------------------------------------------------------------
Software architecture styles : 
Domain Driven Design
Layering
Object oriented
Component based
Microservices
---------------------------------------------------------------------------
What is the difference between Loose-Coupling versus Tight
Coupling? Give example(s). 

Tight coupling means classes and objects are dependent on one another. 
In general, tight coupling is usually not good because it reduces the flexibility 
and re-usability of the code while Loose coupling means reducing the dependencies 
of a class that uses the different class directly.
example : If you change your shirt, then you are not forced
to change your body – when you can do that, then you have loose coupling.
When you can't do that, then you have tight coupling.
--------------------------------------------------------------------------------
What is SOA? 
service-oriented architecture, defines a way to make software components reusable and interoperable via service interfaces
People : employee decision makers / platform : increase operational efficiency / practice :
 emplot best practice methodology / process : aligne it with business operation 

----------------------------------


Lesson7: Design
1. Domain entities : Entities are Domain concepts that have a unique identity in the problem domain. They are mutable , state can be changed after instantiation.
2. Value objects : value object is a small object that represents a simple entity whose equality is not based on identity. They are immutable can not be changed after instantiation.
3. Domain Services : Domain Services stores centralized directory information and lets users and domains communicate.
4. Data Access objects : data access object (DAO) 
   is a pattern that provides an abstract interface to some type of database or other persistence mechanism.
5. Domain events
7. What are the SOLID principles for OO software Design? 
-high Cohesion , lose coupling 
-Encapsulation
-Flexibility
-Reusability

----------------------------
Clean code is a reader-focused development style that produces software that's easy to write, read and maintain. 
Clean Code best practices for:
a.	Classes, Variable
b.	Methods
c.	Commenting






 

