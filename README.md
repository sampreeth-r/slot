# Slot Booking System
This is a MERN stack project that allows users to book slots for various services and events. Users can log in using their email and a one-time password (OTP) that is sent to their email. The project uses ReactJS for the front-end, NodeJS for the back-end, and MongoDB for the database.

Features
Users can view the available slots for each service or event and book the ones they want.
Users can cancel their bookings at any time before the slot starts.

Installation
To run this project locally, you need to have NodeJS and MongoDB installed on your machine. You also need to set up some environment variables in a .env file in the root directory of the project. The variables are:

PORT: The port number for the server is 3000.
MONGO_URI: The connection string for MongoDB. You can use a local or remote database.
JWT_SECRET: The secret key for generating JSON Web Tokens (JWT) for authentication.
MAIL_USER: The email address for sending OTPs to users. You need to have a Gmail account and enable less secure apps access.
MAIL_PASS: The password for the email address.
After setting up the environment variables, you can install the dependencies and start the project by running the following commands in the terminal:

# Install dependencies for server
npm install

# Install dependencies for client
cd client
npm install

# Run the client & server with concurrently
npm run dev

The project will be running on http://localhost:3000 for the client and http://localhost:8080 for the server.
