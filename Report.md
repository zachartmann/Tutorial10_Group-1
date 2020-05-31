# **31257 Information System Development Methodologies - Project Report**

Executive Summary
=================
This report presents the definition, analysis, and design of an improved information system solution for the call management centre (CMC) of a major travel company. The Design Thinking principles and agile methodology (Scrum) used are discussed, and iterative progress is documented on GitHub. By first defining the problem the team can acquire great insight into the issue at hand and the objectives and milestones to be achieved. Identifying the key stakeholders will allow the team to understand their target audience and collate opinions, ideas and thoughts to further analyse motives and expectations; the Design Thinking principles will aid in framing the team's approach. Assumptions are then made by the team in order to fill in minor gaps and allow fluidity when conducting iterations. Along with documenting assumptions, overall planning is highly important in any project (especially one of technical nature), which is why there are many models and diagrams before implementation. Finally, recognising the competitive advantages that may be gained in developing the new system, helps stakeholders see the ultimate value and goal of what needs to change and grow within their business and why they are even investing in this project.

Link to Project GitHub repository: [Tutorial10_Group-1](https://github.com/zacaz90/Tutorial10_Group-1)

Problem Definition
==================
Customer experience is heavily impacted because of the call flow rate in the (CMC), as customers are not being assigned to well informed RMs that have the most appropriate knowledge about that particular holiday destination and its traditions i.e. their skillset. This, in turn, is impacting RMs performance in selling packages and serving customers effectively and efficiently.  

There is also no defined guideline for RMs to approach outbound calls, which affects the service provided to the end customer. High costs associated with inbound calls from customers due to the per-call handling time is also of concern. 

Furthermore, a key issue faced by customers is waiting times during busy times. This can have a negative impact on the major travel company’s brand and make them potentially lose customers. 

## **Objectives**

This project is designed to help the major travel company develop an information system to improve the functionality of their in-house Call Management Centre. This is done by adjusting the call flow rate to match customers to a suitable relationship manager, based on their skillset, product knowledge and profile. The aim is to improve the customer experience and satisfaction. Ultimately the objective is to increase the sales of holiday packages adding to the profitability and provide better assistance to relationship managers performing sales.

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

* **Customers** - explore and purchase holiday packages from the travel company via the CMC
* **Relationship Managers (RMs)** - perform sales of holiday packages through inbound/outbound customer calls
* **Travel Company** - attempts to make profit utilising the CMC to sell holiday packages, controls key business functions (e.g. operational expenses, human resources)

## **Point of View (POV) Statements**
### Customers
* Customers calling the travel company need to  have their call answered in a timely manner because the current situation has customers waiting on the phone with no RM callback
* Customers speaking to a Relationship Manager need to be  matched with an RM who has the required language proficiency because the current situation has customers being inadequately paired with RMs who don’t meet skill/language requirements
* Customers with little travelling experience need to  call an RM capable of assisting them in finding a package to suit their needs because in the current situation, some customers are finding imperfect packages due to inadequate RM matching

### Travel Company
* Travel Company managing RM staff needs to determine which staff members are underperforming (reaching KPIs) because the current situation does not have a system with KPI tracking capabilities
* Travel Company need to manage incoming calls so that additional call costs do not impact company budget because the current situation does not have a system which effectively manages incoming calls (without unforeseen impacts to potential end-users)
* Travel Company managing customer relations needs to improve CMC operation and call flow rate because currently, customers are complaining about wait times
* Travel Company managing customer relations needs to to profile RMs because RMs are not being matched effectively with customers being served

### Relationship Managers
* Relationship Managers need to serve customers that match their skill set and knowledge because, in the current situation, some RMs do not have the required knowledge to best server calling customers
* Relationship Managers need the system to provide guidelines/script for outbound calls to ensure high-quality customer service because in the current situation, there is no defined way to approach these calls
* Relationship Managers need to have an established profile (depending on the age, sex, culture, language proficiency, experience and product knowledge) because in the current situation, customers are allocated based only on RM’s expertise

## **Empathy Maps**
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
Enhance Interactive Voice Response unit | Gain initial understanding of customer needs without the need for an in-person RM answering the call. We concluded that other ideas such as playing ads while customers were on hold would be ineffective as it would lead to negative customer experience.
Improve RM questionnaire  | Allows better initial classification of the RM by providing more parameters for the CMC to score by.
Added internal wiki of further package information | This was decided to be the best way to have all RMs confident with all packages, so they are more likely to make a sale to customers even if they lack experience with the destination.
Feedback tool implemented  | Customer feedback tool was added so that the CMC can implement RM scoring in real-time after the call is undertaken.
Enhanced RM guidelines  | Natural language processing is embedded in the CMC to enhance the autogenerated RM scripts to increase sale chances. 

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
Use case diagrams help to visualise the expected behaviour of the interactions between the users (Customers), the system and other actors (i.e. Relationship Managers) and describes system behaviour but not how it will be done. Thus use case diagrams assists us in designing a system from the end user's perspective. The diagrams below show this in regards to outbound and inbound calls respectively:
### Use Case Diagram - Outbound Calls
![Image of Use Case Diagram (Outbound Call)](./diagrams/UseCaseDiagram-OutboundCall.png)

### Use Case Diagram - Inbound Calls
![Image of Use Case Diagram (Inbound Call)](./diagrams/UseCaseDiagram-InboundCall.png)

## **Activity Diagrams**
These diagrams help to visualise the behaviour of the system and actors across multiple use cases including decisions and the flow of events (still not describing the how). The diagrams below show this in regards to outbound and inbound calls respectively:
### Activity Diagram - Outbound Calls
![Image of Travel Company Activity Diagram (Outbound Call)](./diagrams/ActivityDiagram-OutboundCall.png)

### Activity Diagram - Inbound Calls
![Image of Travel Company Activity Diagram (Inbound Call)](./diagrams/ActivityDiagram-InboundCall.png)

## **Class Diagram**
This diagram represents the structure of the classes involved in the wider system. It displays their attributes and methods as well as the relationships that are between them, such as below:

![Image of Class Diagram](./diagrams/ClassDiagram.png)

## **Collaboration Diagrams**
These diagrams represents the dynamic behaviour of objects and the structure of the interactions between them. It also displays the sequence of these interactions through numbering; however, focuses more on the messages that flow between each object rather than time-based interactions (seen in sequences diagrams). The diagrams below show this in regards to outbound and inbound calls respectively:
### Collaboration Diagram - Outbound Calls
![Image of Collaboration Diagram (Outbound Call)](./diagrams/CollaborationDiagram-RM.png)

### Collaboration Diagram - Inbound Calls
![Image of Collaborative Diagram (Inbound Call)](./diagrams/CollaborationDiagram-Customer.png)

Potential Advantages and Disadvantages
======================================
## **Competitive Advantage**
Developing this new information system, if successful, will lead to a plethora of competitive advantages against other major travel companies looking to increase their customer loyalty or retention. Currently, the CMC (Call Management Centre) has reduced operating efficiency due to call flow control and call routing issues. This leads to some customers having long wait times and drives up the inbound call cost of the CMC. Through the information system's implementation, these areas could be improved and provide many advantages.

Lessening the call flow control/routing issues through the development of the new information system will reduce wait times for customers and provide more effective matches with RMs (Relationship Managers). This enhancement in user experience will improve customer retention, as they see changes being made in the system for their benefit. In addition, implementing an easier method of feedback elicitation could lead to a large uptake in customer loyalty due to their opinions being taken into consideration. The above points will inadvertently put greater pressure on competitors to keep up, providing an extraordinary competitive advantage.

From a more business-centric point of view, the travel company will save costs in handling the increasing customer base. This is due to the information system's ability to reduce per-call handling time, which reduces inbound call costs.

## **Possible Effects of Project Failure**
If the information system is ineffective, there are some considerable adverse effects to take into account. Ranging from the loss of customers to increased operating costs for no benefit, the adverse effects possible should be weighed into consideration alongside the competitive advantages to most accurately evaluate the possible result of the information system.

By communicating to users that the travel company is implementing a solution to their biggest issues, there is an inherent risk if we fail to deliver. If the solution fails to meet expectation, customers may feel rightly disappointed particularly if these issues have been ongoing. There is a high risk that they may cease interaction with the travel company and move on to a competitor - a huge competitive disadvantage.

Additionally, there is a small risk that the increase in tasks performed by the CMC may decrease its effectiveness. This would provide a run-on effect, whereby the CMC is not only slower but expected to be faster too. This lower efficiency would lead to higher inbound call costs and reduced call flow handling.

Conclusion
==========

In conclusion, it is recommended that this major travel company implement the new features designed/described in this report. Appropriate Design Thinking principles and Scrum framework have been applied to effectively analyse the company's current situation and develop both non-technical (Use Case Diagrams, Activity Diagrams) and technical (Class Diagram, Collaboration Diagrams) models for development of the enhanced information system. Upon implementation, the major travel company will likely benefit from increased relationship manager efficiency and customer satisfaction.
