# logInOut simple app

# ASSIGNMENT REQUIREMENTS
In this assignment you will be required to make a signup and login page that uses MySQL to store all data

# SIGN UP PAGE
- Create table in mysql database to store username, email and password
- Display error message if user tries to signup with an existing username / email
- If there is a match it should take the user to a page that allows them to edit their username, email, password or delete their account
- If the is username does not match any username in the database then a error message should say “This user does not exist, Please sign up”
- If the is username matches but not the password in the database then a error message should say “Incorrect password”

# LOGIN PAGE
When a user logs in the backend should compare the username and password with the existing Database entries

# UPDATE PAGE
- When a user deletes his account he should be redirected to the login screen
- When you first log in to the website you should go to the login screen with a button to go to signup page

# ADMIN USER
- Create an admin user that is stored in the database
- When that user logs into the system is should display a list all users in the system

To start:
```
git clone master http-path
import users.sql in database folder to your database
start the server for database (Apache for example)
npm install
npm start
```
<<<<<<< HEAD

To modify the connection for database:
 - Goes to database/mysqlDatabase and change the properties of object in mysql.createConnection
=======
>>>>>>> 39ca8a5b7f8bbd0246a7f4fa9554a72d6a92e975
