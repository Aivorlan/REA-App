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
# Routes

## Main page 
* The main page URL is `"/"`.
Going to the URL ending in `/login` and `/members` will take you to the page that checks if you have an existing account. If you have an existing account you will be taken to the `/members` page.

## Sign-Up page 
* If you are not authenticated when you go to the main page URL ending in `"/"` this app will display the Sign Up Form page (`/public/signup.html`). When you see the form you must enter an email address and password to sign up. If this field is left empty an error will be displayed. 
 
 ## Login page 
 * On the Sign Up Form there is an 'Or log in here' link that routes you to the URL ending in  `/login` where the user is presented with the Login Form. You must enter the email address and password to log in. A "Welcome ${yourEmailAddress}" will be shown once you are authenticated.  
# Installation 
* npm install 
* express
* sequelize
* mysql
## Questions 
<br>
<img src='https://avatars3.githubusercontent.com/u/65247434?v=4' height='200px' alt='github avatar'>
<br>
<a href='https://github.com/Aivorlan'>Github Profile: Aivorlan</a>
<br>
If you have any questions, please feel free to contact me via email or LinkedIn message.
<br>
Email: OfficialQuin@icloud.com
<br>
<a href='https://www.linkedin.com/in/quinton-bryant-485a121a7'>Click here to message me on LinkedIn</a>


