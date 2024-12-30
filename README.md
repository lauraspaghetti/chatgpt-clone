# ChatGPT Clone

## Overview

This project is a clone of ChatGPT developed using the **MERN stack** (MongoDB, Express.js, React, Node.js). It utilizes the **Gemini** model to deliver enhanced conversational AI capabilities. Users can ask questions and download images to receive detailed explanations on various topics. This application serves as both a practical implementation of core web development concepts and an interactive AI tool.

### Features

- **Interactive Q&A**: Users can input questions and receive instant answers.
- **Image Handling**: Users can upload images for analysis, allowing the AI to provide context-based explanations.
- **User Authentication**: Secure access to the application using Clerk.
- **Real-time Chat Streaming**: Engage in live AI-driven conversations.
- **Optimized Performance**: Leveraging image optimization techniques for smoother user experience.

## Technologies Used

- **Frontend**:
  - React 19: JavaScript library for building user interfaces
  - React Router DOM: For navigation and routing
  - Clerk: For user authentication
  - Axios: For making API calls
  - CSS/SCSS: For styling components
  - ImageKit: For image upload, optimization, and delivery

- **Backend**:
  - Node.js: Server-side JavaScript runtime
  - Express.js: Web application framework
  - MongoDB: NoSQL database for data storage

- **Integration**:
  - Gemini: AI model for processing queries and image uploads.

## Installation

### Database  

Create a .env file in the backend directory and add your database connection string and any other configuration variables needed for your application.

### Install Dependencies

1. **Backend**:
   Navigate to the backend directory and install dependencies:

   ```bash
   cd backend
   npm install
   ```

2. **Frontend**:
   Navigate to the frontend directory and install dependencies:

   ```bash
   cd client
   npm install
   ```

## Running the Application

### Backend

To start the backend server run:

```bash
cd backend
npm run start
```

### Frontend

To start the frontend development server run:

```bash
cd client
npm run dev
```

## Usage

1. **Ask Questions**: Enter your question in the designated input field and click the arrow or press enter to receive an answer.
2. **Upload Images**: Click on the upload button to select an image file, and the system will process it to deliver explanations related to the content of the image.

---

Feel free to edit any part of the documentation or let me know if there are specific areas you'd like to elaborate on or modify!

Sure! Here’s an updated version of the documentation, incorporating the topics you covered in the tutorial:

---
