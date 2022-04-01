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
# Create routes directory and create a file api.js on it and also configure api.js `mkdir routes && touch api.js && vim api.js`
![api.js configuration](./Images/routes_configuration.png)

## Install mongoose and create new directory models to work with routes  #install mongoose`npm install mongoose`
![mongoose install](./Images/mongoose.png)
![cluster created](./Images/cluster-A.png)
#create new directory models, create new file todo.js and configure `mkdir models && cd models && touch todo.js`
# Update api.js files configuration on routes directory with `vim api.js`
![update api.js configuration](./Images/routes_configuration_update.png)
### connecting database `node index.js`
![database connected succefully](./Images/node_index.js.png)

### Install postman into your system and test all the API endpoints CRUD and make sure they are working 
![GET running succesfully](./Images/GET-Test.png)

![POST running succesfully](./Images/POST%20test.png)

# FrontEnd Creation
## Creating a user interface for a Web client broeser to interact with application Todo via API
### Create a new folder in todo called client using `npx create-react-app client`
## Installing dependies concurrently and nodemon with `npm install concurrently --save-dev && npm install nodemon --save-dev`
![concurrently succesfuly installed](./Images/concurrently.png)
![nodemonn succesfuly installed](./Images/nodemon.png)
### edit the code in package.json file in Todo folder to use the dependencies
![script edit](./Images/script%20edit.png)
### configure proxy in client package.json file to let the application run on url without adding the path /api/todos/ `cd client && nano package.json`
![proxy configuration](./Images/add_proxy.png)
`npm run dev` 
### cd client/src and then mkdir components and create Input.js, ListTodo.js and Todo.js
`touch Input.js ListTodo.js Todo.js`
### edit Input.js file by inserting given code, open file using `nano Input.js`
![Input.js configuration](./Images/Input.js_file_configuration.png)
### install axios used to make request from node.js in your client directory using
`npm install axios` 
### edit a ListTodo.js file in components directory using nano
![ListTodo.js configuration](./Images/ListTodo.js_configuration.png)
### also edit Todo.js file using nano too `nano Todo.js`
![Todo.js configuration](./Images/Todo.js_configuration.png)
### run dev with npm in Todo directory to enable your application in http url
`npm run dev`
![run dev](./Images/npm_run_dev.png)
![Application on server](./Images/access_server.png)
