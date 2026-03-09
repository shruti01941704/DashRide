
# DashRide – Ride Booking Platform

DashRide is a full-stack ride booking web application designed to connect riders with drivers in real time. It provides a seamless platform for passengers to book rides, drivers to accept requests, and the system to manage trips efficiently. The platform focuses on safety, real-time communication, and intelligent ride allocation similar to modern ride-hailing services.

---

## 📑 Table of Contents
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
  - [Available Scripts](#available-scripts)
- [Contributing](#contributing)


---

# 🚀 Key Features

### User Authentication
Secure login and registration for riders and captains (drivers) with protected routes and role-based access control.

### Real-Time Ride Booking
Passengers can instantly request rides by selecting pickup and drop locations.

### Hybrid Bidding Ride Allocation
Instead of automatic assignment, drivers can accept or bid on ride requests, creating a dynamic fare and fair driver distribution system.

### Real-Time Communication
Uses WebSockets to enable instant updates between riders and drivers for ride requests, acceptance, and ride status.

### Live Ride Tracking
Track ride status in real time including:
- Ride requested
- Driver assigned
- Ride in progress
- Ride completed

### Emergency Safety Feature
Includes an emergency button that allows riders to report urgent situations. The system sends the selected emergency type along with live location to the backend for immediate action.

### Women Safety Ride Mode
If a female passenger books a ride, the system prioritizes matching with female drivers. If none are available, male drivers with the highest safety ratings are assigned.

### Driver Safety Feedback
Passengers can provide safety feedback after rides. Drivers with better safety scores receive higher priority for ride assignments.

### Responsive Design
Modern and mobile-friendly UI that works smoothly across desktops, tablets, and mobile devices.

---

# 🛠️ Technology Stack

## Frontend
React: Dynamic user interface for riders and drivers  
React Router: Client-side routing for navigation  
Tailwind CSS: Utility-first CSS framework for responsive UI  
Axios: API communication between frontend and backend  

## Backend
Node.js: Server-side runtime environment  
Express.js: Backend framework for creating REST APIs  

## Real-Time Communication
WebSockets: Enables instant communication between riders and drivers

## Database
MongoDB: NoSQL database for storing users, rides, and driver data  
Mongoose: Object data modeling for MongoDB

## Authentication
JWT (JSON Web Token): Secure login authentication and protected routes

---

# 📁 Project Structure

```
DashRide
│
├── client
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   └── App.js
│   │
│   └── package.json
│
├── server
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   └── server.js
│
├── .env
└── README.md
```

---

# 🏁 Getting Started

Follow these steps to run DashRide locally.

---

## Prerequisites

Ensure the following are installed:

Node.js (v16 or higher)  
MongoDB (local installation or MongoDB Atlas)  
npm or yarn  
A modern web browser  

---

# ⚙️ Installation

### Clone the Repository

```
git clone https://github.com/your-username/dashride.git
cd dashride
```

### Install Dependencies

Install backend dependencies:

```
cd server
npm install
```

Install frontend dependencies:

```
cd ../client
npm install
```

---

# ▶️ Running the Application

Start the backend server:

```
cd server
npm run dev
```

Start the frontend client:

```
cd client
npm start
```

The application should now run locally at:

```
http://localhost:3000
```

---

# 📸 Screenshots

![Landing Page](https://github.com/user-attachments/assets/0a3c8543-5582-4c4f-b961-ff290f42705a)

![Ride Booking](https://github.com/user-attachments/assets/400abc60-5f1d-4745-a371-9be00eae3da3)

![Driver Dashboard](https://github.com/user-attachments/assets/9494d8c8-70c7-42ca-97d9-b158567d8ebf)

![Ride Request](https://github.com/user-attachments/assets/345d8765-384c-45fc-921d-cdc48e0e8b5c)

![Ride Confirmation](https://github.com/user-attachments/assets/61e4e3c8-fd4b-4a93-b14d-bffdf1c86c8a)

![Ride Tracking](https://github.com/user-attachments/assets/35e1f940-53e5-4ad3-94c5-24e3891b676d)

![Trip Progress](https://github.com/user-attachments/assets/b8024cbb-8dc7-4c87-9ae9-d538f02fb18b)

![Completed Ride](https://github.com/user-attachments/assets/c2dfb5ad-13d1-49c3-9d65-c7a46f60c5b8)

---

# 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

⭐ If you like this project, consider giving it a star on GitHub!
