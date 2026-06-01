# 🎓 Student Management System API

A RESTful CRUD API built using Node.js, Express.js, MongoDB, and Mongoose for managing student records efficiently. This project demonstrates backend development concepts including database connectivity, schema modeling, API development, and CRUD operations using MongoDB.

## 🚀 Features

- Create new student records
- Retrieve all student records from MongoDB
- Update existing student information
- Delete student records
- RESTful API architecture
- MongoDB integration using Mongoose ODM
- JSON-based request and response handling
- Scalable backend structure

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JavaScript
- Postman

## 📂 Project Structure

```bash
mongoose-crud/
│
├── server.js          # Express server setup and API routes
├── Student.js         # Mongoose schema and model
├── package.json       # Project dependencies and scripts
└── README.md
```

## 📌 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /students | Create a new student |
| GET | /students | Retrieve all students |
| PUT | /students/:id | Update student details |
| DELETE | /students/:id | Delete a student |

## 📄 Sample Student Data

```json
{
  "name": "Sai Bhargavi",
  "course": "Computer Science",
  "age": 21
}
```

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Building RESTful APIs with Express.js
- Connecting Node.js applications with MongoDB
- Creating and managing Mongoose schemas
- Implementing CRUD operations
- Testing APIs using Postman
- Understanding backend application architecture

## 🔥 Key Highlights

- Complete CRUD functionality
- MongoDB database integration
- Mongoose ODM implementation
- Clean and maintainable code structure
- Beginner-friendly backend project
- Foundation for full-stack MERN development
