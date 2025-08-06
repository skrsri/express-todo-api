# 📝 Express.js Todo API

A simple RESTful Todo API built with **Express.js** that performs CRUD operations using the **local JSON file system** for storage (no database required).

---

## 🚀 Features

- ✅ GET all todos
- ✅ GET a todo by ID
- ✅ POST a new todo
- ✅ PUT to update a todo
- ✅ DELETE a todo
- ✅ Handles 404 errors for unknown routes

---

## 📦 Tech Stack

- Node.js
- Express.js
- File System (`fs`)
- Postman (for testing)

---

## 📁 Project Structure
├── todos.json # Data store (JSON array)
├── app.js # Main Express app with API routes
├── README.md # Documentation


---

## 🛠️ API Endpoints

| Method | Route           | Description         |
|--------|------------------|---------------------|
| GET    | `/todos`         | Fetch all todos     |
| GET    | `/todos/:id`     | Get todo by ID      |
| POST   | `/todos`         | Create new todo     |
| PUT    | `/todos/:id`     | Update todo by ID   |
| DELETE | `/todos/:id`     | Delete todo by ID   |

---

## 📬 Sample Todo Format

```json
{
  "id": 12345,
  "title": "Complete Node project",
  "description": "Build an Express API for managing todos"
}

🚧 Future Improvements
Add input validation

Add persistent DB (MongoDB / PostgreSQL)

Add user authentication


🧑‍💻 Author
Built with ❤️ using Node.js and Express.
