# Project title
- CS50 Final Project URL: https://www.youtube.com/watch?v=slmdEhiBEn0

# Description
- CS50 Final Project is a web-based application using JavaScript, Python, Flask and SQL
- on which a user can register a new account, login, view details, view home, update details, and logout.
- the register page, a user is able to enter his or her information, including user name, email, and password.
- then press register, which sends a post-reguest to save your date in date base.
- the login page, a user uses the details that were provided earlier during registration (username, password) to login ino system.
- the home page, a Logged in successfully message is displayed with a header that says Welcome!! CS50 Home Page.
- In the side bar, there are 4 buttons: home, user details, update info, and logout, so the user could switch through those pages.
- the user details page, all the user's details are shown.
- On the update page, a user is able to update information, for example, a password or email.
- If the logout button is clicked, the system will logout, and the user must provide login details again to login into the system.
- This project satisfies all the web application rules, including ( CURD ) POST, GET, UPDATE.
- It uses user authentication and verification at both the front-end and back-end levels.



# How to deploy and run
- Create mysql database with the name cs50_final_project
- Import the attached file cs50_final_project.sql to your database
- Change the db connection params in app.py bassed on your db details
- Open the project with your preferred IDE
- Flask run
- Browse to http://127.0.0.1:5000 
- On login page switch to register page to create new account
- Use the account details (username and password) to login
