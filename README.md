# banking-app-wDockerMongo

This is work in progress for MITxPro week 27 Banking application with MERN stack. 

# MongoDB, express, react, node.js

# Installation Guidelines: 

download docker desktop.  git clone to local machine, run npm install to get dependencies which include cors, mongodb, express, and docker.  
Run docker desktop and run the database from docker with 

docker run -p 27017:27017 —name bad bank -d mongo

run ps to confirm it's running

docker ps 
 
new terminal window to project directory and run node index.js to start the front end on http://localhost:3000 

That's it for now.  Next to figure out authentication.  Most likely will use firebase: https://firebase.google.com/docs/admin/setup

