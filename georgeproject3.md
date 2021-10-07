# SIMPLE TO-DO APPLICATION ON MERN WEB STACK

<img width="538" alt="1MERN STACK DIAGRAM" src="https://user-images.githubusercontent.com/89888370/136368195-46d50228-74be-4b77-9362-830b94270c7f.PNG">

### MERN Web stack consists of following components:

**MongoDB:** A document-based, No-SQL database used to store application data in a form of documents.

**ExpressJS:** A server side Web Application framework for Node.js.

**ReactJS:** A frontend framework developed by Facebook. It is based on JavaScript, used to build User Interface (UI) components.

**Node.js:** A JavaScript runtime environment. It is used to run JavaScript on a machine rather than in a browser.

## Task
To deploy a simple To-Do application that creates To-Do lists

**Install Node.js with the command:**
"sudo apt-get install -y nodejs"

<img width="680" alt="NODE JS INSTALLED" src="https://user-images.githubusercontent.com/89888370/136368539-456c6f16-46ac-4719-9222-8c24260716f3.PNG">

## Application Code Setup 
**Create a new directory for your To-Do project:** : mkdir Todo

Run **"npm init"** to initialise your project.

Run the command **"ls"** to confirm that you have package.json file created.

Next, Install **ExpressJs** and create the Routes directorY: **npm install express**

Now create a file *index.js* with the command below: **touch index.js**

Install the dotenv module:  **npm install dotenv**

we need to create *routes* that will define various endpoints that the To-do app will depend on. create a folder **routes** : mkdir routes

create create a file **api.js**  in *routes* folder

install mongoose which is a Node.js package that makes working with mongodb easier: **npm install mongoose**

Create a new folder *models* : **mkdir models** and create a file and name it **todo.js**

<img width="455" alt="SERVER RUNNING ON PORT 5000" src="https://user-images.githubusercontent.com/89888370/136369577-d73d2952-fe2f-459a-afac-ad8be2c20a18.PNG">

**Express working on brower on port 5000**

<img width="956" alt="EXPRESS WORKING ON BROWSER" src="https://user-images.githubusercontent.com/89888370/136369795-657191da-a809-4481-837f-37d7f2f0bbb7.PNG">





