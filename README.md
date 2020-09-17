# GroupFormation

### Project Definition
-----
GroupFormation is a tool to facilitate the organization of students into groups, and to organize, track and display the results of peer group assessments. The project is our own variation of the CATME Smarter Teamwork website. CATME is a tool used by University instructors to facilitate the organization and peer evaluation of group projects in University course.

"GroupFormation" primary functionality is the ability for an instructor to enter a set of criteria for a survey that each student completes on the first day of class. The answers to each student's survey are used in a backend calculation to form all of the groups for the course based on the parameters defined by the instructor. In addition to group formation, the project supports mechanisms to facilitate peer evaluation.

### Requirements
-----
#### Milestone one
* User authentication and authorization
* Admin dashboard which allow the creation and deletion of courses, and assignment of existing users as Instructor for a course
* Course admin page
* Import list of students from CSV file

#### Milestone two
* Validate and enforce a password policy
* Create a QuestionManager page to insert, delete and update question bank

#### Milestone three
* Using design patterns
* Add error handling & logging
* Add a "Create survey" page accessible from a link on the course admin page
* Group segregation based on responses received from students

### User Interface
-----
#### *Login* | *Register* | *Forgot Password*
![alt text](/images/1.png)
#### *Admin course panel* | *Add Course* | *Delete Course*
![alt text](/images/2.png)
#### *Assign Instructor*
![alt text](/images/3.png)
#### *Instructor and TA's course panel*
![alt text](/images/4.png)
#### *Instructor can add students and TA to particular course*
![alt text](/images/5.png)
#### *Group formation algorithm panel*
![alt text](/images/6.png)
#### *Student Survey screen*
![alt text](/images/7.png)
#### *Group Formation Results*
![alt text](/images/8.png)

### Technology Used
-----
*	Spring Boot
*	MySQL
*	GitLab
* Jira Software

### Software Development Characteristics
* Agile Model
* Test-driven Development
* Continuous Integration / Continuous Deployment
* S.O.L.I.D Principles
* Design Patterns
* Error Logging
