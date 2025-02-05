# Task-Manager

Project Setup Guide
Step 1: Navigate to the Root Directory
Ensure you are in the root directory of the project.
cd /path/to/project/root
Step 2: Set Up the Backend
Move into the backend directory and install dependencies:
cd backend
npm install
Step 3: Return to the Root Directory
Navigate back to the root folder:
cd ..
Step 4: Set Up the Client
Move into the client directory and install dependencies:
cd client
npm install

Step 5: Configure Environment Variables
Create a .env file inside the backend directory and add the following environment variables:
MONGODB_URI="mongodb+srv://anchal90279:n7nsrjbzX1pvyDiE@cluster0.erkcd.mongodb.net/"
JWT_SECRET=anchal
CLIENT_URL=http://localhost:3000
PORT=8000
Step 6: Run the Project
Start the Backend Server
Navigate to the backend directory and run:
cd backend
npm start
Start the Client
Open a new terminal, navigate to the client directory, and run:
cd client
npm run dev
Your project should now be running successfully.
•	Ensure that Node.js and npm are installed on your system before proceeding.
•	Modify the .env file as needed for production or different environments.
•	If you face any errors, check the logs and dependencies to resolve them.
