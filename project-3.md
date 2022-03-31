# Project 3 MERN Documentation
## Backend COnfiguration

`sudo apt update && sudo apt upgrade` 

### find node.js software on ubuntu using `curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`
![find node.js software install code on ubuntu](./Images/node.js-find.png)
### install node js and npm`sudo apt-get install -y nodejs`
### verify node and npm installation and version with`node -v && npm -v`
![node and npm verification](./Images/node_npm.png)
### Create Todo directory and run npm init in Todo Directory to create package.json files `mkdir Todo && cd Todo && npm init`
![Package.json with npm init](./Images/Todo-application.png)

---
## Install Expressjs to run node.js server on 5000 port and also specify and make different directory for each task our application is going to do
### install express and create index.js file `npm install express && touch index.js`
![show files on Todo](./Images/display%20Todo%20files.png)
`npm install dotenv`
`vim index.js`
![index.js file configuration to port 5000](./Images/index%20file%20configuration.png)
### start server with `node index.js`
![start server](./Images/start-server.png)
[server accesws with public Ip](http://54.234.189.155:5000)
![server acces through browser](./Images/access_server.png)
## Routes for Todo Application
#Create routes directory and create a file api.js on it and also configure api.js
![api.js configuration](./Images/routes_configuration.png)






![alt text](image.jpg)







![alt text](image.jpg)