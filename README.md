A full-stack chat application built using the MERN stack:

Frontend: ReactJS
Server: NodeJS
APIs: ExpressJS
Database: MongoDB
Socket.IO

Run Locally

Follow these steps to set up and run the project on your local machine.

Prerequisites

Ensure you have the following installed:

Node.js

MongoDB (local or cloud-based, e.g., MongoDB Atlas)

Git

Setup Instructions

1. Clone the Repository

git clone

2. Navigate to the Project Directory

cd 

3. Install Server Dependencies

npm install

4. Set Up Environment Variables

Create a .env file in the root directory and add the following:

MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key

5. Start the Server

npm run start

6. Install Frontend Dependencies

cd frontend
npm install

7. Start the Client

npm start

Access the Application

Once the server and client are running:

Backend API: http://localhost:5000

Frontend: http://localhost:3000
