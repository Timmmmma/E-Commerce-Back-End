# 13 Object-Relational Mapping (ORM): E-Commerce Back End
# Employee-Tracker
  ![badge](https://img.shields.io/badge/license-ISC-brightgreen)<br />
  
  ## Description 
  This challenge is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.
  
  ## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation 
  Download or use `git clone` from the <a href="https://github.com/Timmmmma/E-Commerce-Back-End.git">Link</a>, then open in terminal and run `npm install`.
  ## Usage 
  First of all, please connect to the MySQL and create database.
  
  Run `mysql -u USERNAME -p` and input your password,
  
  Run `SOURCE db/schema.sql` and `quit`,
  
  Run `npm run seed` to seed the database,
  
  Run `npm start` 
  
  <a href="https://drive.google.com/file/d/1wxHlcBiLTbKF_wL2CKC8s4P5ff0E9kGy/view?usp=sharing">Screencastify</a>
  
  If there is any error, please check the .json file and fix it by run `npm install`, `npm install mysql2 `, `npm install sequelize`, `npm install dotenv`
  ## License 
  ISC
  ## Tests
  This app is not required to test
  ## Questions
  If you have any questions about this projects, please contact my <a href="https://zhentian222@gmail.com">Email</a> or <a href="https://github.com/zhentian">Github</a>.

