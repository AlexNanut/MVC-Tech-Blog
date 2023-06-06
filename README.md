# 14 Model-View-Controller (MVC): Tech Blog

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description.

The Tech Blog is a Heroku deployed application, allowing developers writing about technical concepts, recent advancement and new technologies. It allows users to publish blog posts and comment on other developers' posts as well. 

## Table of Contents:
- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [User Story](#User-Story)
- [Built With](#Built-With)
- [What I Learned](#What-I-Learned)
- [Continued Development](#Continued-Development)
- [Author](#Author)


# Overview

## The Challenge:

The challenge of building this application involved creating a platform that could support multiple users, where users can add blog posts and comments allowing users to authenticate themselves and protect their personal data. The application had to be built using modern web development technologies and follow best practices, including the MVC architecture pattern.

## User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

## Acceptance Criteria

```md
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```
## Usage Instructions:

#### Visit the homepage, "Login" or "Sign Up" for an account if you don't already have one.

1. Account login: click on "login" in the navigation menu - enter Username and Password then click "Sign In" to proceed.
2. Account Sign Up: click on "Sign Up" in the navigation menu - once open, enter Username, Email and Password then click "Sign Up" to proceed.
3. Once you have an account, you can create blog posts. 
4. Create a blog post: click on the "dashboard" option in the navigation menu and select "Create a New Blog Post."
5. Account Log out: click on "logout" in the navigation menu.

## Deployed Application Link:
[Deployed Application Link:](https://mvc-tecblog.herokuapp.com/)

## GitHub Repository:
[GitHub Repository:](https://github.com/AlexNanut/MVC-Tech-Blog)

## Screenshots: 
### Figure 1. Screenshot signup
<img width="1440" alt="Screenshot signup" src="https://github.com/AlexNanut/MVC-Tech-Blog/assets/108309770/5470256f-ba6a-48d8-af0e-118a575d2669">

### Figure 2. Screenshot login 
![Uploading Screenshot login.png…]()

## Built With:

- JSON
- Dynamic JavaScript
- Node.js 
- Express.js
- Bcryptjs
- Connect Session Store using Sequelize: [6.32.0]
- Dotenv: [16.1.3]
- Express: [4.18.2]
- Express Handlebars: [7.0.7]
- Express-Session: [1.17.3]
- Handlebars.js: [4.7.7]
- Node MySql2: [3.3.3]
- Sequelize: [6.32.0]
- Visual Studio Code

## What I Learned:
1. Implementing Model-View-Controller (MVC) architecture.
2. Creating and interacting with a MySQL database using Sequelize ORM.
3. Creating and using Express.js servers and routes.
4. Using Handlebars.js to create and display dynamic templates.
5. Implementing user authentication and password hashing with bcrypt.


### Continued Development:
1. Pagination for blog posts and comments.
2. Learning more about how handlebars work. 
3. Editing and deleting comments.

## Author
Follow me on Github at [AlexNanut](https://github.com/AlexNanut)
