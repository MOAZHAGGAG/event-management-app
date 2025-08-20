# Event Management App

This is a simple event management system built with Python, FastAPI, Streamlit, and PostgreSQL. It allows you to create, view, update, and delete events, as well as manage event categories.

## Features
- Add, view, update, and delete events
- Manage event categories (add new categories, select from existing)
- Simple web interface using Streamlit
- REST API backend using FastAPI
- PostgreSQL database for persistent storage
- Dockerized for easy setup and deployment

## Getting Started

### Prerequisites
- Docker and Docker Compose installed
- Python 3.11+ (for local development)

### Setup
1. Clone the repository:
   ```sh
git clone https://github.com/MOAZHAGGAG/event-management-app.git
cd event-management-app
```
2. Build and start the app using Docker Compose:
   ```sh
docker-compose up --build
```
3. Access the frontend:
   - Open your browser and go to `http://localhost:8501`
4. Access the backend API:
   - Go to `http://localhost:8000/docs` for API documentation

### Database Access
- The PostgreSQL database is exposed on port 5432 (or 5444 for locals such as DBeaver)
- Default credentials:
  - Database: `event_management`
  - User: `eventuser`
  - Password: `eventpass123`

## Project Structure
```
backend/        # FastAPI backend
frontend/       # Streamlit frontend
init.sql        # Database initialization script
Dockerfile.*    # Docker build files
requirements*.txt # Python dependencies
```

## How to Contribute
- Fork the repo and create a pull request
- For questions or issues, open an issue on GitHub

---
Made by Moaz Haggag
