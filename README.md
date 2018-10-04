![ETHExplorer V2 Screenshot](http://i.imgur.com/wgROAS9.png)


**Project Title:**

 ### ETHExplorer - Nodejs
 

For one of our clients I created a private Ethereum blockchain and had to create an Eth Explorer. I found many Eth explorers implemented in Angular Js and they were quite slow. Moreover, Angular Js version of Eth explorer requires Ethereum Node to be exposed to public access. I felt security threats and implemented the equivalent version in Nodejs (https://nodejs.org/en/) and used EJS (https://www.npmjs.com/package/ejs) to template this Nodejs app. Its faster, lighter. Some of the features might be missing like refreshing blockchain info on regular intervals etc., Will add web sockets in future version and try to cover all the features. Thanks to Carsenk (https://github.com/carsenk/). I used his Angular version as the reference code.

**Prerequisites** :

- Basically, we need **Nodejs**.

**Installation:**

- You can install node.js from the site: [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

- After cloning run **npm install** in the root folder of the project.

- Start the project using **node app.js**

- Then visit [http://localhost:80](http://localhost:80)(port number in app.js) in your browser of your choice.
 
 
 

