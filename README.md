# InnoTutor 📚
**Authors**: Daniil Livitn, Roman Soldatov, Emil Khabibulin, Tasneem Toolba
<br><br>
**Technologies**: <br>
* **Flutter (FrontEnd)**: UI cross platform applications for Android, IOS , and web
  * Visual Studio Code and Android Studio are used as an IDE

* **Java Spring Boot, Firebase, Docker, PostgeSQL (BackEnd)**: <br>
  * IntelliJ IDEA IDE

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

## Diagrams 📊
* **UML Case Diagram**: <p>
![Lab 3 2  Diagrams-UML Use Case Diagram](https://user-images.githubusercontent.com/69918609/134770611-fb37f6cf-0597-4544-992b-d9e547ab09ad.jpg)
<!-- <img src="https://user-images.githubusercontent.com/69918609/134770611-fb37f6cf-0597-4544-992b-d9e547ab09ad.jpg" width=500 height=500>> -->
* **Database Diagram**: <p>
![Database Diagram](https://user-images.githubusercontent.com/69918609/134770631-84834784-166a-4934-aafc-e5c5952322c0.jpg)
 * **Class Diagram**: <p>
![Class Diagram](https://user-images.githubusercontent.com/49106163/134800752-965bcaec-fbc5-45a3-93bd-9727b492a216.png)
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

## Backlog 📃
You can track our user stories on the Trello board. <br>
Link: https://trello.com/b/5xWBSmzG
| Epics       | Features           | Functionality  |
| :-------------: |:-------------:| :-----:|
| As a student, I want to see the list of available tutors, so that I can choose the right person for me. (MUST) | As a student, I want to request a tutor's service, so that this tutor will see that I am asking for help. (SHOULD)<br><br> As a tutor, I want to have an availability to add a CV, so that students can see what subjects I am good at. (MUST)| As a tutor, I want to accept or reject a student asking me for help, so that I can maintain my list of students that I teach. (COULD) <br><br>As a tutor, I want to specify a subject which I am going to teach, so that students will see me in the “tutors list”. (MUST) <br><br> As a tutor, I want to specify the type of meetings, so that students will see the format (private/group) and the type (online/offline) of sessions which I prefer to conduct. (SHOULD) <br><br> As a tutor, I want to add a description in my CV, so that students will see what particular topics I want to teach, why I am good at it, etc. (COULD)|
| As a tutor, I want to see a list of students who asked for help, so that I can offer my help to someone. (SHOULD) | As a tutor, I want to see a list of students who asked for help, so that I can offer my help to someone. (SHOULD)<br><br>As a tutor, I want to respond to a student's request, so that he/she will see that I am ready to help. (COULD)<br><br>As a student, I want to have an availability to upload a request asking for help, so that tutors can see me and help me. (SHOULD) |As a student, I want to see a list of tutors who responded to my request for help, so that I can choose the one with which I want to study. (COULD)<br><br>As a student, I want to specify a subject which I want to study, so that tutors will see my subject’s request. (SHOULD)<br><br>As a student, I want to specify the type of meetings, so that tutors will see the format (private/group) and the type (online/offline) of sessions which I prefer most. (COULD)|
| As a tutor, I want to create a new session with my students for a particular subject, so that my students will see an upcoming event in the calendar. (SHOULD)s | As a tutor, I want to specify the type of upcoming meeting, so that students will see the format (private/group) and the type (online/offline) of a session that I am going to conduct. (SHOULD)<br><br> As a student, I want to have a calendar of upcoming sessions, so that I will see the schedule of meetings that my tutors are going to conduct. (SHOULD)|  |
|As a user of the website, I want to have my profile, so that I can have a saved list of upcoming sessions and personal information. (MUST) |As a user of the website, I want to log in to the website, so that I can access my profile. (MUST)<br><br>As a user, I want to specify my contacts, so that other users know how to contact me. (SHOULD)<br><br>As a student, I want to rate the tutor I've been studying with, so that other students could see it while choosing a tutor. (COULD)|As a user of the website, I want to log in using Innopolis credentials, so that there is no need to register. (SHOULD)<br><br>As a tutor, I want to see the rates which my students submit, so that I can see the quality of my services. (COULD)

