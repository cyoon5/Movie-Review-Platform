# Movie Review Platform

## Overview
This project was developed as part of a university course on full-stack development, where I gained hands-on experience building a multiuser system with real-world API integration, testing, and deployment practices.


This is a full-stack, multiuser movie review system built with **FastAPI** (backend) and **Next.js** (frontend).  
It allows multiple users to register, review, and interact with movies, while admins can moderate content and manage users.  

The system **integrates the TMDb API** to fetch movie data, providing real-world, up-to-date movie information. Data is stored using **JSON files**, avoiding traditional databases.

---

## Key Features

- **Multiuser System**
  - User roles: **Admin** and **Regular User**
  - Role-specific dashboards and functionality
  - Admins can moderate reviews, manage users, and apply penalties

- **Movie Review Functionality**
  - Users can add, edit, and delete reviews
  - Reviews are displayed with movie information fetched from the TMDb API
  - Search, sort, and filter movies and reviews

- **Data Management**
  - JSON/CSV storage for reviews, users, and penalties
  - Supports CRUD operations for all entities

- **Frontend**
  - Built with **Next.js**
  - Clear navigation for users to browse movies, write reviews, and view dashboards
  - Admin dashboard for moderation and management

- **Backend**
  - Built with **FastAPI**
  - Exposes RESTful API consumed by the frontend
  - Handles authentication, role-based access, and business logic

- **Testing & Quality**
  - Backend tested using **Pytest**
  - Continuous Integration via **GitHub Actions**
  - Containerized with **Docker** for easy deployment

---

## Tech Stack

- **Backend:** FastAPI, Python, Pytest
- **Frontend:** Next.js, React
- **Data Storage:** JSON files
- **External API:** TMDb API
- **DevOps:** GitHub Actions, Docker

1. Clone the repository:  
   ```bash
   git clone <your-repo-link>
   cd <repo-folder>
