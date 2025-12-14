# 🍬 Sweet Shop Management System

A full-stack **Sweet Shop Management System** built using the **MERN Stack** (MongoDB, Express, React, Node.js) and developed by strictly following **Test-Driven Development (TDD)** principles.

This project demonstrates a well-structured RESTful API, secure JWT-based authentication, and a responsive frontend with role-based Admin management features.

---

## 🚀 Features

### Core Functionality
- **User Authentication:** Secure user registration and login using **JWT (JSON Web Tokens)**.
- **Product Management:** View all available sweets with real-time stock information.
- **Search & Filter:** Quickly search sweets by name or category.
- **Inventory Management:** Purchase logic that automatically updates stock quantities.
- **Security:** Protected routes to ensure only authenticated users can access shop features.

### 👑 Admin Features (Protected)
- **Role-Based Access Control:** Admin-only permissions.
- **Admin Dashboard:** Dedicated interface for inventory management.
- **CRUD Operations:** Add, update, and delete sweets.
- **Restocking:** Simple restock functionality to replenish inventory.

---

## 🛠️ Tech Stack

### Backend
- **Node.js & Express** – REST API development  
- **MongoDB & Mongoose** – Database and schema modeling  
- **JWT & Bcrypt** – Authentication and password security  
- **Jest & Supertest** – Test-Driven Development and API testing  

### Frontend
- **React (Vite)** – Fast and modern frontend framework  
- **Tailwind CSS** – Responsive UI styling  
- **Axios** – API communication  
- **React Context API** – Global authentication state management  

---

## ⚙️ Installation & Setup

Follow the steps below to run the project locally.

### 1. Clone the Repository
```bash
git clone <your-repo-link-here>
cd sweet-shop-management
```

---

### 2. Backend Setup

Navigate to the backend folder and install dependencies:

```bash
cd backend
npm install
```

#### Configure Environment Variables
Create a `.env` file inside the `backend/` directory and add:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/sweetshop
JWT_SECRET=your_super_secret_key_123
```

#### Seed the Database (Important)
This command clears the database and creates an initial Admin user along with sample sweets:

```bash
npm run data:import
```

#### Start the Backend Server
```bash
npm run dev
```

Backend will run on:  
**http://localhost:5000**

---

### 3. Frontend Setup

Open a new terminal and navigate to the frontend folder:

```bash
cd ../my-app
npm install
```

Start the frontend application:

```bash
npm run dev
```

Frontend will run on:  
**http://localhost:5173**

---

## 🔐 Test Credentials

Use the following pre-configured accounts for testing:

| Role  | Email | Password | Access Level |
|------|------|---------|--------------|
| **Admin** | `admin@sweetshop.com` | `password123` | Full Access (Add / Edit / Delete Sweets) |
| **User**  | `user@sweetshop.com`  | `password123` | Customer Access (View, Search, Buy) |

---

## 🧪 Running Tests (TDD)

This project follows **Test-Driven Development**.  
To run backend tests:

```bash
cd backend
npm test
```

### Test Coverage Includes
- ✅ Authentication (Register / Login)
- ✅ Sweets CRUD Operations
- ✅ Inventory Purchase & Restock Logic
- ✅ Protected Routes & Authorization

---

## 🤖 AI Usage Disclosure

*As required, below is a transparency report of AI assistance used during development.*

### AI Tools Used
- **Gemini (Google)** – Used as a development assistant and reasoning partner.

### How AI Was Used
1. **Project Setup:** Generated initial boilerplate for Express and Vite.
2. **TDD Workflow:** Helped design failing test cases before implementation.
3. **Debugging:** Assisted in resolving MongoDB and environment configuration issues.
4. **Refactoring:** Suggested improvements for Admin authorization middleware.

### Reflection
AI tools significantly accelerated the setup phase and helped maintain strict TDD discipline, allowing greater focus on business logic and code quality.

---

## 📸 Screenshots

*(Add screenshots to the repository and link them below)*

| Dashboard | Admin Panel |
|:--------:|:-----------:|
|          |             |

---

## 👤 Author

**Amit Tiwari**  
*(Project forked and customized for personal submission and learning purposes)*

