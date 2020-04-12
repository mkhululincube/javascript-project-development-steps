## Project development

> Tutorial will be based on javascript projects however the knowledge can be applied on any type of software project :


To demostrate we will use the tools below:


>Front End - React

>Backend - Node JS

>Database - MongoDb/MySQL

## Steps

## PLANNING

This is the stage in which UML Diagrams are crafted.

> Determine the size of project

> Timeline for the project

> Number of people that will be working on the software project

The number of people working on the project, timeline and size of project will help you 
chose the suitable Software Development Methodology.

> Upon chosing the methodology determine the tools to be used.

## Project Management Tools 

> Jira/Trello/Asana etc

For bigger and complex projects Jira is the most suitable

> Kanban boards - visually depict work at various stages of a process using cards 
to represent work items and columns to represent each stage of the process.

### Assign tasks

Depending on the the methodology being used


## DESIGN

Personel involved : Designers, Business developers and Product Owners

Project Wireframes / Mockups

There are quite a number of wireframing tools that you can use. 

However I have used Justinmind.

Submit wireframes for approval. Once they are approved its time to move to the next stage which is development.


#DEVELOPMENT

Personel involved : Developers, Architects, Database Administrators and DevOps

### Tools

Tools are determined by the size of the project.

####Version Control

Using version control software helps you keep track of changes — and keep every team member working off the latest version

For version control you can use git, svn, mercurial or subversion depending on your preference and project spec however Git is widely used, hence we will use [Git](https://git-scm.com/).


#### Docker 

Use of Containers

> To mantain same environment between your team members

> Version control system for your entire app's operating system


#### CI/CD Continous Integration and Development

CI/CD refers to the set of operating principles, and collection of practices that enable application development teams to deliver code changes more frequently and reliably. 
The CI/CD is also known as the CI/CD pipeline.


For CI/CD you can use Jenkins, Netlify, Circle CI or Travis CI depending on project spec and tools that you are using.

In our case we will use [Netlify] (https://www.netlify.com/)


#### Code Editor / IDE

Speed and and developement experience will be determined by the ide you use. Use IDE that you are comfortable with and take note research
about the IDE extensions that will increase your productivity.
Visual Studio code [VSCode](https://code.visualstudio.com/download) is widely used in Javascript Community.



####Environment setup

> Download and setup node js [nodejs](https://nodejs.org/en/download/)

> Download and set up git bash [gitbash](https://git-scm.com/downloads)

> Download and setup code editor/IDE of your choice



#### Create your folder structure

Its a matter of preference however it's always advisable to follow MVC Standards folder structure.



#####React Js and Node Js (Express) Folder Structure


> React JS - Front End

> Node Js (Express) - (backend / API) 


Create Application Folder

Inside Application folder create 2 folders namely:

> frontend

> api

Your react code will reside inside frontend folder

Your node js code will reside inside api folder


Open your terminal or git bash and change directory to your frontend folder then execute the commands below:

You can go the webpack way or the less complicated way using create-react-app



```` npm install install create-react-app -g ````

```` create-react-app . ```` // . (dot) means create react app on the current folder which is frontend

All the neccessary files and packages will be installed and basic folder stucture will be created.

> Congatulations ! You have successfully installed react 

To start your react app run the command below :

```` npm start ````


###### HAPPY REACT PROGRAMMING !!!!!!


###BACKEND

Change directory to api folder

Create index.js (entry point)

Execute the command below :

```` npm init  // To initialise your packeges and create package.json ````

Create src folder

Inside src folder create the folders below:

> controllers // Business logic files

> middlewares // Middlewares

> models // Creation of Schema and interaction with database takes place here

> config // config files  

> routes // routes


Above is the basic/general folder structure of node applications

#### HAPPY EXPRESS PROGRAMMING


## TESTING

Personel Involved : Software Testers and QAs


Jest is widely used in react community

Read on Testing using Jest [Jest](https://jestjs.io/docs/en/getting-started.html)


## DEPLOYMENT AND MAINTENANCE

Personel Involved : Developers and DevOps

This is where CI/CD comes into play.

Read on CI/CD using [netlify](https://docs.netlify.com/)























