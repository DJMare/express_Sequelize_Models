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


(14) Add the connection information to connect to mySQL in routes/index.js file: 

NODEMON NOTE

Sometimes nodemon crashes in Windows 10 and there is a simple fix:

(1) Open Task manager (press Ctrl+Alt+Delete)

(2) Select the 'Processes tab'

(3) Search for 'Node.js: Server-side JavaScript'

(4) Select it and click on 'End task' button

Now you can run npm start.
