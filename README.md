# ONGC Quiz Management App System

## Overview
The ONGC Quiz Management App System is a web application built using React and PHP that serves as a comprehensive solution for managing and conducting quizzes within the ONGC organization. This system is divided into three main folders: "ongc," "login-system," and "cra." The "ongc" folder contains the PHP application for ONGC admin users to manage the quiz database, including creating, updating, and deleting questions. The "login-system" folder houses the PHP application responsible for user authentication and authorization. Once authenticated, users can access the quiz page in the "cra" folder, which is implemented in React. The React app fetches questions from the SQL database managed by ONGC admin and provides a user-friendly interface for answering quiz questions. The system also offers functionality to display quiz results, sorted by quiz attempts, for authorized users, viewable exclusively by admin users. Admin users have the ability to publish results as needed.

## Folder Structure

### 1. ongc
This folder contains the PHP application for ONGC admin users to maintain the quiz database. Key features include:
- Creating and managing quizzes.
- Adding, updating, and deleting questions.
- Starting and ending quizzes.
- Managing quiz data in the SQL database.
![WhatsApp Image 2023-11-02 at 23 46 22_bb43d02a](https://github.com/Birajj2189/quiz-management-system/assets/93638316/910d8546-0a25-4096-b03f-4c0efde8382b)

![WhatsApp Image 2023-11-02 at 23 52 51_cef3ebe6](https://github.com/Birajj2189/quiz-management-system/assets/93638316/520bee74-89d9-4a72-9a57-f6bbc4a3458f)


### 2. login-system
In this folder, you will find the PHP application responsible for user authentication and authorization. Key features include:
- User registration and login.
- Authorization control to ensure only authorized users access the quiz section.
- Secure user authentication and session management.
  ![WhatsApp Image 2023-11-02 at 23 46 25_ee94077e](https://github.com/Birajj2189/quiz-management-system/assets/93638316/6f8879da-7ac7-4ded-a235-c751abe0681f)
  
  ![WhatsApp Image 2023-11-02 at 23 48 42_429ae243](https://github.com/Birajj2189/quiz-management-system/assets/93638316/1f6c845c-052a-4fd9-91e6-194535717c6d)


### 3. cra
The "cra" folder houses the React application responsible for the user interface, question verification, and validation. Key features include:
- Displaying quizzes for authorized users.
- Fetching quiz questions from the SQL database managed by the admin.
- User-friendly and responsive quiz interface.
- Verification and validation of user responses.
- Displaying quiz results for authorized users, sorted by quiz attempts.
![WhatsApp Image 2023-11-02 at 23 54 18_7e559d1c](https://github.com/Birajj2189/quiz-management-system/assets/93638316/acc8e017-9a15-487d-abb6-7d72611366a3)


## Getting Started

### Prerequisites
Before you can use the ONGC Quiz Management App System, you'll need the following:
- Web server (e.g., Apache) with PHP support.
- MySQL database for storing quiz data.
- Node.js and npm for running the React app.

### Installation

1. **Set Up the Database:**
   - Create a MySQL database and import the provided SQL schema to set up the quiz database.

2. **ongc (PHP App):**
   - Configure the database connection in the PHP files within the "ongc" folder to point to your MySQL database.
   - Deploy the "ongc" folder on your web server.
   - Access the admin site to create quizzes and manage questions.

3. **login-system (PHP App):**
   - Configure the database connection in the PHP files within the "login-system" folder.
   - Deploy the "login-system" folder on your web server.
   - Users can register and log in here, with authorization to access quizzes.

4. **cra (React App):**
   - Navigate to the "cra" folder.
   - Run `npm install` to install the required dependencies.
   - Configure the React app to communicate with the PHP API endpoints for user authentication and quiz data.
   - Run `npm start` to start the React app. It will be accessible at a specified URL.

## Usage

1. **Admin Users:**
   - Access the "ongc" folder to create quizzes and manage questions.
   - Start and end quizzes as needed.
   - View and manage quiz results.

2. **Authorized Users:**
   - Register and log in through the "login-system" folder.
   - Access quizzes through the "cra" folder.
   - Attempt quizzes, review results, and check your progress.

3. **Admin Users (Result Publication):**
   - Admin users can publish quiz results when they choose.

## Additional Notes

- Ensure proper security measures are in place to protect sensitive user and quiz data.
- Regularly back up the database to prevent data loss.
- Secure the PHP and React applications from unauthorized access.
- Keep the system up to date with the latest security patches and updates.

  Optional Extended Description
The ONGC Quiz Management App System not only simplifies quiz administration but also introduces a layer of interactivity and engagement for quiz participants. With a well-structured folder system, powerful features, and a carefully planned user journey, this system provides ONGC with a robust platform for knowledge assessment.

As a testament to its flexibility, the system caters to both ONGC admin users responsible for creating and maintaining quizzes and authorized users looking to expand their knowledge base. The system is fortified with security measures, ensuring that sensitive data is safeguarded throughout the process.

A particularly noteworthy feature is the ability of ONGC admin users to schedule quizzes, allowing for tailored assessments that align with ONGC's training and development goals. This capability ensures that quizzes are conducted at the most opportune times.

The "cra" folder, powered by React, introduces a rich and immersive quiz-taking experience, making learning engaging and enjoyable. It is designed to accommodate a variety of quizzes, making it versatile for different types of knowledge assessments within the organization.

To enhance the educational experience, the React app incorporates verification and validation mechanisms to ensure the accuracy and fairness of quiz results. It displays results in an easy-to-read format, offering insights into individual and collective performance, which can be vital for ONGC's training and development efforts.

The ONGC Quiz Management App System is more than a tool; it is an investment in ONGC's continuous learning and development, a commitment to ensuring that knowledge remains relevant and up-to-date in a dynamic industry. The system's optional extended description underscores its role as a central pillar in ONGC's pursuit of knowledge excellence.
