Task Management Application

This repository contains the Task Management Application built using the MERN stack (MongoDB, Express, React, Node.js). It includes task management features, and is styled using Material UI.

Features

Task Management:

Add tasks with title and description.

Edit and delete tasks.

Search tasks by title.

Responsive Design: Styled using Material UI for a professional look.

Setup Instructions

Prerequisites

Node.js (version 14 or higher)

MongoDB (local or Atlas)

Git

Clone the Repository

git clone <repository-url>
cd task-manager-app

Backend Setup

Navigate to the backend folder:

cd backend

Install dependencies:

npm install

Create a .env file in the backend folder and add the following:

PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/task-manager?retryWrites=true&w=majority
JWT_SECRET=your_jwt_secret

Replace <username> and <password> with your MongoDB credentials.

Start the backend server:

npm run dev

Frontend Setup

Navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the frontend application:

npm run dev

Open the application in your browser at http://localhost:5173.

Design Choices and Assumptions

Material UI: Chosen for its modern components and ease of customization, providing a professional appearance.

Database Schema: Simple schema with title, description, and timestamp fields for tasks.

Search and Pagination: Implemented to enhance usability when managing large task lists.

Additional Features

Search Bar: Case-insensitive search for tasks by title.

Pagination: Limits the number of tasks displayed per page for better performance.

Navbar: Contains navigation links for login, signup, and the task manager home page.

Links

Frontend Deployment: Frontend Application

Backend Deployment: Backend API

Contribution

Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!
