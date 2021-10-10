![logo](https://user-images.githubusercontent.com/44948387/136674082-18921bd1-b4f5-40d3-81bf-f98028c159c6.png)   <br>

<img src="https://img.shields.io/github/stars/InnoTutor/README?style=social">ᅠ  <img src="https://img.shields.io/github/stars/InnoTutor/Frontend?style=social">ᅠ<img src="https://img.shields.io/github/stars/InnoTutor/Backend?style=social">   ᅠ [![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/InnoTutor/Backend/blob/main/LICENSE) ᅠ   [![Hits-of-Code](https://hitsofcode.com/github/InnoTutor/Backend?branch=main)](https://hitsofcode.com/github/InnoTutor/Backend/view?branch=main)<br><br><br>
**Authors**: Daniil Livitn, Roman Soldatov, Emil Khabibulin, Tasneem Toolba
<br><br>

## What is the goal of this project?
The problem we are trying to solve is to fulfill students’ needs in some hard courses by the help of other students who are/were good at those hard courses, and make the university consider such help as an official student activity so that those students who helped others, get awarded. 
* Build a platform for **Innopolis university** students to share their knowledge, where students that are good in some courses and want to help others know where to inform others about this willingness to help.
* The website needs to manage how each of the students and tutors finds each other, and communicate.
* The built platform should be able to manage meeting schedules, tutors’ and students’ availability.
* The system should handle authentication with **university accounts**.
* The build application needs to award the tutors (university’s students) by the internal university’s currency (**innopoints**) or by discussing other awards with the university itself.

# Requirements
**Technical Stack**: <br>
* **Flutter (FrontEnd)**: UI cross platform applications for Android, IOS , and WEB
  * Visual Studio Code and Android Studio are used as an IDE
  * Link to the repository: [Frontend Repository](https://github.com/InnoTutor/Frontend)
* **Java Spring Boot, Firebase, Docker, PostgeSQL (BackEnd)**: <br>
  * IntelliJ IDEA IDE
  * Link to the repository: [Backend Repository](https://github.com/InnoTutor/Backend)
<br><br>
## Glossary 📝
* **User**: anyone who uses the “InnoTutor” website.
* **Tutor**: a university student who offers help in some academic courses.
* **Student**: a university student who asked for help in some academic courses.
* **Requests list**: user’s list of help requests that he/she uploaded so tutors could see them.
* **Services list**: tutor’s list of courses that he/she is going to teach.
* **CV Card**: some kind of portfolio uploaded by a tutor on the profile. A tutor can specify the subject, description and preferences about online/offline and private/group meetings. A card can be *reserved*, so no one can see it except a tutor. All uploaded **CVs** will be shown in user's **Services list** and in **Tutors list**, if this card was not reserved.
* **Request Card**: a card created by a **student** asking for help for a partiuclar subject with preferences of **session format and type**. Any tutor can rerspond to this request and add a **student** to his/her **My Students** list. A **student** can hide any of his/her cards, so no one can see it. **Request Cards** can be seen in **Students list**, if this card was not hidden.
* **Tutors list**: list of tutors offering their help given their preferences, e.g. online/offline, subject, and whether in a group or not.
* **Students list**: list of students who asked for help, all tutors see those students.
* **My Students**: list of tutor’s students who asked him/her for help. A tutor can manage these students via removing them or creating sessions with them.
* **Session**: an upcoming meeting which contains a tutor, list of students, subject, date, time, offline/online format, private/group type and description with information about room number or conference link. The session can be created only by a tutor specifying his/her students from the “My Students” list.
* **Session format**: meeting will be held online or offline.
* **Session type**: meeting will be *private* (only for one student) or *group* (for several students).
* **My schedule**: list of **user**'s upcoming sessions.
* **Tutor's rating**: rating which each tutor has for his/her services. Students can rate **CV cards**, so others can see the tutor's service quality.
* **Innopolis University**: University in Russian Federation, Republic of Tatarstan, Innopolis city. Link to the [university website](https://innopolis.university). 
* **Innopoints**: the internal currency of the Innopolis University with which you can make purchases in a special store or use in the canteen to buy lunches.
* **Innopolis email**: an email that can get only students and staff of Innopolis University.

## Stakeholders and their roles
* **End User**: university students that would be either as tutors for students, or students who will be responsible for a continuous feedback as a use (**tutors ratings** will be provided)<br>
 **Stake**: Service Quality
* **Development Team**
  * Developer 1 – Backend developer. Implement the backend on Java/Spring which interacts with the PostgreSQL database.
  * Developer 2 – Backend developer. Implement the backend on Java/Spring which returns the result to the frontend via REST API.
  * Developer 3 – Backend developer. Write tests for the Backend.
  * Developer 4 – Frontend developer. Integrate backend with frontend and implement the logic of UI elements.
  * Developer 5 – Frontend developer. Create and implement a user-friendly designusing Flutter, containing all the features made on the backend where all developers will test their part before integrating parts. <br>
 **Stake**: Development process
* **Project Manager & lead**:  Professor Yegor Bugaenko and our TA Aleksandr Tsupko 
  * Professor and TA: managing the project by controlling the entire creation process, considering problems, needs during the process, giving advices (*call to action* from lectures and practices from labs) and considering testing the final product.<br>
 **Stake**: managing project
* **Customer**: Professor Yegor Bugaenko (internal customer), University administration (external customer)
  * Professor: provides everything that’s needed to fulfill the project needs, including instructing and giving advice.
  * University administration: responsible for accepting and delivering the final product to the end user.
## Backlog 📃
You can check our backlog with user stories by following the [link](https://github.com/InnoTutor/README/blob/main/UserStories/userStories.md)

## Non-functional requirements ✅
To check non-functional requirements of our project, follow the [link](https://github.com/InnoTutor/README/blob/main/NonFunctionalRequirements/NonFunctionalRequirements.md)

# Design
## Diagrams 📊
* [Class Diagram](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/ClassDiagram.md): <p>
* [Sequence Diagram](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/SequenceDiagram.md): <p>
* [Database Diagram](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/DatabaseDiagram.md): <p>
* [Use Case Diagram](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/UseCaseDiagram.md) <p>

 
## Design Patterns
 * How do we used **SOLID**? 
   * **S**(ingle responsibility) - each database entity has only one resposibility representing its data. Moreover, each class has only one purpose. For example, class *AverageRating* has a constructor with final field of ratings list and has a method wich is responsible for calculating the average cards rating exactly for a particular tutor's list.
   * **O**(pen-closed) - each entity is opened for extension and closed for modification. It means that it is possible to add new fields or new elements to the entity(open) and in the same time entity can be used by other classes (closed).
   * **L**(iskov substitution) - we did not use this principle since we do not use inheritence in the project.
   * **I**(nterface segregation) - we did not use this principle since we did not create special interfaces to be implemented by classes.
   * **D**(ependency inversion) - we created interfaces and used them instead of objects (examples: in backend in services.utility.sessionconverter.SessionConverter and dto.searcher.UserCard)
 * **Observer pattern**- to notify tutors about students requests and notify students about tutors responds
 * **Adapter pattern** - to interpret database data to the another convenient form for the frontend
 
# Architecture
 To check the architecture of our application you can open diagrams by following links below.
* [Static View](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/StaticViewDiagram.md): <p>
* [Dynamic View](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/DynamicViewDiagram.md): <p>
* [Allocation View](https://github.com/InnoTutor/README/blob/main/UMLDiagrams/AllocationViewDiagram.md):<p>

# Code
 * [Link for a working demo](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
 * [The result of PMD static analyzer](https://github.com/InnoTutor/README/blob/main/StaticAnaylyzer/result.md). Do not be scared by such big number of violation. We fixed all the violations that we could fix. Other violation can not be fixed due to spring framework specific code which reuires to follow special name convention, so the framework could understand fields and create particular [Beans](https://docs.spring.io/spring-framework/docs/current/reference/html/core.html#beans-definition).
 * Test coverage - !TODO!


<br>
<br>
