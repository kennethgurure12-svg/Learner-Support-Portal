//Part 1 - Architecture Investigation
 1. What is client-side development, and where does client-side code execute?
 2. What is server-side development, and how is it different from code executing in the browser?
 3. Within SkillsTrack, explain the role of HTML, CSS, JavaScript, , Firebase 
Realtime Database and the Firebase REST API.
 4. Is Firebase the same thing as server-side JavaScript? Explain your answer.
 5. When a learner creates a learning task, which operations happen on the client side and which involve 
a remote/server-side service?
 6. Why should authentication, database access and security not be treated as purely client-side concerns?
 7. Research at least two alternative technologies that could provide backend/server-side functionality 
instead of Firebase. Explain how the architecture would change.
 8. Identify at least three security risks that could occur if sensitive information or security 
responsibilities are incorrectly placed in client-side JavaScript.

Answers to Part 1:

1) Client side development is the part of the front end development where the user is able to see and touch or rather interact with the system itself baisically whatever information inputed by the client or the user so for example when a user inputs their info to a website that process where the web app now goes into the fetch mode about to ask if the user is valid or not 

how/ where does the code execute: the code executes itself on your devices then the code runs in the web browser of that app you are using so baisically the background because every webb app always has java running in the backend of the axctuall web app 

2) Server side development is the a  part in which the information inputed by the user is being veriefied baisically its like the database were the information is stored if the user infomation exsists then the info goes back to the client side to confirm or decline what ever was inputed so its baisically the authenticator that allows access or not if details are correct then its gets that information then delivers it 

how this exexutes : it executes by waiting for information to be given to it while working in the background , for this example we will say javascript and once the the web browser takes information and carries it to the server side the server check the info if good it send if not it still sends but tells it we dont know who this is 

3) HTML: well the role of HTML in our web app would be to define and create structre and organize the content being put in the webpage 

CSS: CSS ia all the styling and fixing of how the webpage should be brought or seen from the users side how the page should look what colour it should use the fint size and background colours etc all those types of things would be used for the webpage 

Javascript: This is the coding that brings the functionallity to the webpage so the webpage performs specfic instructions baisically just the functionality of the web app as a whole so when i click a button what should it do should it add values should it count up or down thats bring the webpage to life making it actually work 

Firebase Authentication:  Firebase is were the webpage becomes a web app what this means the Fire Base Auth is the place where the client server and server side is happening once this is where the auth takes place from the fetch to the get method firebase stores and checks user information and verifies if its correct or not then we have the next step where it populated user information once verification is done 

Firebase Realtime Database: 

Firebase REST API:

4) No, Firebase is not the same thing as server-side JavaScript. Firebase is a comprehensive Backend-as-a-Service (BaaS) platform by Google that provides pre-built cloud infrastructure like databases, authentication, and hosting. Server-side JavaScript is a programming environment (like Node.js) used to execute code on a server rather than a user's browser.

5) When a learner creates a learning task, the client-side browser handles user input, form validation, and immediate interface updates. The remote server handles authentication, permanent database storage, server-side validation, and syncing data across other connected devices or users.

6) Treating authentication, database access, and security as client-side concerns is a massive risk. The client device is totally controlled by the user. Anyone can inspect code, bypass checks, and steal data.

7) Two popular alternative technologies to Firebase are Supabase (an open-source Firebase alternative built on PostgreSQL) and Appwrite (a self-hosted backend server that uses Docker).

8) Key Security RisksBypassed Access Control / Client-Side Validation: Relying on frontend code to hide administrative menus or check user permissions lets malicious users alter the Document Object Model (DOM) or edit script variables to unlock restricted features.Hardcoded Secret Exposure: Storing private API keys, database credentials, or proprietary algorithms in frontend source code allows anyone to read them via browser developer tools.

Data Leakage via Browser Storage: Keeping private user data or session tokens in insecure web storage like localStorage makes that data easily accessible to stolen sessions or Cross-Site Scripting (XSS) attacks. 

//Part 2:

![My Local Photo](Part 2.1.jepg)
![My Local Photo](Part 2.2.jepg)
![My Local Photo](Part 2.3.jepg)

![My Local Photo](my-image.jpg)

//Part 3:




Part 4:
//Part 4 - Trace One Complete Project Feature
Select ONE: User registration/login, Task management, Support-session booking, or Progress tracking.
9. 1. What action does the user perform?
10. 2. What does JavaScript do in the browser?
11. 3. What validation occurs?
12. 4. What information leaves the browser?
13. 5. Which Firebase service receives the request?
14. 6. What does Firebase do with it?
15. 7. What response/data is returned?
16. 8. How does JavaScript process the result?
17. 9. How is the interface updated?
18. 10. What should happen if the request fails?
USER -> CLIENT -> REQUEST -> FIREBASE -> RESPONSE -> CLIENT -> USE

answer:
1. What action does the user perform?
The user enters their email address and password and clicks the Login button.

2. What does JavaScript do in the browser?
JavaScript listens for the button click event, reads the values from the email and password fields, and prepares a login request.

3. What validation occurs?

JavaScript checks that:
the email field is not empty,
the password field is not empty,
the email is in a valid format.
If validation fails, an error message is displayed and the request is not sent.

4. What information leaves the browser?
The browser sends:
the email address,
the password.
This information is sent securely to Firebase Authentication.

5. Which Firebase service receives the request?
Firebase Authentication receives the login request.

6. What does Firebase do with it?
Firebase Authentication:
checks whether the email exists,
verifies the password,
authenticates the user,
creates an authenticated user session if the credentials are correct.

7. What response/data is returned?
Firebase returns:
the authenticated user object,
the user’s unique ID (UID),
authentication status,
or an error message if login fails.

8. How does JavaScript process the result?
JavaScript checks whether the login was successful.
If successful:
it stores the authenticated user state,
retrieves the user’s information,
prepares the dashboard.
If unsuccessful:
it displays the error message returned by Firebase.

9. How is the interface updated?
After a successful login:
the user is redirected to the dashboard,
the user’s name is displayed,
task data is loaded,
progress information becomes visible.

10. What should happen if the request fails?
The application should:
display a clear error message,
keep the user on the login page,
allow the user to correct their details,
prevent access to protected pages.
