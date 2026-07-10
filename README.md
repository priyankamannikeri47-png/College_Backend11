# College Management API


<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/1a499c9b-a271-480b-a73b-6cf9ff31dde2" />
<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/ef1d3862-20bc-44d0-b2cd-8068f474a0a8" />
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/0568cabf-6e92-44cd-b7b4-901e04b3a0ae" />
<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/5d86725d-2f0d-4791-8475-c692a3c2f7b0" />



A robust RESTful API built with **Node.js**, **Express**, and **Mongoose** for managing a college database system. This project includes secure user authentication using **JWT (JSON Web Tokens)** and full **CRUD (Create, Read, Update, Delete)** operations for managing student records.

---

## 🚀 Features

* **User Authentication**: Secure user registration and login endpoints utilizing `bcryptjs` for password hashing and `jsonwebtoken` for stateless authentication.
* **Student Management**: Complete CRUD operations for handling student profiles.
* **Database Integration**: Structured data management using MongoDB and Mongoose schemas (User, Course, Teacher, Student).
* **Environment Configuration**: Protected environment variables handled via `dotenv`.

---

## 🛠️ Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB, Mongoose ODM
* **Security**: bcryptjs, JSON Web Tokens (JWT)
* **Configuration**: dotenv

---

## 📋 Prerequisites

Before running this project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v14+ recommended)
* [MongoDB](https://www.mongodb.com/) (Running locally on `mongodb://127.0.0.1:27017`)

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash

git clone <repository-url>
cd <project-directory>

Install Dependencies 
npm install

Put environment variable by creating .env file
JWT_SECRET=your_super_secret_jwt_key_here

### Owner -
Priyanka M
