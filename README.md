# Teacher_Student_Interaction_CSED_Portal


Contents
Preface iv
Acknowledgements v
1 Introduction 1
1.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1
1.2 Motivation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
1.3 Objective . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
1.4 Software Development Model Used . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
1.5 Languages Used . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 2
1.6 Organization of report . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
2 Proposed Work 4
2.1 Database Design . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4
2.2 Actors Involved . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
2.2.1 Teacher . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7
2.2.2 Student . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
2.3 Features on Teacher Side . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8
2.3.1 Add/Remove Batch in courses . . . . . . . . . . . . . . . . . . . . . . . . . 8
2.3.2 Upload Notices/ Assignments . . . . . . . . . . . . . . . . . . . . . . . . . . 9
2.3.3 Details of enrolled batch . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 9
2.3.4 List of late submissions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 10
2.3.5 Explore uploaded notices/Assignments . . . . . . . . . . . . . . . . . . . . . 10
2.3.6 Update Exam marks . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
2.4 Features on student side . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11
2.4.1 Added/ Removed in a course . . . . . . . . . . . . . . . . . . . . . . . . . . 11
2.4.2 Explore assigned work . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
2.4.3 Submit the solution . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 12
2.4.4 Rating of teacher . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13
vi
2.4.5 Exploring notices . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 14
3 Conclusion and Future Work 15
3.1 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
3.2 Future Work . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15
References 17
vii
Chapter 1
Introduction
If we focus on the current scenario of CSED, teachers and students need a mediator to interact
with each other to communicate any information regarding any subject. For example, to send
assignments, study material, notice or any other content related to the subject teacher has to
communicate it to the batch through a class representative. When students need to submit solution
of assignments, make a request, etc, they need to go directly to the teachers office. In this way
of communication, some important information can be delayed in case of unavailability of class
representative. Many times this creates problems for students and make the learning process
slower. Teachers also can not available all the time for a batch because of their busy schedule. It
is also very difficult for teachers to manage every information or students submission in hard copy.
Due to all these problems faced by students and teachers, there is a need to develop an integrated
system to establish direct communication between teachers and students of CSED, without the
requirement of any mediator.
This web-portal establishes direct communication between faculty and students of CSED. It
allows teachers to directly convey any information, assign works to the students of the added batch.
Students can also upload solutions for assignments which is easily accessible to the teacher. This
portal helps to make marking system more transparent. It is easier for students to give feedback
to teachers so that any improvement can be helpful with the same batch.
1.1 Overview
Student and teacher need to log-in to access the portal. After log-in teacher can add a batch to
a course which is being taught to that batch by him/her in the current semester. By doing this
all students of that batch will be added to the course. A teacher can post notices or assignments
to a particular course and batch. Uploaded assignments and notices can be downloaded by the
students and teacher himself. A student is allowed to upload a solution to a particular assignment
1
which is visible at the teacher side. Students can also easily download their previously uploaded
solutions. The newly updated solution replaces the previous one.
This way of communication reduces the gap between teacher and student by removing mediator.
This way it saves the time and effort of the teacher which is wasted to seek help always from class
representative to convey any kind of information to the enrolled batch. It also reduces paperwork.
1.2 Motivation
The motivation behind this project is:
• Creating an easy and anytime communication between teacher and student in order to improve student-teacher relationship by establishing direct communication through this portal
and by removing mediator.
• To communicate information sent by teacher directly to all students of a batch at a time by
posting all the information to the portal.
• To save time of teachers and students which is wasted to make communication through
class representative by removing class representative as a mediator and establishing direct
interaction.
• To reduce paper work by adding online solution submission and online information transfer.
1.3 Objective
The objective of this project is to save the time, effort of teachers and students of CSED by
eliminating the class representative as a mediator or single point of contact for each other. It also
helps to save paperwork because all assignments and submission are online.
1.4 Software Development Model Used
The project has been developed keeping the incremental build model of software engineering in
mind. Thus, requirement gathering and analysis of the problem had to be updated after every
progress in the development phase, post which the development and implementation of the various
prototypes take place to nally reach a nal design.
1.5 Languages Used
Following languages have been used for the development:
2
• Front-End Development[1][3]
– HTML
– CSS
– Bootstrap 4
– JQuery (JavaScript)
• Back-End Development
– PHP
• Database Management System
– MySQL (RDBMS)
1.6 Organization of report
Chapter 1 consists the introduction, overview, motivation and objective of the approach.
Chapter 2 describes the features and functionalities of the developed system.
Chapter 3 describes the future work and conclusion of the report.
3
Chapter 2
Proposed Work
The CSED portal provides a plethora of functionalities for all kinds of users using this portal. The
main focus of the entire project is to remove the gap between teachers and students of Computer
Science and Engineering Department. The web portal has very much achieved the goal in a
substantial matter. Now teaching and learning in CSED will be far more comfortable.
2.1 Database Design
Good database design is the one that divides our information into subject-based tables to reduce
redundant data, helps support and ensure the accuracy and integrity of our information, and
accommodates our data processing and reporting needs. So, we have tried to design a database
that not only caters to our needs but is also efficient, fast and accurate[6].
The database management system used for this portal is MySQL. A database management
system is one of the most important components of a project because it manages data efficiently
and allows users to perform multiple tasks with ease. A database management system stores
organize and manage a large amount of information within a single application[4].
The Entity-Relationship Diagram, Physical Design and Use-Case Diagram for our project are
given.
4
Figure 1: Entity-Relationship Diagram[2]
5
Figure 2: Physical Design of Database
6
Figure 3: Use Case Diagram for the system[5]
2.2 Actors Involved
The different types of roles/actors involved in The CSED portal are:
2.2.1 Teacher
Every teacher who is teaching in the Computer Science Engineering Department is a part of the
CSED portal. A teacher can log-in to the portal. A teacher can add or remove a batch in single
7
or multiple courses which teacher is teaching in a semester. A teacher can upload notices and
assignments to a batch enrolled in a course. A teacher can check the assignment solution status of
students and also can upload exam marks on the portal.
2.2.2 Student
Every student who is registered in MNNIT and having B.Tech. program in Computer Science
Engineering or Information Technology branch or having MCA program is a part of the CSED
portal. Student can log-in to the portal. Student can be added to multiple courses by multiple
teachers. Student can see all the notices and assignments uploaded in a course. Student can submit
a solution of assignments. Student can see its exam marks and can also give a rating to teachers
on the basis of its experience of learning in the class.
Figure 4: Log-In page for student and Teacher
2.3 Features on Teacher Side
Teachers have following features on the CSED portal:
2.3.1 Add/Remove Batch in courses
Teacher can add or remove all students of a batch to single or multiple courses by just clicking a
button.
8
Figure 5: Add or Remove batch from a course
2.3.2 Upload Notices/ Assignments
Teacher can upload notices for a batch enrolled in a course. Teacher can also upload assignments
for a batch with due date of submission.
Figure 6: Document upload for a batch
2.3.3 Details of enrolled batch
Teacher can see list of all students of a batch enrolled in a course. Teacher can see the status and
copy of solution submission by each and every student for every assignment.
9
Figure 7: Document upload for a batch
2.3.4 List of late submissions
Teacher can easily see the list of all the students who has not submitted the solution of any
assignment on time or not submitted any solution at all. This list is just one click away.
Figure 8: List of late submissions
2.3.5 Explore uploaded notices/Assignments
Teacher can see all the notices and assignments uploaded by him/her for a batch and can also
download it.
10
Figure 9: List of uploaded notices/assignments
2.3.6 Update Exam marks
Teacher can update mid-semester and end-semester exam marks of each and every student which
is shown to student.
2.4 Features on student side
Students have following features on the CSED portal:
2.4.1 Added/ Removed in a course
Student can be easily enrolled in a course by a teacher who is currently teaching his/her batch.
Here student finds all the courses in which he/she is enrolled in current semester.
11
Figure 10: Student Profile with all courses
2.4.2 Explore assigned work
Student can see and explore the assigned work to him/her in a course by a teacher. Student can
see list of assignments, its issue and due date. Student can download assignment to its device.
Figure 11: Explore the course
2.4.3 Submit the solution
Student can submit the solution of assignments online. It is restricted with due date. No submission
is allowed if due date of assignment is over. Because of this no need to go to the teacher’s office.
Online solution submission instead of hard copy is not only fast and easy but environment friendly
12
also.
Figure 12: Submit the assignment solution
2.4.4 Rating of teacher
Based on the learning experience in the class in a course, student can give rating to a teacher in
out of 5.This rating is anonymous to the teacher. Teacher can only see the average rating by all
the students.
Figure 13: Student can give rating to teacher
13
2.4.5 Exploring notices
Student can see, explore and download all the notices which is uploaded for all the courses in which
he/she is enrolled. Every notice will reach to each enrolled student with no delay.
Figure 14: List of uploaded notices for all courses
14
Chapter 3
Conclusion and Future Work
3.1 Conclusion
Moving towards the end of the implementation and deployment phase of the project, we mainly
worked around looking for bugs, and certain problems and changes that were needed regarding the
portal.
The portal will help the teacher to send a message or any information to the whole batch
directly without any delay in this process due to the mediator. It will be easy for the teacher
to manage each subject because everything as notices, assignments, student details, submissions
will be at one place. On the other hand, it will also provide students with the convenience in not
only sending solutions to the assignments but also accessing all the study material and information
related to a particular course at one portal.
Management is going to be very easy for both teacher and student as this portal provides a
very good user interface and solves most of the problems faced by teacher and student during a
course period which arises due to communication gap or document management.
3.2 Future Work
The project is aimed at creating an efficient portal to reduce the communication gap and paper
work and make the system more convenient and efficient for both student and teacher. We will
be looking forward for the deployment of the portal so that it can be used in an effective way and
help the teacher and student to communicate easily. In future we will be looking forward to:
• Integrate the mini and major project assignment and management of the project.
• Integrate the feature that student should be able to contact to any teacher personally to
make strong relationship between student and teacher.
15
• This project can be expanded to all the departments of MNNIT.
As it is known that every project has a scope of optimization, we tried to act on it and we hope
that this practice continues in future too.
16
References
[1] Bootstrap 4. https://getbootstrap.com.
[2] Entity relationship diagram. https://www.draw.io/.
[3] Html,css,javascript, php. https://w3schools.com.
[4] Is Database Design Important To Application Performance Management? https://www.
appliedtrust.com/blog/2013/08/is-database-design-important-to-application-performance-management.
[5] Use case diagram. https://online.visual-paradigm.com/solutions/
free-use-case-diagram-tool/.
[6] Team, M. What is the importance of a database management system? https://www.
manomayasoft.com/blog/item/210-what-is-the-importance-of-a-database-management-system.
