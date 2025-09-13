# TODO App (React + Vite + Redux)

This project is a **TODO app** built using **React + Vite** with **Redux** for global state management. The app allows users to log in with their name, manage their todo list, and fetch existing todos when they log in again.

---

## 🚀 Features

### 👤 User Login / Logout
- Users can log in using their **name**.
- On logout, the session ends.
- When a user logs in again, their existing todos are fetched and displayed.

### 📝 Todo Management
Each Todo object contains:
- `id`
- `name`
- `completed` (status)

By default, the todo list is empty for new users.

Supported actions:
- ✅ Add a new Todo  
- 🔄 Update the status of a Todo (mark complete/incomplete)  
- ❌ Remove a Todo  
- ✏️ Update Todo name (if time permits)  

### 🌍 State Management
- Uses **Redux** for global state management.

### 🎨 UI Components
- Uses **React-Bootstrap** for a clean, responsive UI.

---

## 🛠️ Tech Stack
- **React (Vite)** → Frontend Framework  
- **Redux** → Global State Management  
- **React-Bootstrap** → UI Components  
- **Local Storage / Redux-Persist** → Persist user todos across logins  

---

## 📦 Installation

Clone the repository:
```bash
git clone <your-repo-url>
cd <your-project-folder>

---

## 📸 Screenshots

### 🔐 Login Screen
![Welcome Screenshot](./public/welcome_screen.jpg)

### ✅ Todo List
![Home Screen](./public/home_screen.jpg)
![Add Task](./public/add_task.jpg)
![Edit Task](./public/edit_task.jpg)
![Complete Task](./public/complete_task.jpg)
