

 # Travel Diary

## Video Demo
[Watch the Demo](https://youtu.be/zFsoJGLjs1c)

## Description
Travel Diary Application
Introduction
The Travel Diary is a full-stack web application designed to help users document, organize, and cherish their travel experiences. Built using the MERN (MongoDB, Express, React, Node.js) stack, this application offers a user-friendly interface and robust backend to manage travel notes effectively. Whether it’s planning future trips or reminiscing past adventures, Travel Diary provides a secure and feature-rich platform for travelers.

Features
1. User Authentication
   Secure login and signup functionality to ensure only authorized users can access their notes.
   Passwords are securely hashed and stored using industry-standard practices (e.g., bcrypt).
   JSON Web Tokens (JWT) are used for session management.
2. Note Management
   Users can create, update, and delete travel notes effortlessly.
   Each note can include a title and detailed content.
3. Pin Important Notes
   Users can pin their important notes, which keeps them at the top of the list for quick access.
4. Search Functionality
   Built-in search bar to find specific notes by title or content keywords.
   Instant search results ensure a smooth user experience.
5. Responsive Design
   Fully optimized for mobile and desktop devices to ensure accessibility anywhere.
6. Secure Database
   Notes and user data are stored in a MongoDB database, ensuring scalability and reliability.
   Technologies Used
## Frontend
   React.js: For creating an interactive and dynamic user interface.
   React Router: To manage navigation between pages.
   CSS: For styling components and ensuring a responsive design.
## Backend
   Node.js: For server-side execution and handling API requests.
   Express.js: For building RESTful APIs and managing server-side logic.
## Database
   MongoDB: A NoSQL database for storing user data and travel notes.
   Mongoose: An ODM library for MongoDB to streamline database operations.
## Authentication and Security
   JWT (JSON Web Tokens): For secure session management.
   bcrypt.js: For hashing passwords before storage.
## Project Workflow
## Backend Workflow
1. API Endpoints:

   Endpoints for user authentication (register/login/logout).
   CRUD (Create, Read, Update, Delete) operations for notes.
2. Database Integration:

   MongoDB is used to store user and note data.
   Efficient indexing for faster search functionality.
## Frontend Workflow
1. User Interface:

   Intuitive forms for user login/signup and note creation.
   Clear navigation for viewing, editing, and pinning notes.
2. Dynamic Content:

   State management with React hooks.
   Real-time updates for notes and search results.

Stay organized and cherish your travel memories with **Travel Diary**!


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## Future Enhancements
Photo Attachments: Allow users to upload images to their notes.
Collaborative Notes: Enable group sharing and editing of notes.
Offline Access: Provide offline functionality using service workers.
Notifications: Set reminders for planned trips or upcoming events.

## Execution Steps

### Running the Travel Diary App

#### Backend (Express.js)
1. Open your terminal and navigate to the `backend` folder:
   cd backend
2. Install dependencies:
   npm install

3. Connect MongoDB:
   Copy the MongoDB connection string from your MongoDB account.
   Open the config.json file in the backend folder and paste the connection string.
   Replace <password> in the connection string with the correct user password.

4. Start the backend server:
   npm Start

  ## Frontend (React.js)

1. Navigate to the frontend/travel-diary-app folder
   cd frontend/travel-diary-app
2. Install dependencies
   npm install
3. Start the React development server:
   npm run dev

## Once completed, the frontend server will open the app in your default web browser.




Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
