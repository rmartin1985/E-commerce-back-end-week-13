# E-commerce-back-end-week-13

  ![](https://img.shields.io/badge/license-MIT-blue)

  ## Description
 For this week's challenge, we were asked to create the back end for an e-commerce site. This challenge was two fold in nature.

 The first part of the challenge required me to create the Models for the database. Had to create Models titled Category, Product, ProductTag, and Tag. Each of these needed specific columns for their respective data in the e-commerce database. Then I had to make sure that all of the relational data was joined correctly using the proper Sequelize syntax. 

 The second part of the challenge entailed creating the CRUD (Create, Read, Update, Delete) operations for the API requests. Aside from a few bits of code that were provided for me, I was responsible for the rest of the code to create these routes using the proper syntax (GET, POST, PUT, DESTROY).

 All of the routes worked, however for some reason when using Insomnia Core to test the "Update Category by ID" route, it gives a "404" error code but you will see in the video that the update does in fact work. This route was curiously the one that was mainly provided for us. 

 There is a Screencastify video demo below showing all of these routes in action using Insomnia Core to test them all out. 

  ## Table of Contents
  1. [Installation](##installation)
  2. [User Story](#user-story)
  3. [Acceptance Criteria](#acceptance-criteria)
  4. [Demo](#demo)
  5. [Technology](#technology)
  6. [Questions](#questions)
  7. [License](#license)
  

  ## Installation
  1. Fork this repository
  2. Clone repository to your local directory
  3. Make sure you have installed Node.js 
  4. Run npm install to install the necessary dependencies
  ```
  npm install
  ```
  5. Run mysql 
  ```
  mysql -u root -p
  ```
  6. Load the schema 
  ```
  source db/schema.sql
  ```
  7. Seed the database
  ```
  npm run seed
  ```
  8. type "node server.js" or "npm start" in the command line to connect to the server
  ```
  node server.js
  ```
  ```
  npm start
  ```

  ## User Story
  ```
  AS A manager at an internet retail company
  I WANT a back end for my e-commerce website that uses the latest technologies
  SO THAT my company can compete with other e-commerce companies
  ```
  ## Acceptance Criteria
  ```
  GIVEN a functional Express.js API
  WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
  THEN I am able to connect to a database using Sequelize
  WHEN I enter schema and seed commands
  THEN a development database is created and is seeded with test data
  WHEN I enter the command to invoke the application
  THEN my server is started and the Sequelize models are synced to the MySQL database
  WHEN I open API GET routes in Insomnia Core for categories, products, or tags
  THEN the data for each of these routes is displayed in a formatted JSON
  WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
  THEN I am able to successfully create, update, and delete data in my database

  ```

  ## Demo

  [Screen Castify](https://watch.screencastify.com/v/INfl7dWsP2mt6BtOYJEh)

  ## Technology Used
  **1. [Node.js](https://nodejs.org/en/)**

  **2. [MySQL2](https://www.npmjs.com/package/mysql2)**

  **3. [Sequelize](https://www.npmjs.com/package/sequelize)**

  **4. [dotenv](https://www.npmjs.com/package/dotenv)**

  ## Questions

  If you have any questions regarding this project, you can reach me at my GitHub account or by email at:
  <br />
  Github: [rmartin1985](https://github.com/rmartin1985)
  <br />
  Email: rmartin1985@att.net

  ## License
  Licensed under the [MIT License](LICENSE)