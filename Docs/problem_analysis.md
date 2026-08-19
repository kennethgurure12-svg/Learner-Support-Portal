Problem Analysis 

1. Problem Statement
Students currently keep their goals, tasks, support bookings, and progress in different documents and messages. This makes it difficult for assessors to track learner progress, identify students who need support, and monitor outstanding work. It can also lead to poor communication, delayed responses, and missing information.
To solve this problem, we will develop a web-based Student Support Portal. The portal will allow students to securely log in, view announcements, manage their tasks, request support, upload documents, and track the progress of their requests. Assessors will be able to view learner progress, see outstanding tasks, identify students who need support, and manage support requests more easily. This system will improve communication and make it easier for both students and assessors to manage learning activities.
2. Requirements 
The system must:
•	Allow students to register and log in.
•	Authenticate the users using Firebase Authentication.
•	Allow students to submit support requests/ bookings.
•	Display announcements.
•	Allow students to manage their own tasks.
•	Allow students to upload documents.
•	Allow students to play mini-coding game. 
•	Allow assessors to view and respond to requests/ bookings.
•	Show status of each request (pending, in progress, resolved etc..).
•	Allow students to print their progress summary. 
•	Allow students and assessors to log out.
•	Store information on Firestore.


3. User stories 
•	A student wants to log into the portal so they can submit a support request.
•	A student wants to check the status of their request 
•	An assessor wants to view all the support requests / bookings so they can assist students.
•	A student wants to upload documents. 
•	An assessor wants to update the request status so that the students know the progress. 
•	A student wants to log into the portal and play the mini-coding game 
•	A student wants to print their progress summary.

4. Project Scope
•	User registration
•	User login
•	Student dashboard 
•	Firebase Authentication 
•	Firestore database 
•	Upload documents 
•	Submit support requests / bookings 
•	View request status 
•	Mini-coding game 
•	Logout 

5. Use  Cases 
1.	 Students 
2.	Assessors 
Student Use Cases: 
•	Register account 
•	Login 
•	View Learner Dashboard 
•	View announcements 
•	Submit support requests 
•	View request status 
•	Update Profile 
•	Upload documents 
•	Manage own tasks 
•	Play mini-coding game 
•	Print progress summary 
•	Logout 

Assessor Use Cases:
•	Login 
•	View student information
•	Manage announcements 
•	View documents 
•	View support requests
•	Update support request status 

6.Testable  acceptance criteria 
Requirement 	Acceptance Criteria 
User Login 	Students can log in using a valid email and password 
Registration 	New users can successfully create an account 
Upload Documents 	Students can upload documents and the uploaded document is stored successfully.
Submit requests 	Students can submit support requests, and the support is saved in Firestore after submission. 
View requests	Students are able to see all of their submitted requests. 
Request status 	Students can see whether a request is pending, in progress, or resolved. 
Mini-coding game 	Students are able to play mini-coding games. 
Logout 	Clicking the logout button signs the user out and returns them to the login page. 






