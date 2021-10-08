# InnoTutor 📚
**Authors**: Daniil Livitn, Roman Soldatov, Emil Khabibulin, Tasneem Toolba
<br><br>
**Technologies**: <br>
* **Flutter (FrontEnd)**: UI cross platform applications for Android, IOS , and web
  * Visual Studio Code and Android Studio are used as an IDE
  * Link to the repo: [Frontend Repository](https://github.com/InnoTutor/Frontend)

* **Java Spring Boot, Firebase, Docker, PostgeSQL (BackEnd)**: <br>
  * IntelliJ IDEA IDE
  * Link to the repo: [Backend Repository](https://github.com/InnoTutor/Backend)
## What is the goal of the project?
The problem we are trying to solve is to fulfill students’ needs in some hard courses by the help of other students who are/were good at those hard courses, and make the university consider such help as an official student activity so that those students who helped others, get awarded. 
* Build a platform for Innopolis university students to share their knowledge, where students that are good in some courses and want to help others know where to inform others about this willingness to help.
* The website needs to manage how each of the students and tutors finds each other, and communicate.
* The built platform should be able to manage meeting schedules, tutors’ and students’ availability.
* The system should handle authentication with university accounts.
* The build application needs to award the tutors (university’s students) by the internal university’s currency (innopoints) or by discussing other awards with the university itself.
## Glossary 📝
* **User**: anyone who uses the “InnoTutor” website.
* **Tutor**: a university student who offers help in some academic courses.
* **Student**: a university student who asked for help in some academic courses.
* **Requests list**: user’s list of help requests that he/she uploaded so tutors could see them.
* **Services list**: tutor’s list of courses that he/she is going to teach.
* **CV**: some kind of portfolio uploaded by a tutor on the profile. A tutor can specify the subject, description and preferences about online/offline and private/group meetings. All uploaded CVs will be shown in the Services list.
* **Tutors list**: list of tutors offering their help given their preferences, e.g. online/offline, subject, and whether in a group or not.
* **Students list**: list of students who asked for help, all tutors see those students.
* **My Students**: list of tutor’s students who asked him/her for help. A tutor can manage these students via removing them or creating sessions with them.
* **Session**: an upcoming meeting which contains a tutor, list of students, subject, date, time, offline/online format, private/group type and description with information about room number or conference link. The session can be created only by a tutor specifying his/her students from the “My Students” list.
* **My schedule**: list of upcoming sessions.
* **Innopoints**: the internal currency of the Innopolis University with which you can make purchases in a special store or use in the canteen to buy lunches.
* **Innopolis email**: an email that can get only students and staff of Innopolis University.

## Stakeholders and their roles
* **End User**: university students that would be either tutor for students, or students.
who will be responsible for a continuous feedback as a use <br>
 **Stake**: Service Quality
* **Development Team**
  * Developer 1 – Backend developer. Implement the backend on Java/Spring which interacts with the PostgreSQL database.
  * Developer 2 – Backend developer. Implement the backend on Java/Spring which returns the result to the frontend via REST API.
  * Developer 3 – Frontend developer. Integrate backend with frontend and implement the logic of UI elements.
  * Developer 4 – Frontend developer. Create and implement a user-friendly designusing Flutter, containing all the features made      on the backend where all developers will test their part before integrating parts. <br>
 **Stake**: Development process
* **Project Manager & lead**:  Professor Yegor Bugaenko and our TA Aleksandr Tsupko 
  * Professor and TA: managing the project by controlling the entire creation process, considering problems , needs during the process, and considering testing the final product.<br>
 **Stake**: managing project
* **Customer**: Professor Yegor Bugaenko(internal customer), Universityadministration(external customer)
  * Professor: provides everything that’s needed to fulfill the project needs, including instructing and giving advice.
  * University administration: responsible for accepting and delivering the final product to the end user.
## Backlog 📃
You can check our backlog with user stories by following the [link](https://github.com/InnoTutor/README/blob/main/UserStories/userStories.md)

## Non-functional requirements ✅
To check non-functional requirements of our project, follow the [link](https://github.com/InnoTutor/README/blob/main/NonFunctionalRequirements/NonFunctionalRequirements.md)


## Diagrams 📊
* **UML Case Diagram**: <p>
![Lab 3 2  Diagrams-UML Use Case Diagram](https://user-images.githubusercontent.com/69918609/134770611-fb37f6cf-0597-4544-992b-d9e547ab09ad.jpg)
<!-- <img src="https://user-images.githubusercontent.com/69918609/134770611-fb37f6cf-0597-4544-992b-d9e547ab09ad.jpg" width=500 height=500>> -->
* **Database Diagram**: <p>
![Database Diagram](https://user-images.githubusercontent.com/49106163/136595438-587bd5b5-4a1c-4c7e-aeaf-18e0056d1c24.jpg)
 * **Class Diagram**: <p>
![Class Diagram](https://user-images.githubusercontent.com/49106163/135507554-4b746e8d-0634-41cb-9f61-580d187c84ea.png)
* **Sequence Diagram**: <p>
![Lab 4 2  Sequence diagram-Sequence Diagrams](https://user-images.githubusercontent.com/69918609/134770645-c04453de-abd8-4a8d-895e-64d2c119eee3.jpg)
* **Static View**: <p>
![Lab 3 1  Static_Dynamic_Allocation views-Static View](https://user-images.githubusercontent.com/69918609/134770668-5b6cb7cf-cecf-44f4-9e2f-2698267a4875.jpg)
* **Dynamic View**: <p>
![Lab 3 1  Static_Dynamic_Allocation views-Dynamic view](https://user-images.githubusercontent.com/69918609/134770681-9bcfec20-69cf-49c3-8dc5-451aa73b84b5.jpg)
* **Allocation View**:<p>
![Lab 3 1  Static_Dynamic_Allocation views-Allocation view](https://user-images.githubusercontent.com/69918609/134770704-649a47ae-837a-4856-beb4-bfd72bed6a1f.jpg)
<br>
<br>
 

