# The Blog Spacer

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation / Usage](#installation--usage)
- [Links](#links)
- [Summary](#summary)
- [Screenshots](#screenshots)

## Overview
**The Blog Spacer** is a CMS-style blog platform that allows users to create an account, post content, and engage with other users through comments. 
With a user-friendly interface and robust features, the site empowers users to express their thoughts, share blog posts, and interact with the community. 
The homepage displays all posts, and users can view, comment on, or even delete and edit their own posts from their profile dashboard. 
The app offers smooth navigation, personalized experiences, and a secure authentication system for seamless user interaction.

## Features
- **Account Creation:** Users can sign up by providing a username and password, and once registered, they can log in to access their dashboard and create posts.
- **Posting & Commenting:** Logged-in users can write and publish blog posts. They can also comment on existing posts, enhancing user interaction.
- **Dashboard Management:** Users can view, update, and delete their posts from the dashboard.
- **User Session Timeout:** For security, users will be logged out after a certain period of inactivity, requiring re-login to make any changes or post content.

## Technologies Used
- **JavaScript:** Used for front-end functionality and backend logic.
- **CSS:** For styling the front-end pages.
- **SQL (MySQL / Sequelize):** Database management to store user data, posts, and comments.
- **Handlebars:** Templating engine to render dynamic content to the user interface.
- **Render:** Platform used for deploying the application.

## Installation / Usage
For local: 
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/san1718/mc14_TheBlogSpacer
   ```
2. **Install Dependencies:**
    ```bash
    npm install
    ```
3. **Set Up Database:** Ensure your database is set up with the correct configurations. Create a `.env` file and add your database credentials:
    ```plaintext
    DB_NAME=your_database_name
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    ```
4. **Seed the Database:** Add sample data to your database:
    ```bash
    npm run seed
    ```
5. **Run the Application:** Start the server:
    ```bash
    npm start
    ```
6. **Access the Application:** Open your browser and navigate to
    * [http://localhost:3001](http://localhost:3001)

## Links
[Home](https://github.com/san1718/mc14_TheBlogSpacer)
<br />
[Deployed](https://theblogspacer.onrender.com/)

## Summary
**The Blog Spacer** is a dynamic blogging platform designed to provide an engaging experience for users looking to share their thoughts and connect with others through comments. 
The app includes secure user authentication, an intuitive dashboard for managing posts, and a homepage that showcases the latest content. 
It offers essential features like user account creation, comment functionality, and session management, making it an ideal tool for developers and content creators to share their ideas in a modern, user-friendly environment.

## Screenshots
<img width="1512" alt="Homepage" src="https://github.com/user-attachments/assets/f333cedd-a1d6-431d-b0ad-d673935c05a1" />
<img width="1512" alt="Signup" src="https://github.com/user-attachments/assets/605c1810-ba68-4db5-be4f-6f415c103aab" />
<img width="1512" alt="Profile" src="https://github.com/user-attachments/assets/d662fc33-e4e8-4fe0-9391-e78888e805ba" />
<img width="1512" alt="PostComment" src="https://github.com/user-attachments/assets/663222e8-dc7b-43f0-933f-a8b7853dba0d" />
