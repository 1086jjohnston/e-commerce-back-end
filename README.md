# e-commerce-back-end

Here is a program for an e-commerce website that utilizes Sequelize to communicate with MySQL.

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

# How-to

1. Clone repository
2. Create an .env file in your code 
" DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='MySQL password' "
3. Run following commands on command line
  a. npm init
  b. npm intall mysql2
  c. npm install sequelize
  d. npm install dotenv
4. Run MySQL on command line
  a. mysql -u root -p (your MySQL password)
  b. source db/schema.sql
  c. quit
5. Run following commands on command line
  a. run npm seed
  b. npm start
6. you can run POST, PUT, DELETE tests in Insomnia now using localhost address. Enjoy!

[![Watch Youtube walkthrough here](https://img.youtube.com/vi/Bp4ctwUhpww/0.jpg)](https://www.youtube.com/watch?v=Bp4ctwUhpww)

