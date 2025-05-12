# Bike Service Booking Application

A full-stack application for booking bike service appointments.

## Features
- User registration and authentication
- Service booking management
- Service history tracking
- Admin dashboard
- Real-time appointment status updates

## Tech Stack
- Frontend: React.js with Material-UI
- Backend: Java Spring Boot
- Database: MySQL
- Authentication: JWT

## Project Structure
```
bike-service-app/
├── frontend/           # React frontend application
├── backend/           # Java Spring Boot backend
└── docs/             # Documentation
```

## Setup Instructions

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Build the project:
   ```bash
   ./mvnw clean install
   ```
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

## Environment Variables
Create a `.env` file in the frontend directory with:
```
REACT_APP_API_URL=http://localhost:8080/api
```

## API Documentation
API documentation is available at `/api-docs` when running the backend server.

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 