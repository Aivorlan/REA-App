# REA-App
Reverse Engineering Authentication.

# Unit 14 Sequelize Homework: Reverse Engineering Code
AS A developer

I WANT a walk-through of the codebase

SO THAT I can use it as a starting point for a new project

GIVEN a Node.js application using Sequelize and Passport

WHEN I follow the walkthrough

THEN I understand the codebase

# How It Works 
This app allows the user to log in and out. It also allows the user to sign up. 
## Routes
The main page URL is `"/"`.
Going to the URL ending in `/login` and `/members` will take you to the page that checks if you have an existing account. If you have an existing account you will be taken to the `/members` page. If you are not authenticated when you go to the main page URL ending in `"/"` this app will display the Sign Up Form page (`/public/signup.html`). When you see the form you must enter an email address and password to sign up. If this field is left empty an error will be shown. 
## B)
## C)
