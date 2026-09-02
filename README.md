# 🎬 Movie Ticket Booking System

A modern full-stack web application for discovering movies, exploring showtimes, selecting seats, and managing movie ticket bookings through an intuitive and responsive interface.

## 📌 Project Overview

The **Movie Ticket Booking System** is designed to simplify the movie booking experience by bringing movie discovery, showtime selection, seat selection, booking management, and user authentication into a single platform.

The application follows a **client–server architecture**, with a responsive frontend communicating with a RESTful backend and MongoDB database.

## ✨ Key Features

* 🎥 **Movie Discovery** – Browse and explore available movies.
* 🔐 **User Authentication** – Secure registration and login functionality.
* 🎭 **Movie Details** – View movie information, descriptions, and available shows.
* 🕐 **Showtime Selection** – Select suitable theatre showtimes.
* 💺 **Interactive Seat Selection** – Choose available seats before booking.
* 🎟️ **Ticket Booking** – Create and manage movie bookings.
* 📋 **Booking Management** – View booking details and booking history.
* 🔔 **Notifications** – Support for booking and reminder notifications.
* 🛡️ **Backend Validation & Security** – API validation, authentication, and request protection.
* 📱 **Responsive UI** – Designed to work across desktop and mobile screen sizes.

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      User           │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  React + Vite       │
                    │     Frontend        │
                    └──────────┬──────────┘
                               │
                         REST API
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Node.js + Express   │
                    │      Backend        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MongoDB        │
                    │      Database       │
                    └─────────────────────┘
```

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js
* REST APIs
* JWT Authentication
* Mongoose

### Database

* MongoDB

### Development Tools

* Git & GitHub
* Visual Studio Code
* npm

## 📂 Project Structure

```text
movie-ticket-fullstack-project/
│
├── movie-ticket-frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── movie-ticket-backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── server.js
│   └── package.json
│
├── screenshots/
│   ├── home.png
│   ├── login.png
│   ├── movies.png
│   ├── movie-details.png
│   ├── seat-selection.png
│   └── booking.png
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js 18+
* npm
* MongoDB
* Git

### 1. Clone the Repository

```bash
https://github.com/Navanitha23-aids/Movie-Ticket-Booking-Management-.git
cd movie-ticket-fullstack-project
```

### 2. Setup Backend

```bash
cd movie-ticket-backend
npm install
```

Create a `.env` file and configure your MongoDB connection and application settings.

Then start the backend:

```bash
npm start
```

The backend will run on the configured server port.

### 3. Setup Frontend

Open a new terminal:

```bash
cd movie-ticket-frontend
npm install
npm run dev
```

Open the local development URL shown in the terminal, usually:

```text
http://localhost:5173
```

## 📸 Application Screenshots

### 🏠 Home Page

![Home Page](screenshots/home.png)

### 🔐 Login Page

![Login Page](screenshots/login.png)

### 🎬 Movies Page

![Movies Page](screenshots/movies.png)

### 🎭 Movie Details

![Movie Details](screenshots/movie-details.png)

### 💺 Seat Selection

![Seat Selection](screenshots/seat-selection.png)

### 🎟️ Booking

![Booking](screenshots/booking.png)

## 🔄 Booking Workflow

```text
Login / Register
       ↓
Browse Movies
       ↓
Select Movie
       ↓
Choose Theatre & Showtime
       ↓
Select Seats
       ↓
Confirm Booking
       ↓
Booking Confirmation
```

## 🔒 Security Considerations

* JWT-based authentication
* Environment variables for sensitive configuration
* Server-side request validation
* Protected API routes
* Rate limiting support
* CORS configuration
* Secure database connectivity

> **Note:** Never commit `.env` files, passwords, API keys, database credentials, or other sensitive information to GitHub.

## 🎯 Project Objectives

The main objectives of this project are to:

* Provide a simple and efficient movie booking experience.
* Reduce the complexity of manual ticket booking.
* Provide real-time seat availability through the application.
* Build a scalable full-stack architecture.
* Demonstrate integration between frontend, backend, and database technologies.

## 🔮 Future Enhancements

* 💳 Online payment gateway integration
* 📧 Email ticket confirmation
* 📱 SMS and push notifications
* ⭐ Movie ratings and reviews
* 🤖 AI-based movie recommendations
* 🎫 QR-code based digital tickets
* 📊 Admin analytics dashboard
* ☁️ Cloud deployment and scalable infrastructure

## 👩‍💻 Development

This project was developed as a full-stack web application to demonstrate practical implementation of modern web development concepts including frontend development, REST API design, authentication, database management, and responsive UI design.

## 📄 License

This project is developed for educational and project demonstration purposes.
