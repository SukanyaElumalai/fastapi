# Fastapi

FastAPI Project

This application aims to perform CRUD(Create, Read, Update, Delete) operations to update Inventory products.

# 🚀 Key Features: Manage product entries, updates, and deletions

CORS Enabled: Pre-configured to communicate with frontend frameworks (default: http://localhost:3000).

Dependency Injection: Utilizes FastAPI’s Depends for efficient and thread-safe database session management.

Auto-Documentation: Instant access to interactive API testing via Swagger UI.

# 🛠️ Tech Stack:
# 📥 Installation & SetupPrerequisitesIDE: 
IntelliJ IDEA (with Python plugin) or VS Code.

Database: PgAdmin 4 and a running PostgreSQL instance.

Environment: Python 3.10+.

Step 1: Clone & Navigate

git clone [https://github.com/SukanyaElumalai/fastapi.git](https://github.com/SukanyaElumalai/fastapi.git)

cd fastapi

Step 2: Activate Virtual EnvironmentUse the pre-configured environment in  project folder:

.\myenv\Scripts\Activate.ps1

Step 3: Install Dependencies:

pip install fastapi uvicorn sqlalchemy pydantic

Step 4: Launch the Backend

uvicorn main:app --reload

The server will start at http://127.0.0.1:8000

Step 5: Launch the Frontend in new terminal:
cd frontend
npm install
npm start

# 📡 API DocumentationTest your endpoints directly through the browser:

Interactive Swagger UI: http://127.0.0.1:8000/docs

GET /products - Retrieve all inventory items.

POST /products - Add a new product.

PUT /products/{id} - Update existing product details.

DELETE /products/{id} - Remove an item from inventory.

