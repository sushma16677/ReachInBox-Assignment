Overview
This repository contains the code for Reachinbox frontend App using React with Typescript for an assignment given by Reachinbox.

Technologies Used ( Frontend )
Typescript
React
Tailwind css
Deployment
The application is deployed on netlify and can be accessed here.

Demo Video :-
https://www.loom.com/share/b12a1f9ab67e48ae8e90efff18bccc9b?sid=6a306c49-9d1a-4b37-9dfa-21b4538e3831

Login Page
Screenshot (344)

Landing Page
Screenshot (346)

Deshboard with Dark Mode
Screenshot 2024-04-02 213745

Dashboard with Light Mode
Screenshot (355)

Delete Email
Screenshot (356)

How to Run
Installation
Clone the repository: git clone https://github.com/JahirPendhari09/ReachInBox-Frontend.git 
Navigate to the project directory: cd reachinbox
Install the dependencies: npm install
Start the development server: npm run start
Open your browser and visit: http://localhost:3000

Features
Authentication
Get Emails
Post (send) Email
Delete Email
Endpoints
All Emails
GET {{baseurl}}/onebox/list 
All Emails from Onebox
GET {{baseurl}}/onebox/messages/:thread_id 
Add Onebox Mail
POST {{baseurl}}/onebox/reply/:thread_id 
Delete Email
DELETE {{baseurl}}/onebox/messages/:thread_id 
Credits
This project was developed by Jahir Pendhari as a part of Masai School training program.

Feel free to explore and integrate these endpoints into your application.# ReachInBox-Assignment
