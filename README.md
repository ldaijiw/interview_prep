# Interview Preparation


## Agile and Scrum Questions

**WHAT IS AGILE?**

- Agile is a methodology often applied to software development, with a focus on continuous delivery of incremental changes in small timeframes of a few weeks, rather than delivering a monumental change after a year.
- In general, the Agile manifesto favours interactions and collaborations between developers and customers, with a flexibility to change throughout the course of development.
- For example, as a result of the consideration of these principles, I have a weekly 121 meeting with my trainer in which we discuss ways for both of us to improve at our respective roles.
- This is drastically more beneficial than a quarterly performance review as I can work on smaller improvements each week instead of changing everything after a few months.

**WHAT IS SCRUM?**

- Scrum is a framework centered around continuous improvement, which also happens to be a core principle of agile.
- Work is completed in short timeframes also known as sprints, in which the team clearly lays out what has to be done, without necessarily having to worry about the big picture
- Scrum is structured to allow teams to adapt to changing conditions and user requirements 
- For example, we use an agile board throughout our training to keep a list of subjects we will eventually cover, with a sprint backlog containing more specific topics to complete for the week.
- This way we can focus all of our energy on what needs to be done in the week, without having to be concerned of what we'll do in a week or two

**WHAT IS THE DIFFERENCE BETWEEN AGILE AND SCRUM?**

- Agile is a methodology and mindset with principles and ideals, whereas Scrum is an actual framework for getting work done.
- There are many frameworks that could fit with the Agile methodology

**WHAT ARE THE 3 AMIGOS**

- The 3 Amigos is the grouping of 3 types of people:
    - Business analysts, who consider the product requirements
    - Developers, who consider the actual code to meet these requirements
    - Testers, who discuss test cases to ensure the reliability and quality of the code
- The 3 Amigos may have meetings from 30 to 60 minutes to discuss the aspects of a user story and ensure everyone is on the same page, each person understanding exactly what they have to do.

**WHAT ARE SCRUM ROLES, ARTIFACTS, AND CEREMONIES**

- There are 3 Scrum Roles within a team:
    - Product Owner, focused on understanding the business, customer, and market requirements and prioritising work accordingly
    - Development team, team of developers who build the actual code to meet the product requirements, and forecast how much work to complete with each sprint
    - Scrum Master, focused on ensuring optimising work flow for the team, and bridging the gap between the product owner and the development team

- There are 3 Scrum Artifacts used:
    - Product backlog, maintained by the Product Owner, contains an everchanging list of requirements, that may be re-prioritised as the market and demand for items may change
    - Sprint backlog, list of user stories or bug fixes that the development set out to complete in the current sprint cycle, these items are selected from the product backlog
    - Increment (sprint goal), refers to the usable end-product from a sprint, often referred to as the team's 'definition of done'

- There are 4 main Scrum ceremonies:
    - Sprint Planning, meeting at the beginning of each sprint to define the sprint goal
    - Daily stand up, short meeting every day to ensure everyone is on the same page, and voice any concerns or blockers that may have to be addressed before continuing
    - Sprint review, team showcases their increment at the end of the sprint to stakeholders for feedback
    - Sprint retrospective, where the team discuss what worked well and what needs to be improved for the next sprint.

**WHAT ARE THE DIFFERENCES BETWEEN AGILE, V-MODEL, WATERFALL; AS WELL AS THEIR USE CASES?**

- The Waterfall methodology is a linear project management approach, where stakeholder and customer requirements are gathered at the beginning of the project, and then a sequential project plan is created to accomate those requirements
- The V-Model, also known as Verification and Validation Model, is a type of SDLC model based on the association of a testing phase for each corresponding development stage
- V-Model is especially useful for ensuring a high quality end product due to the quality assurance measures throughout it's lifecycle
- Waterfall has a relatively simple structure with clearly defined project phases with costs and workload estimated at the beginning of the project, however errors can sometimes be recognised only by the end of the development process
- Both of these methodologies are also rigid, they lack flexibility and makes it hard for teams to adapt and improve their direction along the way, whereas Agile is fast to deliver small increments and allows room for flexibility.

## SQL Questions

**WHAT IS A FOREIGN KEY**

- A foreign key is a primary key that exists in a separate table, which builds the relationship to the primary table.

**WHAT IS DML/DDL**

- DML is Data Manipulation Language, referring to the group of commands that allow several actions with an SQL database: select, insert, update, delete
- DDL is Data Definition Language is a standard for commands to define different structures in a database, common commands include: create, alter, drop, truncate

## Python Questions

**WHAT IS OOP AND THE FOUR PILLARS**

