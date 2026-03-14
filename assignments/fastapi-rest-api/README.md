# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a RESTful API in Python using the FastAPI framework, including defining endpoints, request/response models, and running the server.

## 📝 Tasks

### 🛠️ Set Up the FastAPI Project

#### Description
Install FastAPI and Uvicorn, create a basic FastAPI app, and run it locally.

#### Requirements
Completed project should:

- Include a `requirements.txt` (or install commands) for FastAPI and Uvicorn
- Create a `main.py` file with a FastAPI app instance
- Run the server locally (e.g., `uvicorn main:app --reload`)
- Verify the automatic API docs work at `/docs`


### 🛠️ Create CRUD Endpoints

#### Description
Build endpoints that create, read, update, and delete items using Pydantic models.

#### Requirements
Completed project should:

- Define a Pydantic model for an item (e.g., `id`, `name`, `description`, `price`)
- Implement endpoints:
  - `GET /items/` – list all items
  - `GET /items/{item_id}` – get a single item by ID
  - `POST /items/` – create a new item
  - `PUT /items/{item_id}` – update an existing item
  - `DELETE /items/{item_id}` – delete an item
- Use an in-memory store (like a Python dict) for data
- Return appropriate status codes and error messages (e.g., 201 on create, 404 when not found)
