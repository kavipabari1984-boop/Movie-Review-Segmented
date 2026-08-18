# CineReview: Full-Stack Movie Review Application

A full-stack web application designed for movie enthusiasts to discover films, write detailed reviews, rate movies, and engage with a community of film lovers. 

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

### Core Language

Python 3

### Machine Learning & Data Science Libraries

scikit-learn 1.4.2
pandas
numpy
matplotlib
joblib

### Specific ML Components (from scikit-learn)

OrdinalEncoder
ColumnTransformer
SelectPercentile

### Web Framework

Streamlit

### Development Environment

Jupyter Notebook
venv (virtual environment)

### Storage & Infrastructure

Azurite
Queue Storage

### Data

CSV files

---

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
