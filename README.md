# Web-Server-Website (utlizing the mean stack)
Transfer of my personal website to a mean stack web server
>using MongoDb, Expressjs, Angularjs, Nodejs.
This will allow for an easy way to make my website a component based application/spa where I can create a way to auto update my resume when I want to make changes.

# Landing Page
Our custom landing page will be the first to load in with access to other parts of the site which will be detailed below. I would like to keep the image carousel and banner at the top of the web page as well as to try to include the button links under color-container from the previous website. Some of the designs there should be remade as they were a bit messy. Try to aim for a better color theme this time. The material indigo-pink theme may be a good starting point for finding out how to use primary and secondary colors as main parts of your website.

# Admin Login
We will need to add an admin login to access more personalized aspects of the site such as adding resume changes or accessing anything that can make personalized changes to the backend. This will need to have several options for verification plus a user and password.
>It may be worth it to look into ip verification and other types of verifying only selected devices for tighter security

# User Login
Detailed below, I wrote the option of adding a Schedular Application which implies that we would have users utilizing accounts to request personalized access to their accounts.

# Resume Auto-Update
We can use the Component based system for Angularjs to allow for a possible javascript based web editor where in I can alter certain text on my website using basic built in material components + any custom components I might create. We can then send this info back to our web server for it to be stored as the new resume.

# Custom To-Do List For Current Projects
We can create a to-do list or possibly grab data from out github public repos to show the current changes to projects that are currently being worked on.
## Schedular
we can also create a custom project schedular that will be similar to what an Asana Board or a Github Projects Board. This data will be sent to our server to be stored in a database(Mongodb). We can later have our web application request that data when a user wishes to view their projects.

# Project Viewer
An interesting way to show our portfolio would be through a project viewer that could utilize the github wiki and auto pull data from there to be outputted onto our site. We could use the github api for this to pull the wiki data. Remember that all uses of the REST api under the github api will be received in JSON format. We can have a custom Angular component that will detail each project as a tile on our web application.
### Tile Format:
[Project Title]
[Description]
[Image?]
[Tile Link] -> Github wiki loaded into a page with custom css styling
>https://developer.github.com/v3/
>
>https://stackoverflow.com/questions/27654854/is-it-possible-to-get-github-wiki-content-by-github-api

# Comment/Message Board
Allow users to login and send personalized messages to me or other users. ->Implement email association with accounts?
-> Call 3rd party API to send emails (Use this as it is more secure).
>https://developers.google.com/gmail/api/
>
>https://stackoverflow.com/questions/7381150/how-to-send-an-email-from-javascript
>
>http://www.emailjs.com/

# Look into using Docker
see what it may help out with for this project.
