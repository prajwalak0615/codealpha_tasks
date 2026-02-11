# 📱 Finstragram - A Social Media Platform

A full-stack **Social Media Web Application** built using **HTML, CSS, JavaScript** for the frontend and **Node.js with Express.js** for the backend.  
This project is developed as part of the **CodeAlpha Full Stack Development Internship (Task-2)**.

It allows users to create profiles, share posts, like and comment on posts, and interact with other users in real time.

---

## 📌 Project Overview

This application provides a mini social media platform where users can:
- Register and log in
- Create posts
- Like and comment on posts
- Follow other users
- View user profiles

All data is stored securely in a database and managed through a backend server.

---

## 🚀 Features

### 👤 User Management
- User Registration
- User Login
- User Profiles
- Follow / Unfollow users

### 📝 Posts & Interactions
- Create posts
- View posts from users
- Like posts
- Comment on posts
- Delete own posts and comments

### 🔔 Notifications & Emails
- Email notifications using mailers
- Background jobs using workers

---

## 🖥️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- EJS Templates

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Additional Tools
- Multer (for uploads)
- Nodemailer (for email)
- Workers for background jobs
- Gulp for asset management

---

## 📂 Project Structure

```
CODEALPHA_SOCIAL_MEDIA_PLATFORM
├── assets          → Static assets
├── config          → Database & environment configuration
├── controllers     → Request handling logic
├── mailers         → Email services
├── models          → MongoDB schemas (users, posts, comments, likes)
├── production_logs → Server logs
├── public          → Frontend files
├── routes          → Express routes
├── uploads         → Uploaded files
├── views           → UI templates
├── workers         → Background tasks
│
├── .eslintrc.js
├── gulpfile.js
├── index.js        → Main server file
├── package.json
└── readme.md
```

---

## 🗄️ Database

The application uses **MongoDB** to store:

- Users  
- Posts  
- Comments  
- Likes  
- Followers  

Mongoose is used to define schemas and interact with the database.

---

## 🔐 Authentication & Security

- User login and signup  
- Password encryption  
- Session management  
- Protected routes for authenticated users  

---

## 🎯 Internship Task Fulfillment

This project fulfills **Task-2: Social Media Platform** of CodeAlpha:

✔ User profiles  
✔ Posts & comments  
✔ Like system  
✔ Follow system  
✔ Frontend using HTML, CSS, JavaScript  
✔ Backend using Node.js (Express)  
✔ Database for users, posts, comments, followers  

---

## 🧑‍💻 Developer

**Name:** Nagaraj Naik  
**Internship:** CodeAlpha Full Stack Development  
**Task:** Social Media Platform  

---

## 📜 License

This project is created for educational and internship purposes.
