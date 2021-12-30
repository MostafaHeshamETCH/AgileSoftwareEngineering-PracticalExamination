# Agile Software Engineering - Practical Examination

## Student Details

- Student Name: **Mostafa Hesham Abd El Raouf**
- Student ID: **18P6951**
- Student Group & Section: Group 2 Section 1

## Project Details

- Project Name: **Educational Companion System**
- Project Description: For all educational centers that need a cross platform software to manage the whole educational process. Our product is an open source educational companion system for both teachers and students that greatly helps facilitate the educational process in a modern easy way.

## Team Members

### Team A: Frontend

| Name    | Role             | Expertise                        |
| ------- | ---------------- | -------------------------------- |
| Mostafa | UI/UX Designer   | Figma, Adobe XD, Adobe Photoshop |
| Hesham  | Web Developer    | HTML5, CSS3, JavaScript, ReactJS |
| Etchos  | Mobile Developer | Flutter, Dart                    |

### Team B: Backend

| Name    | Role               | Expertise                       |
| ------- | ------------------ | ------------------------------- |
| Omar    | Database Designer  | MySQL, SQL, Firebase            |
| Mohamed | API Integrator     | PHP, Javascript, JQuery         |
| Youssef | Backend Documentor | Professional Code Documentation |

### Team C: Testing

| Name   | Role                     | Expertise                 |
| ------ | ------------------------ | ------------------------- |
| Sherif | Unit & Functional Tester | JavaScript, Selenium, Moq |
| Marwan | Penetration Tester       | PenTesting, SQL Injection |
| Ashraf | Integration Tester       | DBUnit, REST-Assured      |

### Product Owner and SCRUM Master

| Name   | Role          | Work as   |
| ------ | ------------- | --------- |
| Ossman | Product Owner | Full-time |
| Shehab | SCRUM Master  | Part-time |

## Possible Stakeholders "Open-source Software"

- Educational Centers (Teachers + Students)
- Schools (Teachers + Students)
- Universities (Teachers + Students)
- Online Teaching Centers (Teachers + Students)
- Online Teaching Platforms (Teachers + Students)

## Near Vision

### Sprint no.1

By the end of this sprint, a basic usable prototype of the login functionality should be completed for both web and mobile platforms in which we will design and implement the basic UI/UX layout of the system in parallel with designing a secure database with proper authentication and authorization and proper data modelling of all expected form of data objects. Doing so will allow us to better visualize the overall view of the whole system and continue developing based on it.

Main overview:

- Interactive UI of the login screen for both teachers and students.
- Complete database design with proper modelling for required data.
- Implement the ability to give specific authorization to selected accounts.
- Implement the ability for secure authentication of the login process.
- Implement the ability to post material with these documents formats (.pdf, .docx, .doc, .jpeg, .png) in database with proper authentication and authorization.

### Sprint no.2

This sprint should be the introduction to teachers basic functionalities for both web and mobile platforms in which teachers should be able to upload selected material to their specified courses, post assignments with specific due dates and post quizzes with specified start and end dates.

Main overview:

- Interactive UI dashboard for teachers to add assignments, quizzes through it along with material.
- Implement the ability to edit or delete any posted document with proper authentication and authorization.
- Implement the ability to specify due dates for assignments and start and end dates for quizzes.
- Implement the ability for teachers to accept registered students to courses

## Far Vision

We are aiming to build a solid cross-platform open-source application that can provide various functionalities for the educational sector and greatly help facilitate and modernize the traditional learning system. We are building a cross-platform application to make it available for everyone, everywhere regardless the device they are using, and open-source so developers can freely add more features and functionalities to it or possibly learn from it.

## Product Backlog
### Product Backlog Rationale
The ordering of the backlog items are based on their true buisness value given to the stakeholders while taking into consideration the possible return on investment. For items will similar buisness value, they are ordered according to their dependency on each other.

### Notes
 - The sprint duration is **3 weeks**.
 - The team can achieve around **51 story point** per sprint.
 - Story points scale used is based on **modified Fibonacci sequence** which is as following {1, 2, 3, 5, 8, 13, 20, 40, 100}.
 - For each productive working day where the almost all the team members are working for 8 hours a day / 5 times a week, They can finish 3-4 story points per day.
 - 20 story points is a relatively large story, 13 is a medium-sized one and 8 and less are smaller-sized stories.

### Ordered Product Backlog Items
The order for the first two epcis should be as following

