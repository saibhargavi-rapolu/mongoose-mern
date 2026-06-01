🎓 Student Management System API

A RESTful CRUD API built using Node.js, Express.js, MongoDB, and Mongoose for managing student records. This project demonstrates database connectivity, schema modeling, and complete CRUD operations through a clean and scalable backend architecture.

🚀 Features
➕ Add new student records
📋 Retrieve all students from MongoDB
✏️ Update student information
🗑️ Delete student records
🔗 MongoDB integration using Mongoose
🌐 RESTful API endpoints
⚡ Express.js backend server
🔄 JSON-based data exchange
🛠️ Tech Stack
Backend: Node.js, Express.js
Database: MongoDB
ODM: Mongoose
API Testing: Postman
Development Tools: Nodemon
📂 Project Structure
mongoose-crud/
│
├── server.js          # Express server and API routes
├── Student.js         # Mongoose schema/model
├── package.json       # Project dependencies
└── README.md
📌 API Endpoints
Method	Endpoint	Description
POST	/students	Create a new student
GET	/students	Fetch all students
PUT	/students/:id	Update student details
DELETE	/students/:id	Delete a student
Sample Student Document
{
  "name": "Sai Bhargavi",
  "course": "Computer Science",
  "age": 21
}
🎯 Learning Outcomes

This project demonstrates:

REST API development
MongoDB database operations
Mongoose schema creation
CRUD implementation
Backend application architecture
API testing and debugging
💡 Key Highlights
Complete CRUD functionality
Real-time database interaction
Clean and beginner-friendly code structure
Industry-standard REST API design
Practical implementation of Mongoose ODM
