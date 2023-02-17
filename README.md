# field-proxy
# backend-task
# Overview
This app will track multiple schedules for individuals inside of your univercity. It is set up to add future appointments, view past appointments, and delete meetings that need to be rescheduled. Multiple profiles can be configured to allow for multi-tier univercitys to use this application. To get started with modifying this project,  and run "npm install" inside your terminal. After the installation is succesful, run "npm start" and open [localhost:5050](http://localhost:5050/) in the browser of your choice.



# Web Pages
The authentication pages are straightforward. The Register and Login pages both contain a form for the respective action that will take place and feature a dynamic header that will change whether you are logged in or not.

The schedule pages include anything with '/schedule/ in the url. These pages contains forms and load data stored in a database. The Profile data and schedule information is all stored in a MongoDB database and is generated with the html template or sent as a JSON object from the server.

# Development Environment
The most prevelant libraies or frameworks I used are Node.js, express, mongoose, and csurf. Node.js was used to organize everything with the package manager and build the server. I used express to handle all the routes and a few other components. Mongoose was implemented to easily manage the connection with MongoDB and build the database. Finally the csurf library was used to help with security and authentication.