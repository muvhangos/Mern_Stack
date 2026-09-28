# MERN Stack — Greg Lim

## MongoDB • Express • React • Node.js

A practical learning journey through the **MERN Stack** based on the Greg Lim MERN Stack course, progressing from the fundamentals through **Chapter 12**.

This repository documents my hands-on development, exercises, backend APIs, MongoDB integration, Express routing, React development, and full-stack concepts learned throughout the course.

---

## 🚀 About This Project

This repository represents my progress learning modern full-stack JavaScript development using:

* **MongoDB** — NoSQL database
* **Express.js** — Backend web framework
* **React.js** — Frontend UI library
* **Node.js** — JavaScript runtime

The goal is to understand how the individual technologies work together to build complete, database-driven web applications.

---

# 📚 Course Progress

## Chapter 1 — Introduction to MERN

### Topics Covered

* Introduction to full-stack development
* Understanding the MERN stack
* Node.js fundamentals
* JavaScript development environment
* npm and packages
* Project structure
* Running JavaScript applications with Node.js

### Technologies

```text
Node.js
npm
JavaScript
```

---

# Chapter 2 — Hello World

## Project

`Chapter-2-Hello-World`

### Topics Covered

* Creating a Node.js project
* Installing Express
* Creating an Express server
* Serving static HTML files
* Understanding the `public` directory
* Express routes
* Starting a development server

### Example Server

```text
Browser
   ↓
Express
   ↓
Node.js
   ↓
HTML
```

### Local Development

```text
http://localhost:3000
```

---

# Chapter 3 — Node.js Fundamentals

### Topics Covered

* Node.js runtime
* Modules
* npm packages
* `package.json`
* Dependencies
* Running scripts
* Backend JavaScript

---

# Chapter 4 — Express

### Topics Covered

* Express.js
* Creating servers
* Routes
* HTTP requests
* HTTP responses
* Middleware
* JSON responses
* REST API concepts

Example:

```text
GET /
GET /api/test
GET /api/products
```

---

# Chapter 5 — REST APIs

### Topics Covered

* REST architecture
* API endpoints
* GET requests
* POST requests
* PUT requests
* DELETE requests
* Request parameters
* JSON data

### REST Structure

```text
GET       → Retrieve data
POST      → Create data
PUT       → Update data
DELETE    → Delete data
```

---

# Chapter 6 — MongoDB

## MongoDB Introduction

MongoDB is the database used throughout the backend portion of the MERN stack.

### Topics Covered

* MongoDB
* MongoDB Atlas
* MongoDB Compass
* Databases
* Collections
* Documents
* CRUD operations
* MongoDB queries

### MongoDB Structure

```text
Database
   ↓
Collection
   ↓
Documents
   ↓
Fields
```

---

# Chapter 7 — MongoDB Atlas

### Topics Covered

* Creating a MongoDB Atlas project
* Creating a cluster
* Database users
* Connection strings
* Connecting Node.js to MongoDB
* Environment variables
* `.env` configuration

Example:

```env
MONGODB_URI=your_mongodb_connection_string
```

> Never commit real passwords, API keys, or database credentials to GitHub.

---

# Chapter 8 — Node + Express Backend

## Project

`node-express-backend`

### Topics Covered

* Express backend
* MongoDB Atlas
* Node.js
* Express routes
* Database connection
* API testing
* Environment variables

### Backend Server

```text
http://localhost:3002
```

The chapter demonstrated how a Node/Express backend can communicate with a MongoDB Atlas database.

---

# Chapter 9 — Movie Database Backend

## Project

`node-express-backend`

Chapter 9 expanded the backend into a more structured application.

### Technologies

```text
Node.js
Express.js
MongoDB
MongoDB Atlas
dotenv
```

### Project Structure

```text
node-express-backend
│
├── controller
│
├── dao
│
├── routes
│
├── .env
│
├── package.json
│
├── server.js
│
└── README.md
```

### Backend Endpoints

The backend was tested with endpoints including:

```text
GET /
GET /api/test
GET /api/products
```

### Database

MongoDB Atlas was used for database storage.

---

# 🎬 Movie Reviews

The movie backend was extended to work with movie reviews.

### Review Operations

```text
POST   /review
PUT    /review
DELETE /review
```

The project introduced the separation of responsibilities between:

```text
Routes
   ↓
Controllers
   ↓
DAO
   ↓
MongoDB
```

---

# Chapter 10 — Leaving Movie Reviews

Chapter 10 continued the movie application and introduced the movie review functionality.

### Concepts

* Movie information
* Movie IDs
* Reviews
* MongoDB queries
* Data access objects
* Controllers
* REST API design
* Updating records
* Deleting records

### Architecture

```text
Client
  ↓
Express Route
  ↓
Controller
  ↓
DAO
  ↓
MongoDB Atlas
```

---

# Chapter 11 — React

The course then moves toward the frontend portion of the MERN stack.

## React Fundamentals

### Topics

* React
* Components
* JSX
* Props
* State
* Events
* Rendering
* Component-based development

