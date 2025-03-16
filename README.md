# MERN Authentication

A full-stack authentication system built using the MERN stack (MongoDB, Express, React, and Node.js), featuring user registration, login, authentication, and protected routes.

---

## Features

- User authentication with JWT (JSON Web Token)
- Password hashing using bcrypt
- Secure API endpoints with authentication middleware
- React frontend with protected routes
- MongoDB Atlas or local database support

## Tech Stack

### Frontend:

- React.js (with React Router)
- React Router (for navigation)
- Tailwind CSS for UI styling
- Axios for API requests

### Backend:

- Node.js with Express.js
- MongoDB with Mongoose (for database management)
- JWT Authentication

### Additional Tools:

- Node.js (runtime)
- Express.js (backend framework)
- MongoDB (database)
- Mongoose (ODM for MongoDB)
- JWT (jsonwebtoken) (authentication)
- bcrypt (password hashing)
- dotenv (environment variables)
- CORS (cross-origin resource sharing)

## Setup Instructions

### Prerequisites:

- Node.js and npm installed
- MongoDB installed or a cloud MongoDB database (MongoDB Atlas)

### Installation

1. **Clone the Repository**
   ```bash
   https://github.com/abhishekrajsingh25/MERN-Authentication.git
   cd MERN-Authentication
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```
   
4. **Environment Variables Setup**
   Create a .env file in the root directory of the backend with the following:
   ```bash
   MONGODB_URI = your_mongo_database_uri
   JWT_SECRET = your_jwt_secret_key
   NODE_ENV = "development"
   SMTP_USER = your_smtp_gmail
   SMTP_PASS = your_smtp_password
   SENDER_EMAIL = your_gmail
   FRONTEND_URL = "http://localhost:5173"
   ```

6. **Environment Variables Setup**
   Create a .env file in the root directory of the frontend with the following:
   ```bash
   VITE_BACKEND_URL = "http://localhost:4000"
   ```
   
### Running the Application

1. **Start the Backend Server**
   ```bash
   cd backend
   npm run dev
   ```
   The backend server should now be running on `http://localhost:4000`.

2. **Start the Frontend**
   ```bash
   cd ../frontend
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5173`.


## Deployment

- The frontend can be deployed using Vercel.
- The backend can be deployed using Vercel.
- MongoDB can be hosted on MongoDB Atlas.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues.

---

Thank you for visiting. I hope you find my work interesting and valuable! To see the Website. 
- Click <a href="https://mern-authentication-abhishekrajsingh.vercel.app/" >Here</a>.
