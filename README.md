# CineReview: Full-Stack Movie Review Application

A full-stack web application designed for movie enthusiasts to discover films, write detailed reviews, rate movies, and engage with a community of film lovers. 

Live Demo: https://cinereview-demo.com  
Frontend Repo: https://github.com/your-username/cinereview-frontend  
Backend Repo: https://github.com/your-username/cinereview-backend  

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Database Design](#database-design)
- [API Endpoints](#api-endpoints)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Deployment](#deployment)
- [Future Improvements](#future-improvements)
- [Credits](#credits)
- [License](#license)

---

## Overview

### Motivation
Built out of a passion for cinema, this project serves as a centralized platform where users can bypass cluttered database sites and enjoy a clean, fast, and interactive space to log their movie thoughts, ratings, and recommendations.

### Objective
To solve the problem of fragmented movie tracking and superficial reviews by providing authenticated users with a structured way to create, read, update, and delete rich reviews paired with star ratings and genre filters.

### Learning Outcomes
- Built full authentication system with JWT
- Designed RESTful API endpoints for movies and reviews
- Implemented complete CRUD operations for user-generated content
- Connected a React frontend to a Node/Express backend API
- Deployed a full-stack web application

---

## Features

- **User Authentication:** Secure registration, login, and logout functionality with password hashing and JWT tokens.
- **Role-based Access Control:** Standard users can manage their own reviews, while administrators can moderate content.
- **Full CRUD Functionality:** Create, read, update, and delete movie reviews seamlessly.
- **Dashboard with Analytics:** View personal review stats, favorite genres, and average ratings given.
- **Fully Responsive Design:** Optimized for mobile devices, tablets, and desktop screens.
- **Search and Filter Functionality:** Filter movies by genre, release year, or search by title instantly.

---

## Tech Stack

### Frontend
- React
- HTML5
- Tailwind CSS
- Axios

### Backend
- Node.js + Express
- REST API
- JWT Authentication
- bcryptjs & Middleware validation

### Database
- MongoDB
- Mongoose ODM

### Tools
- Git & GitHub
- VS Code
- Postman

---

## Architecture

Client (Frontend - React)  
↓  
Server (REST API - Node/Express)  
↓  
Database (MongoDB)  

### Folder Structure

```text
client/
server/
  ├── controllers/
  │         └── reviewController.js
  ├── routes/
  │         └── reviewRoutes.js
  ├── models/
  │         └── Review.js
  ├── middleware/
  │         └── authMiddleware.js
  └── config/
            └── db.js
