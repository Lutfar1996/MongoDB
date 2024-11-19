<h1>Fullstack Web Application - Simple Login System
</h1>

Welcome to the Simple Login System application! This full-stack web application allows users to log in using their email and password. The app uses React for the frontend, Node.js and Express for the backend, and MongoDB for storing user credentials.

🌟 Features:

User Authentication: Users can log in with their email and password.
Secure Password Handling: Passwords are hashed using bcrypt before storing in the database.
JWT Authentication: Uses JWT (JSON Web Token) to maintain user sessions.
Responsive Frontend: Built with React for a seamless user experience.
RESTful API: Backend exposes RESTful APIs for authentication.

🛠️ Technologies Used:

Frontend:

React
Axios (for API requests)
Backend:
Node.js
Express

Database:

MongoDB
Mongoose

Authentication:

JWT (JSON Web Token)
bcrypt (for password hashing)
🔧 System Design
High-Level Workflow

Frontend:

The user enters their email and password in the login form.
The frontend sends an HTTP POST request to the backend for authentication.
Backend:

The backend receives the login request and verifies the user credentials against the MongoDB database.
If credentials are valid, the backend generates a JWT token and returns it.
Database:

MongoDB stores user information, including hashed passwords.
Passwords are securely hashed using bcrypt before saving.
Authentication:

bcrypt is used for securely hashing and comparing passwords.
JWT is used for authenticating the user after login.
