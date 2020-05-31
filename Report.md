# **31257 Information System Development Methodologies - Project Report**

Executive Summary
=================
This report presents the definition, analysis, and design of an improved information system solution for the call management centre (CMC) of a major travel company. The Design Thinking principles and agile methodology (Scrum) used are discussed, and iterative progress is documented on GitHub. By first defining the problem the team can acquire great insight into the issue at hand and the objectives and milestones to be achieved. Identifying the key stakeholders will allow the team to understand their target audience and collate opinions, ideas and thoughts to further analyse motives and expectations; the Design Thinking principles will aid in framing the team's approach. Assumptions are then made by the team in order to fill in minor gaps and allow fluidity when conducting iterations. Along with documenting assumptions, overall planning is highly important in any project (especially one of technical nature), which is why there are many models and diagrams before implementation. Finally, recognising the competitive advantages that may be gained in developing the new system, helps stakeholders see the ultimate value and goal of what needs to change and grow within their business and why they are even investing in this project.

Link to Project GitHub repository: [Tutorial10_Group-1](https://github.com/zacaz90/Tutorial10_Group-1)

Problem Definition
==================
* The current Call Management Centre provides suboptimal:
  * Waiting times
  * RM to customer matching (mismatch)
  * Prioritisation of customers
  * Inbound call costs
* The Call Management Centre currently provides a suboptimal user experience, due to wait times and poor customer-RM matching, leading to user disatisfaction

## **Objectives**
* Develop an information to improve operation of the Call Management Centre
* Adjust call flow-rate to Relationship Managers
* Improving profitability and customer satisfaction
* Match RMs and end-customers according to RMs skills and customer profiles

## **Assumptions**
In the duration of this project the following assumption's were considered in all system analysis and feature recommendations. 

* The CMC has enough processing power to handle complex computations and algorithms.
* The CMC is already equipped with all data with information such as a customer database with information such as postcodes and surnames.
* Employee’s within Major Travel Company have appropriate product knowledge and understanding of the operations within the CMC.
* The functionality of the inbuilt profiler tool includes customer profile generation and allows the CMC to auto-generate a generic list of customers for specified Relationship Managers (RMs).
* The details elicited from the RM questionaire includes RM’s age, sex, culture, language proficiency, experience and product knowledge. 
* The CMC autogenerates generic scripts and guidelines to assist RM sales.
* The current interactive response unit has limited functionality to ensure customer retention with no hold music or ticketing system during peak traffic. 

## **List of Stakeholders**
Stakeholders refer to individuals/entities that have an interest in the development of an information system. The key stakeholders of this project are:

* Customers
* Relationship Managers (RMs)
* Travel Company

## **Point of View (POV) Statements**
### Customers
* Customers calling the travel company need to  have their call answered in a timely manner because current situation has customers waiting on the phone with no RM callback
* Customers speaking to a Relationship Manager need to be  matched with an RM who has the required language proficiency because current situation has customers being inadequately paired with RMs who don’t meet skill/language requirements.
* Customers with little travelling experience need to  call an RM capable of assisting them in finding a package to suit their needs because in the current situation, some customers are finding imperfect packages due to inadequate RM matching

### Travel Company
* Travel Company managing RM staff need to determine which staff members are underperforming in  regards to reaching their KPIs because current situation doesn’t have a system with the capabilities of KPI tracking
* Travel Company managing incoming calls need to manage incoming calls so that no additional call costs impact company budget because the current situation doesn’t have a system which effectively manages incoming calls without causing unforeseen impacts to potential end-users 
* Travel Company managing customer relations need to improve CMC operation and call flow rate because currently, customers are complaining about wait times
* Travel Company managing customer relations need to To profile RMs because RMs are not being matched effectively with customers being served

### Relationship Managers
* Relationship Managers need to serve customers that match their skill set and knowledge because in the current situation, some RMs do not have the required knowledge to best server calling customers
* Relationship Managers need the system to provide guidelines and script for outbound calls to ensure quality best customer service because in the current situation there is not a defined way for how to approach these calls
* Relationship Managers need to have an established profile (depending on the age, sex, culture, language proficiency, experience and product knowledge) because in the current situation, customers are allocated based on RM’s expertise 

## **Empathy Maps**
Empathy maps help immerse us in our stakeholders' environment in order to better understand them. The empathy map for customers, relationship managers and the major travel company, in order, follow:
### Empathy Map - Customers
![Image of Customers Empathy Map](./diagrams/EmpathyMap-Customer.png)

### Empathy Map - Relationship Managers
![Image of Relationship Managers Empathy Map](./diagrams/EmpathyMap-RM.png)

### Empathy Map - Travel Company
![Image of Travel Company Empathy Map](./diagrams/EmpathyMap-TravelCompany.png)

Design Thinking Approach
========================
## **Approach - Design Thinking**
Design thinking is a non-linear, iterative process which seeks the understanding of users to challenge assumptions, redefine problems and create innovative solutions to prototype and test. This customer-centric approach was undertaken to address the improvements requested by the Major Travel Company for their Call Management Centre (CMC). The design thinking approach undertook consists of the execution of five phases, (1) empathize, (2) define, (3) ideate, (4) prototype and (5) test and by addressing these phases we derived customer-centric innovation. 

### Empathise
Phase one consisted of empathising with stakeholders. This represents anyone who is impacted by the project being developed with a particular focus extended on the end customer. Empathy is a crucial step in achieving a human-centred design process and was utilised to gain insight into users and their needs without introducing any pre imposed bias. When we create solutions, we get better solutions when we think of those who will be affected. To document these perspectives, empathy maps were utilised to collaboratively visualise and share our understanding of stakeholders needs and aid future decision making. This stage allowed us to gain a deeper understanding of the perspective of the users involved and how to shape our solution. 

### Define
Phase two, define allowed us to synthesise the knowledge obtained in the empathise stage and define the core problems to solve. Here the problem statements were directly derived from creating point of view (POV) statements for all the stakeholders identified. This stage allowed us as a team to consolidate assumptions and agree on features to be developed to solve the problem given. 

### Ideate
Phase three consisted of utilising the user research conducted to ideate solutions to the problem statements we created in the prior stage. The brainstorming and 'worst possible idea' techniques were utilised to assist within our ideation stage. These techniques were chosen to initiate freeform group discussions and simulated creative solutions in light of the problems identified. These sessions consisted of developing “how might we? (HMW)” statements and deriving features relative to the point of view statements developed in the define stage. The conclusions of the brainstormed features were documented into git via issues. At the conclusion of this stage, the agreed-upon features were converted to issues to be developed for the prototype and testing stage. 

### Prototype/Test
The prototype and subsequent testing phase is representative of the final stages within the design thinking approach. This consists of producing a small-scaled, mock-up of the product or specific features found within the product so that tangible investigations can occur on the solutions generated in the previous stage. To assist in the prototype stage the team designed artefacts representative of the design of the system. The user flows are demonstrated within the use case diagram, activity diagrams, class diagram and collaborative diagrams provided. Due to the nature of this project, the prototype and respective testing are not within scope. 

### Artefacts
Artefact | Description
---|---
Empathy Maps | Empathy Maps are used to visualise user attitudes and behaviours. This map is split into 6 quadrants (Says, Thinks, Does, Feels, Pains and Gains).
POV Statements | Point of view statements are statements which focus on the specific user and their needs. These statements represent the team’s results for the define phase.
How might we? (HMW) | How might we statements represent our results of the ideate phase and are short statements built from point of view statements

## **Brainstormed Ideas and Reflection**
The following features were concluded from the brainstorming session. 
Feature | Justification
--- | ---
Enhance Interactive Voice Response unit | Gain initial understanding of customer needs without the need for an in-person RM answering the call. We concluded that other ideas such as playing ads while customers were on hold were abandoned as they would lead to negative customer experience.
Improve RM questionnaire  | Allows better initial classification of the RM by providing more parameters for the CMC to score by.
Added internal wiki of further package information | This was decided to be the best way to have all RMs confident with all packages, so they are more likely to make a sale to customers even if they lack experience with the destination.
Feedback tool implemented  | Customer feedback tool was added so that the CMC can implement RM scoring in real-time after the call is undertaken.
Enhanced RM guidelines  | Natural language processing is embedded in the CMC to enhance the autogenerated RM scripts to enhance sale chances. 

The biggest issue we, as a group, faced over the course of our project was our unfamiliarity with GitHub. This took out a portion of each group meeting, as we had to spend time figuring out a correct and consistent workflow. Another issue we found was the lack of face-to-face communication due to COVID-19. This was especially prevalent when filming the video as collating everyone’s individual video and editing became very complicated.

## **How Might We (HMW) Statements**
### End-Customer
* HMW better reach customers who have been on hold for an extended period of time.
* HMW better match customers to RMs so they have a high quality of customer service.
* HMW better match RMs with customers so they can find perfect packages.
* HMW prevent customers from hanging up.
* HMW better communicate with customers to lock down deals within a minimal call time.

### Relationship Managers
* HMW profile RMs, so they are matched effectively to customers served.
* HMW match more knowledgeable RMs to specific customers.
* HMW better allocate customers based on RM expertise

### Travel Company
* HMW monitor KPIs.
* HMW manage incoming calls so that they do not add additional costs to the travel company by occupying human resources (Relationship Managers).

## **Agile Methodology - Scrum**
Scrum is the most widely used agile methodology for software design and development. The framework assumes that requirements and processes constantly/ unpredictably change which is often the case in real-world scenarios. Requirements are developed and reviewed iteratively to allow for greater adaptability to changes in client needs, technological advancements, and other environmental factors (e.g. global pandemics).

### Roles
Scrum teams are self-organising and cross-functional meaning they are independent and trusted to complete work as they see fit. The nature of this project required the product owner and scrum master to double as members of the development team.

Role | Team Member | Responsibilities
--- | --- | ---
Product Owner | Zac | Establishes, communicates, and monitors the progress of the product vision including defining and prioritising features to be developed.
Scrum Master | Aiswarya | Facilitates scrum team events and promotes scrum theory, rules, and practices.
Development team | Anastasia, Sanya, Sean | Builds and delivers a working increment of the project in every sprint.

### Events/Activities
A sprint is a fixed period of time after which a deliverable iteration of a product must be developed. The following activities were conducted in each of our team's 1-week sprints (Sunday to Friday).

Event | Description
--- | ---
Sprint Planning | Conducted on the first day of each sprint, these meetings established and reviewed backlog tasks/issues/goals for the current sprint. Tasks were assigned to members and moved to “Ready for dev” on the project board.
Sprint Review | Every Friday, the development team explained and delivered their work for the sprint. This progress was evaluated and tasks left to complete were determined.
Sprint Retrospective | After each sprint review, we re-evaluated and improved/resolved our workflow, communication, and other issues that arose during the sprint.
Daily Scrum | Each day, progress updates and issues were discussed and resolved. Due to our team’s clashing schedules, most daily scrum meetings were agreed to be communicated over text.


### Artefacts
Artefact | Description
---|---
Product Backlog | Prioritised list of all tasks/requirements for a product.
Sprint Backlog | Subset of the Product Backlog for development during a sprint.
Product Increment | Potentially shippable version of the product built each sprint.
Sprint Burndown Chart | Graphical representation of development progress over time (backlog items completed).

Workproducts and Models
=======================
## **Use Case Diagrams**
Use case diagrams help visualise the expected behaviour of interactions between users, the system and other actors. By describing behaviour, but not inner-workings, it helps design the system from the user's perspective. The diagrams below show this in regards to outbound and inbound calls respectively:
### Use Case Diagram - Outbound Calls
![Image of Use Case Diagram (Outbound Call)](./diagrams/UseCaseDiagram-OutboundCall.png)

### Use Case Diagram - Inbound Calls
![Image of Use Case Diagram (Inbound Call)](./diagrams/UseCaseDiagram-InboundCall.png)

## **Activity Diagrams**
Activity diagrams help to visualise the behaviour of the system and actors across multiple use cases, including decisions and the flow of what happens, without the how. The diagrams below show this in regards to outbound and inbound calls respectively:
### Activity Diagram - Outbound Calls
![Image of Travel Company Activity Diagram (Outbound Call)](./diagrams/ActivityDiagram-OutboundCall.png)

### Activity Diagram - Inbound Calls
![Image of Travel Company Activity Diagram (Inbound Call)](./diagrams/ActivityDiagram-InboundCall.png)

## **Class Diagram**
Class diagrams represent the structure of the classes involved in the system. It displays their attributes, methods and relationships between classes, such as below:
![Image of Class Diagram](./diagrams/ClassDiagram.png)

## **Collaboration Diagrams**
Collaboration diagrams represent the dynamic behaviour of objects and the structure of the interactions between them. It also displays the sequence of the interactions, focusing more on the messages that flow between objects than time-bised interactions. The collaboration diagrams for outbound and inbound calls, respectively, can be seen below:
### Collaboration Diagram - Outbound Calls
![Image of Collaboration Diagram (Outbound Call)](./diagrams/CollaborationDiagram-RM.png)

### Collaboration Diagram - Inbound Calls
![Image of Collaborative Diagram (Inbound Call)](./diagrams/CollaborationDiagram-Customer.png)

Potential Advantages and Disadvantages
======================================
## **Competitive Advantage**
Developing this information system will lead to many competitive advantages; if successful. Currently, the Call Management Center (CMC) has issues in its call flow control and call routing. These issues lead to customers having long wait times, which in turn drives up inbound call costs for the CMC.

Lessening the call flow control/routing issues will directly reduce wait times and provide more effective matches with RMs. Consequently, the travel company will save costs in handling customers due to reduced per-call handling time. As the new information system is making changes for the customer's benefit, it will result in improved customer retention. Additionally, implementing an easier method of feedback elicitation could lead to greater customer loyalty, as they can effortlessly raise concerns. Furthermore, the travel company will save costs in handling customers due to the information system's ability to reduce per-call handling time.
These benefits will put greater pressure on competitors to keep up, providing an extraordinary advantage.

## **Possible Effects of Project Failure**
Producing an ineffective information system will lead to considerable adverse effects. From the loss of customers to increased operating costs, the adverse effects should be weighed into consideration alongside the advantages to must accurately evaluate the possible result of the information system.

Communicating to customers that the travel company is implementing a solution to their issues, and then failing to meet expectations, will cause customers to feel rightly disappointed. Additionally, there is a small risk that the CMC will decrease its effectiveness due to the increase in tasks added by the information system. This lowered efficiency will actually increase inbound call costs and reduce call flow handling.
Via the many detriments listed above, the failure of this project may cause customers to cease interaction with the travel company and move on to a competitor - a huge competitive disadvantage.

Conclusion *or* Explanation of each iteration intention, rationale, focus?
==========
8. Document in GitHub all your iteration and models as you progress.

Recording the intention, rationale, and focus of each system’s development iteration using Github’s commit messages, project boards, and issue tracking capabilities
