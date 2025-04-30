# taskify-backend
Taskify-Backend Code changes
•  Backend: Node.js with Express and MongoDB (with Mongoose)
•  Frontend: React (using Create React App)
1. Backend (Node.js + Express + MongoDB)
a. Project Setup
mkdir taskify-backend && cd taskify-backend
npm init -y
npm install express mongoose cors body-parser dotenv
b. Folder Structure
arduino
CopyEdit
taskify-backend/
├── models/
│   └── Task.js
├── routes/
│   └── tasks.js
├── .env
├── server.js

2. Running the Backend
a. Navigate to the backend folder:
cd taskify-backend
b. Install dependencies:
npm install
c. Start MongoDB
If you're using local MongoDB:
mongod
d. Start the backend server:
node server.js

Backend Server up at http://localhost:5000/tasks
