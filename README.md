The OpenShift `nodejs` cartridge documentation can be found at:
http://openshift.github.io/documentation/oo_cartridge_guide.html#nodejs

To debug openshift app and see server logs, navigate to the app git root and run
the following: rhc tail -a app_name_here

Node.js Notes:

command: npm install
will look at your package.json file and add the appropriate dependencies to your
node_modules folder

command: node server.js
will run your application locally at address ip:port

Author: Stephen Dyksen
Date: 1/20/2016
Description: Friend Frequency is a cross-platform mobile application that allows
users to play a two-person game that revolves around finding associations between
words.


Code Organization:
The code is broken up into three main sections. The database, the server, and
the application.


Technology:
Database:

Server:
  Node.js

Application:



UX Engineering Process:
  www.friendfrequency.com/ux
