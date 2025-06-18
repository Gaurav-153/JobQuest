# 🧑‍💼 MERN Stack Job Portal Web App

A full-featured job portal web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This platform connects job seekers with employers, allowing users to post and apply for jobs, manage profiles, and more.

---

## 🚀 Features

### 👤 Job Seeker
- Register and log in
- Create and update profile
- Browse and search jobs
- Apply to jobs
- Track application status

### 🏢 Employer
- Register and log in
- Post new job listings
- Manage job postings
- View and manage applications

### 🔐 Authentication
- JWT-based authentication
- Role-based access control (Job Seeker / Employer)
- Secure password hashing (bcrypt)

### 💻 Tech Stack
- **Frontend:** React.js, Redux Toolkit, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT, bcrypt
- **Styling:** Tailwind CSS / Bootstrap (customize accordingly)
- **State Management:** Redux / Context API

---

## 🛠️ Installation & Setup

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)

### 1. Clone the Repository

```bash
git clone https://github.com/Gaurav-153/mern-job-portal.git
cd mern-job-portal
```
### 2. Backend Setup 
```bash
cd backend
npm install
cp .env.example .env  # Update MongoDB URI, JWT secret, etc.
node index.js
```
### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
### 4. Environment Variables
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