React allows the frontend to communicate with backend APIs and display dynamic application data.

### React Architecture

```text
React Application
       ↓
Components
       ↓
API Requests
       ↓
Express Backend
       ↓
MongoDB
```

---

# Chapter 12 — Full MERN Application

Chapter 12 brings the different parts of the MERN stack together.

## MERN Architecture

```text
┌─────────────────────┐
│       React         │
│      Frontend       │
└──────────┬──────────┘
           │
           │ HTTP / REST API
           ↓
┌─────────────────────┐
│      Express        │
│       Server        │
└──────────┬──────────┘
           │
           ↓
┌─────────────────────┐
│       Node.js       │
│      Runtime        │
└──────────┬──────────┘
           │
           ↓
┌─────────────────────┐
│      MongoDB        │
│      Database       │
└─────────────────────┘
```

---

# 🛠️ Technologies Used

| Technology      | Purpose                 |
| --------------- | ----------------------- |
| JavaScript      | Programming language    |
| Node.js         | Backend runtime         |
| Express.js      | Backend framework       |
| MongoDB         | Database                |
| MongoDB Atlas   | Cloud database          |
| MongoDB Compass | Database management     |
| React           | Frontend                |
| npm             | Package management      |
| Git             | Version control         |
| GitHub          | Source-code hosting     |
| VS Code         | Development environment |

---

# 📂 Learning Structure

My MERN learning projects are organized by chapter:

```text
MERN Stack
│
├── chapter 1
│
├── chapter 2
│   └── Chapter-2-Hello-World
│
├── chapter 3
│
├── chapter 4
│
├── chapter 5
│
├── chapter 6
│
├── chapter 7
│
├── chapter 8
│   └── node-express-backend
│
├── chapter 9
│   └── node-express-backend
│
├── chapter 10
│
├── chapter 11
│
└── chapter 12
```

---

# 🧠 What I Learned

Through Chapters 1–12, I developed practical experience with:

### Backend Development

* Node.js
* Express.js
* REST APIs
* Routing
* Controllers
* Middleware
* HTTP requests
* JSON APIs

### Database Development

* MongoDB
* MongoDB Atlas
* MongoDB Compass
* Collections
* Documents
* CRUD
* MongoDB queries
* Database connections

### Frontend Development

* React
* Components
* JSX
* Props
* State
* API communication
* Frontend/backend integration

### Development Tools

* VS Code
* npm
* Git
* GitHub
* MongoDB Compass
* MongoDB Atlas
* PowerShell

---

# 🔐 Environment Variables

Sensitive configuration should be stored in `.env`.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=3000
```

The `.env` file should **not** be uploaded to GitHub.

Recommended `.gitignore`:

```gitignore
node_modules/
.env
.DS_Store
```

---

# ▶️ Running a Project Locally

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Move into the required chapter:

```powershell
cd "chapter 9\node-express-backend"
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

The application can then be accessed through the local server address displayed in the terminal.

---

# 🧪 API Testing

Backend endpoints can be tested using:

* Browser
* REST clients
* Postman
* VS Code REST tools

Example:

```text
GET /
GET /api/test
GET /api/products
```

---

# 🌱 Learning Progress

```text
JavaScript
    ↓
Node.js
    ↓
Express
    ↓
REST APIs
    ↓
MongoDB
    ↓
MongoDB Atlas
    ↓
Controllers
    ↓
DAO
    ↓
Movie APIs
    ↓
Reviews
    ↓
React
    ↓
MERN
```

---

# 🎯 Goal

The objective of this learning journey is to build a strong practical foundation in **full-stack web development** and apply the knowledge to real-world applications.

The MERN stack provides experience across the complete application lifecycle:

```text
Frontend
   +
Backend
   +
Database
   +
API
   +
Authentication
   +
Deployment
```

---

# 👨‍💻 Developer

**Samuel Muvhango**

Full Stack Web Developer | IT & Systems Engineer

### Technologies & Areas of Interest

* Full Stack Web Development
* Python
* JavaScript
* MERN
* Django
* React
* Node.js
* Express
* MongoDB
* REST APIs
* Cloud Technologies
* AI Tools
* IT Systems Engineering

---

# 📈 Next Steps

After completing the Greg Lim MERN Stack chapters, the next stage is to continue building real-world applications using the concepts learned.

Planned areas include:

* Full-stack applications
* Authentication
* Secure APIs
* Database design
* React interfaces
* API integration
* Cloud deployment
* GitHub projects
* Production-ready applications

---

## ⭐ Learning in Public

This repository documents my progress from learning the fundamentals of Node.js and Express through building database-driven applications with MongoDB and React.

**From the first "Hello World" server to full-stack MERN development.**

```text
LEARN → BUILD → TEST → DEBUG → DEPLOY → IMPROVE
```

---

## 📜 Course Reference

This repository is based on the **Greg Lim MERN Stack** learning material and is intended to document my personal learning and practical development progress.

© Samuel Muvhango
