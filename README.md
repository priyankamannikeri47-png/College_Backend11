# College Management API


<img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/5e6174d3-2334-49d4-ad23-33b562d44ef3" />
<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/bb22deb4-a762-4065-b690-eb3249fb7250" />
<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/4ca2d6a8-39ed-4fed-b3e7-acb64b572326" />

//github.com/user-attachments/assets/5d86725d-2f0d-4791-8475-c692a3c2f7b0" />



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
