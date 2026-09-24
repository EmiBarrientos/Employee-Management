# Employee Management

A full-stack web application for managing employees, built with **React** on the frontend and **Node.js + Express** on the backend.

The application provides a simple interface for performing **CRUD operations** on employee records stored in a **MySQL** database.

## ✨ Features

* Create new employees
* View the employee list
* Edit employee information
* Delete employees
* Client-side data validation
* RESTful API for employee management
* MySQL database integration
* Error handling and HTTP response management
* Responsive user interface with Bootstrap

## 🛠️ Tech Stack

### Frontend

* React
* Axios
* Bootstrap
* SweetAlert2

### Backend

* Node.js
* Express
* MySQL

### Tools

* Git
* GitHub
* npm

## 🏗️ Project Structure

The project is divided into two main applications:

```text
Employee-Managment/
├── client/          # React frontend
├── server/          # Node.js + Express backend
├── .gitignore
├── package-lock.json
└── README.md
```

### Frontend

The React application provides the user interface for managing employees and communicates with the backend through HTTP requests using Axios.

### Backend

The Node.js and Express application exposes RESTful endpoints for employee CRUD operations and handles communication with the MySQL database.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* [Node.js](https://nodejs.org/)
* npm
* MySQL
* Git

### 1. Clone the repository

```bash
git clone https://github.com/EmiBarrientos/Employee-Managment.git
cd Employee-Managment
```

### 2. Set up the database

Create a MySQL database named:

```sql
CREATE DATABASE gestion_empleados;
```

Then import the database schema located at:

```text
server/database.sql
```

Update the database connection configuration in:

```text
server/db.js
```

with your local MySQL credentials.

### 3. Start the backend

Open a terminal and navigate to the server directory:

```bash
cd server
npm install
npm start
```

The backend will run on:

```text
http://localhost:3001
```

### 4. Start the frontend

Open another terminal and navigate to the client directory:

```bash
cd client
npm install
npm start
```

The frontend will run on:

```text
http://localhost:3000
```

## 🔌 API

The backend provides RESTful routes for managing employee records.

The API handles the main CRUD operations:

| Operation | Description                 |
| --------- | --------------------------- |
| Create    | Add a new employee          |
| Read      | Retrieve employee records   |
| Update    | Modify an existing employee |
| Delete    | Remove an employee          |

## 📸 Screenshots

### Home

*Add application screenshot here.*

### Employee Form

*Add employee form screenshot here.*

## 🎯 Project Purpose

This project was developed as a **full-stack learning project** to practice building a web application from frontend to backend and database integration.

It provided hands-on experience with:

* Building REST APIs with Node.js and Express
* Developing user interfaces with React
* Connecting a backend application to MySQL
* Consuming APIs from a React frontend
* Implementing CRUD operations
* Organizing a full-stack application into separate frontend and backend layers

## 👨‍💻 Author

**Emiliano Barrientos**

* GitHub: [@EmiBarrientos](https://github.com/EmiBarrientos)
* LinkedIn: [Emiliano Barrientos](https://linkedin.com/in/emiliano-barrientos)