**Epic number 1** [102 Story Point]

 As a teacher, I would like to login to the app and post material, assignment or quizzes to the students registered to my courses so they can have direct access to my posted assets.

| # | Title | User Story | Estimation | Assignee |
| - | - | - | - | - |
| 1 | Interactive Login Screen | As a teacher, I would like to login to the app through my computer or mobile with a specific username and password so I can alter my specified course content. | 20 Story Points | Mostafa, Marwan, Hesham, Etchos |
| 2 | Database Modelling | As a teacher, I would like all the data of the course and the students to be saved on the system so I can access them at anytime | 13 Story Points | Etchos, Marwan, Youssef | 
| 3 | Post Material | As a teacher, I would like to post material with different document formats so my students can access them. | 20 Story Points | Hesham, Omar, Ashraf, Youssef |
| 4 | Post Assignments | As a teacher, I would like to post assignments with specified due dates so my students can hand them in time.| 13 Story Point | Omar, Youssef, Marwan |
| 5 | Post Quizzes | As a teacher, I would like to post quizzes with specified start and end dates so my students can take them in the same time. | 20 Story Points | Mostafa, Ashraf, Sherif |
| 6 | Edited Posted | As a teacher, I would like to alter any posted material, assignments or quizzes so I can fix any problems | 8 Story Points | Etchos, Sherif |
| 7 | Accept Student | As a teacher, I would like to accept or reject any student who requested to join my course so I can control who can access my posted material. | 8 Story Points | Mohamed, Ashraf, Hesham

**Epic number 2** [99 Story Points]

As a student, I would like to login to the app and access material, submit assignments and take quizzes to the my registered to my courses so my teacher can evaluate me.

| # | Title | User Story | Estimation | Assignee |
| - | - | - | - | - |
| 8 | Interactive Register Screen | As a student, I would like to register to the app through my computer or mobile with a specific username and password so I can use the app. | 20 Story Points | Mostafa, Youssef, Hesham, Sherif |
| 9 | Course Registration | As a student, I would like to register my self to selected course so I can access the course material | 13 Story Points | Hesham, Marwan, Youssef | 
| 10 | Access Material | As a student, I would like to access and download all material my teacher posted so I can study them. | 13 Story Points | Mostafa, Omar, Marwan|
| 11 | Submit Assignments | As a student, I would like to submit assignments so my teacher can grade them.| 13 Story Point | Omar, Youssef, Ashraf |
| 12 | Take Quizzes | As a student, I would like to take quizzes so my teacher can evaluate them. | 20 Story Points | Mostafa, Ashraf, Sherif, Marwan  |
| 13 | Check Grades & Request Reviews | As a student, I would like to check my grades at anytime and request grade review if needed so I can validate my grades. | 20 Story Points | Etchos, Sherif, Hesham |

## Number of story points my team can achieve per sprint

as stated above, The team can achieve around **53 story point** per sprint. (average between 45-60)

## Rationale and Rules used in the Workflow
A screenshot of the workflow and the rules from Jira are written in the Google Docs file.

The basic idea of the workflow used is that every issue should be moved only in the following sequence, Once the issue is created, It is moved to the TODO state. When it started it have to go to the IMPLEMENTING state and someone must be assigned to it. Then when it is finished, it must go to the TESTING state where only members of the testing teams and either accept it and move it to DONE state or reject it and moves it back to IMPLEMETING phase for refinement.

Taken into consideration of this flow, Two rules were applied to Three transitions. The rule “Assign an issue to someone” is placed on the start transition to make sure that each issue placed in the IMPLEMENTING state must be assigned to one of the dev team first. and the rule “Restrict who can move an issue” is placed on the two transitions: Accepted and Rejected, to make sure only a member of testing team can move this issue from TESTING state to DONE state in case of acceptance or back to IMPLEMENTING state in case of rejection.


## Daily Scrum Document
Written in the Google Docs file with all Jira's screenshots. Click [here](https://docs.google.com/document/d/1TXyKv0WMZDqDoUfbaykE7t5ZJIfIMlwu_XEBcHUHm_w/edit?usp=sharing). to go to it.

## Sprint Document
Written in the Google Docs file with all Jira's screenshots. Click [here](https://docs.google.com/document/d/1TXyKv0WMZDqDoUfbaykE7t5ZJIfIMlwu_XEBcHUHm_w/edit?usp=sharing). to go to it.

