📘 EduDoc

EduDoc is a full-stack web application designed to manage, search, and organize educational documents efficiently. It provides secure user authentication, structured document management, and a responsive user interface tailored for academic use cases.

This project demonstrates real-world full-stack development practices, including authentication, REST APIs, protected routes, and a modern frontend architecture.

🚀 Features

🔐 User Authentication

Secure login & registration

Protected routes for authenticated users

📄 Document Management

Create, view, and manage educational documents

Structured backend models for users and documents

🔎 Search & Filtering

Search documents efficiently

Pagination and filtering support on the frontend

🧩 Modular Frontend Architecture

Reusable React components

Clean separation of concerns

⚙️ Production-style Backend

RESTful API using Express

MongoDB models for persistent storage

🛠️ Tech Stack
Frontend

React (Vite)

JavaScript (ES6+)

CSS

Axios

React Router

Backend

Node.js

Express.js

MongoDB

Mongoose

Tooling & Configuration

Vite

ESLint

Git & GitHub

📁 Project Structure
EduDoc/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── main.jsx
│   ├── index.html
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/NishanthRao01/EduDoc.git
cd EduDoc

2️⃣ Backend Setup
cd backend
npm install
npm start


Make sure MongoDB is running locally or update the database connection string.

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

🔐 Environment Variables

Create a .env file inside the backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

🧪 Usage

Register or log in as a user

Access protected routes

Browse, search, and manage documents

Navigate using pagination and filters

📌 Project Highlights

Clean Git history with proper .gitignore

Separation of frontend & backend concerns

Real-world authentication flow

Scalable folder structure

Suitable for internships & entry-level roles

🧠 Learning Outcomes

This project helped reinforce:

Full-stack application architecture

REST API design

Authentication & authorization

Component-based UI development

Git & GitHub best practices

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Open a Pull Request