- Object Oriented Programming is a programming style that focuses on the usage of objects/data, rather than functions and logic
- The 4 pillars of OOP are Inheritance, Encapsulation, Abstraction, Polymorphism
	- Encapsulation involves maintaining a private state within the object, other objects can only interact with the public functions
	- Abstraction is the process of selecting data from a larger pool to select only the relevant details for the object, and is useful to apply the same info without modifying it to other objects
	- Inheritance is the ability for one object to acquire specific properties of another object, allowing methods and attributes to be reused in the new, child class. This helps to implement DRY, don't repeat yourself, as code can be reused multiple times
	- Polymorphism enables us to redefine methods for objects that inherit from another class, allowing for easier modifications for multiple objects that may share the same parent.

**CAN YOU GIVE AN EXAMPLE OF WHEN YOU IMPLEMENTED OOP**

- For a musical project, I'm working on a script that has to be able to quickly switch between different scales of notes of varying frequencies. 
- I implemented OOP to create a note class, that encapsulates all of the useful data about a specific note to itself,  and a scale class that is essentially a collection of notes but has key characteristics that are contained within itself
- OOP allows me to create any scale of any number I want very easily

**WHAT IS TDD AND HOW HAVE YOU USED IT**

- Test driven development employs the usage of specific unit tests that are constructed first, designed to fail, and then code is written to pass these tests
- Once the code has passed every test it is approved and goes live
- A coding exercise in JS with a series of tests to ensure that the game logic was applied correctly. As I was unfamiliar with the code at first, the unit tests helped to break down exactly what was required of me.

## DevOps Questions

**WHAT IS DEVOPS**

- DevOps is a set of practices that combines the development team and operations team to form one group that tackles development and operations together
- DevOps also aims to shorten the lifecycle of software development and provide automated continuous delivery whilst maintaining high quality of software

**WHY DEVOPS**

- As DevOps adopts many of its principles from Agile, changes are made in smaller increments and so fewer problems arise, and those that do tend to be less complex in nature. 
- The usage of many tools from Jenkins to Ansible allowing for continuous delivery allows more energy and time to be spent on innovation and developing new features

**WHY DID YOU CHOOSE DEVOPS**

- Although my primary experience throughout my physics degree was with python working on interesting data analysis and visualisation projects, I've had a variety of work experience from completing an internship at the Educational Technology Department at Imperial to even working as a waiter and barman at a fast paced restaurant in central London.
- Throughout all of these enlightening experiences I've realised I'm always trying to work out more efficient ways to complete tasks, and find methods to automate complicated processes that don't need to be done manually, and the variety has helped me find ways to improve my my communication skills and work with anyone.
- Particularly during my internship I successfully wrote a script to automate a process for teaching staff to drastically reduce the time from potentially 30 minutes down to just 1. The philosophy, mindset, and principles of DevOps really resonated with me.
- The idea of continuous integration and delivery is fascinating to me and feels very intuitive as a method for software development. I feel DevOps is the perfect path for me to follow as I can quickly pick up the necessary skills and then find ways to maximise efficiency and profits even further.


**What are Environments?**

- An environment is where code runs and can be designed for different purposes
- Virtual environments are a particularly useful tool to keep dependencies required by different projects separate and consistent by creating isolated virtual machine/environments for them
- So far we've learned a variety of tools to create virtual environments such as
	- Vagrant and VirtualBox to create and provision V envs locally
	- EC2 with AWS and Ansible to utilise cloud computing

**What is CI/CD?**

- CI stands for Continuous Integration which involves the automated testing of any new code that is written
	- Any time a change is made the code is sent to a testing environment
	- If the new code passes all the tests it is then integrated into the codebase and can move along to the next stage of the pipeline which is CD
- CD stands for continuous delivery, and involves taking code that has been successfully integrated and automatically moving it to a production-like environment, where new features and changes can be observed
	- Teams with mature CI/CD pipelines may opt to include continuous deployment, which is a further stage that involves the automated deployment of code onto the live server, ready for the end-users 
- The main tool we've used to set up pipelines is Jenkins, where we can utilise the source control management of Github to test any new changes that have been pushed to a development branch, and utilising an EC2 instance on AWS as the testing environment  

**What is the Cloud**

- Cloud computing is the on-demand availability of computer system resources, especially data storage and computing power, without direct active management by the user
- The cloud is especially useful as it gives flexibility and options for businesses, allowing them to invest a small amount for the resources they need and nothing more, with the option to expand or reduce as necessary
- This and the shared responsibility model, in which the cloud provider is responsible for the physical security of the cloud and the user is responsible for security within the machines they use in the cloud, allows for significantly reduced initial capital expenditure

**What are the problems DevOps is trying to solve? How are we solving them?**



**What is IAC**

- IAC is infrastructure as code, and is the process of managing and provisioning computer data cenres through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools
- This allows teams to implement DRY: Don't Repeat Yourself to use tools such as Ansible to easily create multiple EC2 instances with a specific configuration instead of repeatedly configuring it in the AWS console
