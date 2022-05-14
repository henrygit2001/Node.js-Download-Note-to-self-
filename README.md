# Express-Download-Note-to-self

What are the basic to set up a successful Express File:
1) Downloading Node.js
2) Install Node.js Intellisense and Developer Pack
3) Create a new node.js file by calling npm init
4) Install express
5) Install Nodemon to be able to refresh pages while changing code in IDE. 

Trouleshooting the Issues:
1) If I meet the error: Error: listen EADDRINUSE, then I can: 
a)Change to a new port (e.g: change from port 8080 to like port 8079 for instance)
b)Delete the active processes the port is currently listening to by going to cmd prompt then netstat -ano | pid = "<the name of the ID" and then
   killstat -PID = "<the ID>"
