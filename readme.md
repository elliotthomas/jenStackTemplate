JEN Stack Template
==================

Basic JQuery, Node, Express template. Connects a client to a server on port 8080. Basic routes are set up for the index.html on the base url, as well as a 'testGet' route and a 'testPost' route which fire on button clicks.

Setup:
-----
* fork/clone this repo [X]
* npm install in the folder into which you have cloned [X]
* run 'npm start' to spin up the server [X]
* check localhost://8080 in your browser [X]
* test the button clicks and check for your output in the console[X]

Completing the project:
----------------------
* display info from testGet call on the DOM[X]
* add input fields for a new event: eventName, athleteName, award[X]
* change the testPost button to get this user input and create a new object with this data [X]
* change the test post to send this object to the server [X]
* log out the req.body on the server side (should be this user input) [X]
* create an array of events on the server side and push new objects to it [X]
* have the server respond with a new object that has this array within 
* log out that array in the browser console when received
* display those awards on the DOM
