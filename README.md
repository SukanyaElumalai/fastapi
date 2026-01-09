# Fastapi
FastAPI Project
This project aims to perform CRUD(Create, Read, Update, Delete) operations to update Inventory products.
🚀 Features
CRUD Operations: Performs managing products.

CORS Enabled: Configured for local development with frontend frameworks (default: localhost:3000).

Dependency Injection: Uses FastAPI Depends for database session management.

🛠️ Tech Stack
Framework: FastAPI

ORM: SQLAlchemy

Pydantic: For data validation and serialization.

Database: PostgreSQL

📥 Installation & Setup

Prerequisties:
IDE : IntelliJ
Python Interpreter
PgAdmin to view database changes

Clone the repository:
git clone fastapi
cd fastapi

.\myenv\Scripts\Activate.ps1
This creates your virtual environment to run the application

pip install fastapi uvicorn sqlalchemy pydantic

uvicorn main:app --reload

To run frontend:
cd frontend
npm start

📡 API Endpoints

Check the endpoints using SwaggerUI:

Swagger UI: http://127.0.0.1:8000/docs
