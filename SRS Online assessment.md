# Online Assessment System
## Document:
System Requirement Specification Document

## Title:
System Reqruiement Spefication for Online Assessment Portal
## Team:
- Student
- CDAC Administrator
- Exam Coordinator
- Tech Support
- Institute Coordinator
## Objective (Purpose):
  System aims to conduct online exams on remote platform for students. Institute suppose to provide quetion paper on student portal and also they can track the results. This system will be used by any educational institute to host exams, administrator and to access online examinations.
## Scope:
  The Online Examination System will provide a platform for conducting online exams securely, efficiently, and with user-friendly features. This system focus on rapid behaviour of system that process different requests and generate results as fast as possible.
  - Since it is web based system , user can login to portal from anywhere and able to appear for the exam.
  - Examiner not need to be present at the time of exam as system can deals with various security threats, fault tolerence, backup and recovery of data in case of power failure etc.  
## Definitions:
  - OES : Online Examination System.
  - UI  : User Interface.
  - BAR : Backup And Recovery.
  - DB  : Database

## Functional Requirements:
  System is basically integration of three modules as mentioned below -
  #### 1 . User Management -
  - User can register as student, examiner, administrator using their unique ID.
  - User needs to complete all required verification steps for successful registration.
  - Once user registered successfully, system will generate username and password which will required at the time of login.
  - Users can log on to their respective portal and can be able to access various system services.
      - Student can log on to their portal and give exams, verify the results, update their profiles
      - Institute co-ordinator can log on to their portal and can check for various options like List of student from their institute appeared for exams. System will also maintained list of student from various institute who has cleared the exam or not.
  #### 2 . Exam Management -
  - Exam co-ordinator can create exams on admin portal by specifying exam type(Mock exam, Aptitude, Module assignment) and assign them to students or specific group of students by applying if any criteria is mentioned there.
  - Exam co-ordinator can specify date and time for exam.
  - Exam co-ordinator will also track the list of students who matched the exam passing criteria or not.
     
## NonFunctional Requirement:


#### 1. Performance:
- The system should support a large number of concurrent users.
- Response times for actions such as exam loading and submission should be minimal
#### 2. Security:
- The students and faculties authorized by the CDAC Administrator are allowed to access the system. 
- User data, including passwords, should be securely stored.
- Access to exams and results should be restricted based on user roles.
#### 4. Reliability:
-Every time the system is syn with the student data so in any point of time the system crashes or faces a technical issue, the 
 student question are backed up and student need not to worry in any situation.
#### 5. Scalability:
- The system should be scalable to accommodate a growing number of users and exams.
  Reliability:
#### 6. Availability
- The system should have high availability to ensure exams can be conducted without interruption.
  uptime: 24* 7 available 99.999%
#### 7. Maintainability:
- A Commercial database software will be used to maintain system data persistence a ready made webserver installed to host online 
  assessment system.
- To manage server capabilities it operations team will easily monitored and configure system using administrative tools provided by 
  servers.
#### 8. Safety:
- System ensures safety of data, In case of power failure or network related issues current session of exam can be saved and student will able to resume their exam later on.
