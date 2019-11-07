# express_Sequelize_Models
An express app utilizing sequelize cli to connect to mySql database and to generate model file.

COMMAND PROMPT

(1) Run the following to navigate to your Desktop: 

    cd Desktop

(2) Create a new folder on desktop: 

    mkdir Express

(3) Navigate to the Express directory: 

    cd Express

(4) Run the following command to install the Express generator globally onto your computer: 

    npm install express-generator -g

(5) Enter the following command to generate the Express starter app. This will set the view to use Handlebars and will name the app express_: 

    express --view=hbs express_Sequelize_Models

(6) Once the process is complete, navigate into the express_Sequelize_Models directory: 

    cd express_Sequelize_Models

(7) Now in the express_ directory, run the following: 

    npm install

(8) Install Nodemon globally: 

    npm install -g nodemon
    
(9) Install Nodemon as a devDependency in the package.json file within the express_ directory:

    npm install -save-dev nodemon
    
(10) Install mysql2:

    npm install --save mysql2

(11) Install sequelize: 

    npm install --save sequelize@4.43.0

(12) Open in VS code:

    code . 


VS CODE

(13) Navigate to the routes/index.js file and update. Need to require the mysql2: ![open index js file (express_Sequelize_Models)](https://user-images.githubusercontent.com/35668707/68347978-7f1a6580-00ad-11ea-9ba9-6b75f52619b9.JPG)


(14) Require mysql2 in routes/index.js file: ![require mySql2 in index js file (express_Sequelize_Models)](https://user-images.githubusercontent.com/35668707/68348939-534caf00-00b0-11ea-8902-697f55517952.JPG)

COMMAND PROMPT

(15) Install Sequelize CLI commands globally onto your computer: 

    npm install -g sequelize-cli

(16) Create necessary sequelize folders and filed in project:

    sequelize init

VS CODE

(17) Open config/config.json file and change settings to connect to the database: ![open config json file (express_Sequelize_Models)](https://user-images.githubusercontent.com/35668707/68350121-3c0fc080-00b4-11ea-8960-c219bee9d7b0.JPG)

![update database settings to connect to sakila in config json file (express_Sequelize_Models)](https://user-images.githubusercontent.com/35668707/68350238-91e46880-00b4-11ea-8e89-a4a287998705.JPG)

COMMAND PROMPT

(18) Install mysql2 globally so sequelize CLI will be able to connect to the database:

    npm install -g mysql2
    
(19) Install sequelize-auto tool to generate model files: 

    npm install -g sequelize-auto

![install sequelize-auto tool in command prompt (express_Sequelize_Models)](https://user-images.githubusercontent.com/35668707/68350358-e7207a00-00b4-11ea-8f82-d8d093ac92eb.JPG)
    
MYSQL WORKBENCH

(20) Open database in mySql workbench to view columns in table: ![mySQL workbench schemas - Sakila database](https://user-images.githubusercontent.com/35668707/68350595-b5f47980-00b5-11ea-8d1b-dd9879921010.JPG)


NODEMON NOTE

Sometimes nodemon crashes in Windows 10 and there is a simple fix:

(1) Open Task manager (press Ctrl+Alt+Delete)

(2) Select the 'Processes tab'

(3) Search for 'Node.js: Server-side JavaScript'

(4) Select it and click on 'End task' button

Now you can run npm start.
