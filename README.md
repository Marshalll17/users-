# User Authentication System

## Overview
This project is a full-stack application that implements a user authentication system. It features a React frontend with Material-UI for styling and a Node.js backend with Express and MongoDB for data storage.

## Features
- User registration with email and password
- User login with email and password
- Secure password hashing using bcrypt
- JSON Web Token (JWT) based authentication
- Protected routes on the frontend
- Responsive UI using Material-UI components

## Tech Stack
- Frontend: React, Material-UI, Axios
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT, bcrypt

## Setup and Installation

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running

### Backend Setup
1. Navigate to the backend directory:
 cd backend

2. Install dependencies:
   npm install

3. Create a `.env` file in the backend directory and add your MongoDB URI and JWT secret:
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret

 4. Start the backend server:
     npm start
 ### Frontend Setup

1. Navigate to the frontend directory:
   cd frontend

2. Install dependencies:
   npm install

3. Start the React development server:
npm start


## Usage
- Open your browser and go to `http://localhost:3000`
- Register a new user account
- Log in with your credentials
- Explore the protected dashboard

## API Endpoints
- POST `/api/register`: Register a new user
- POST `/api/login`: Authenticate a user and receive a JWT

## Future Improvements
- Add email verification
- Implement password reset functionality
- Add social media authentication options
- Enhance error handling and user feedback

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.
