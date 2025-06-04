# Bike Rental Application

A full-stack application for bike rentals, similar to Zoomcar. This application allows bike owners to list their bikes for rent and users to rent bikes for their travel needs.

## Features

- User Authentication (Renters and Hosts)
- Admin Dashboard for verification
- Bike Listing and Management
- Booking System
- Payment Integration
- Reviews and Ratings

## Tech Stack

- Frontend: React.js
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT

## Project Structure

```
bike-rental/
├── frontend/          # React frontend application
├── backend/           # Node.js backend server
└── README.md
```

## Setup Instructions

### Backend Setup
1. Navigate to the backend directory
2. Install dependencies: `npm install`
3. Create a .env file with required environment variables
4. Start the server: `npm start`

### Frontend Setup
1. Navigate to the frontend directory
2. Install dependencies: `npm install`
3. Start the development server: `npm start`

## Environment Variables

Create a .env file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
``` 