# Appointment-Booking-System

A full-stack application for managing doctor appointments. This project includes user, doctor, and appointment management with authentication and authorization, built using MongoDB, Express.js, React.js, and Node.js.

## Features

  - User authentication and authorization (JWT)
  - Doctor profile management
  - Appointment booking and status updates
  - Real-time notifications for users
  - Admin dashboard for managing doctors and appointments
  - Frontend built with React.js

## Technologies

  - Frontend: React.js, Redux
  - Backend: Node.js, Express.js, MongoDB (Mongoose)
  - Authentication: JWT (JSON Web Tokens)
  - State Management: Redux
  - Environment Variables: dotenv

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ChamodiLiyanage/Appointment-Booking-System.git
    ```
2. Navigate to the project directory:

    ```bash
    cd Appointment-Booking-System
    ```
3. Install server dependencies:

    ```bash
    npm install
    ```
4. Install client dependencies:

    ```bash
    cd client
    npm install
    ```

5. Set up environment variables in backend/.env:
   
    ```bash
    MONGO_URI=your-mongodb-uri
    JWT_SECRET=your-secret-key
    PORT=5001
    ```

## API Endpoints
User Routes

  - POST /api/user/register – Register a new user
  - POST /api/user/login – User login

Doctor Routes

  - POST /api/doctor/get-doctor-info-by-user-id – Get doctor info by user ID
  - POST /api/doctor/update-doctor-profile – Update doctor profile
  - GET /api/doctor/get-appointments-by-doctor-id – Get doctor’s appointments

Appointment Routes

  - POST /api/appointments/book – Book a new appointment
  - POST /api/appointments/change-appointment-status – Change appointment status

## Running the Application

  - Start the server:

    ```bash
    nodemon server
    ```
  - Start the client:

    ```bash
    cd client
    npm start
    ```

 
