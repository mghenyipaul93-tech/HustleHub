# Hustle Hub

## Overview

Hustle Hub is a full-stack mentorship and learning platform designed to connect learners with developers, mentors, and educational resources.

The platform allows users to:
- discover GitHub developers
- search programming books
- save favorites
- become mentors
- review mentors
- manage mentor profiles

---

# Live Project

Frontend:

https://hustlehhub.netlify.app

Backend API:

https://hustlehub-backend-qgtq.onrender.com

Swagger Documentation:

https://hustlehub-backend-qgtq.onrender.com/apidocs

---

# Features

## Authentication

Users can:
- sign up
- login
- upload profile images
- manage profiles

JWT authentication is used for protected routes.

---

## Mentor Discovery

Users can:
- search GitHub developers
- view developer profiles
- save mentors to favorites

GitHub API is used to fetch developer data.

---

## Books Discovery

Users can:
- search programming books
- open book pages
- save books to favorites

Open Library API is used for book data.

---

## Mentor Profiles

Users can:
- become mentors
- create mentor profiles
- upload mentor images
- set skills and availability

Mentor profiles appear publicly on the Hustle Mentors page.

---

## Reviews System

Users can:
- leave mentor reviews
- rate mentors from 1 to 5 stars

Mentors cannot review themselves.

---

## Admin Dashboard

Admins can:
- view users
- view mentor profiles
- view reviews
- delete reviews
- delete mentor profiles

---

# Frontend Technologies

- React
- React Router
- Vite
- CSS
- Fetch API

---

# Backend Technologies

- Flask
- PostgreSQL
- SQLAlchemy
- JWT Authentication
- Cloudinary
- SendGrid
- Swagger

---

# APIs Used

## GitHub API

Used for:
- developer search
- mentor discovery
- GitHub profile information

## Open Library API

Used for:
- programming books
- book search
- book covers

---

# Project Structure

```bash
HustleHub/
│
├── hustle-hub-frontend/
├── HustleHub_backend/
└── README.md
```

---

# Frontend Installation

## Navigate to Frontend

```bash
cd hustle-hub-frontend
```

## Install Dependencies

```bash
npm install
```

## Run Frontend

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

# Backend Installation

## Navigate to Backend

```bash
cd HustleHub_backend
```

## Install Dependencies

```bash
pipenv install
```

## Activate Environment

```bash
pipenv shell
```

## Run Backend

```bash
python run.py
```

Backend runs on:

```text
http://127.0.0.1:5000
```

---

# Environment Variables

Create a `.env` file in the backend.

```env
SECRET_KEY=your_secret_key
JWT_SECRET_KEY=your_jwt_secret
DATABASE_URL=your_database_url
FRONTEND_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

SENDGRID_API_KEY=your_sendgrid_api_key
FROM_EMAIL=your_email
```

---

# Security Features

- JWT authentication
- Protected routes
- Role-based access control
- Environment variable protection
- Restricted CORS configuration

---

# Testing

The project was manually tested for:
- authentication
- favorites system
- mentor profile creation
- reviews
- admin dashboard
- protected routes
- API documentation
- frontend routing

---

# Deployment

## Frontend

Frontend deployed using:
- Netlify

## Backend

Backend deployed using:
- Render

---

# Future Improvements

- Real-time chat
- Mentor booking system
- Notifications
- Video calls
- Payment integration

---

# Contributors

- Hashim Hassan
- Yasmine Mohamed
- Kaltun Dubow
- Paul Mwasaru

---

# License

This project is for educational and portfolio purposes.

