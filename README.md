📝 Student Task Manager
A simple FastAPI CRUD application to manage student tasks efficiently. This project demonstrates how to build a RESTful API using FastAPI, SQLAlchemy, and SQLite.
🚀 Features
- Create, Read, Update, Delete (CRUD) operations for student tasks
- SQLite database integration
- Pydantic models for data validation
- Modular code structure with separate files for models, schemas, and database setup
📁 Project Structure
Student-Task-manager-/
├── main.py             # FastAPI app entry point
├── models.py           # SQLAlchemy models
├── schemas.py          # Pydantic schemas
├── database.py         # Database connection and session
├── student_tracker.db  # SQLite database file
├── test.db             # Additional test database
└── __pycache__/        # Python cache files


🛠️ Technologies Used
- Python 3.10+
- FastAPI
- SQLAlchemy
- Pydantic
- SQLite
▶️ Getting Started
- Install dependencies:
pip install fastapi uvicorn sqlalchemy
- Run the application:
uvicorn main:app --reload
- Access the API docs: Open your browser and go to http://127.0.0.1:8000/docs
📌 Endpoints Overview
- GET /students – List all students
- POST /students – Add a new student
- PUT /students/{id} – Update student info
- DELETE /students/{id} – Remove a student
📄 License
This project is open-source and available under the MIT License.
