# 📝 React To-Do List Application

A fully functional and beginner-friendly **To-Do List Application** built using **React.js**.  
This project allows users to manage daily tasks efficiently by adding, deleting, and reordering tasks.

This project is ideal for beginners who want to understand **React Hooks**, **state management**, and **event handling** in a real-world example.

---

## 🌐 Live Demo (Deployed Link)

👉 **Live Application:**  
🔗 https://todo-app-ecru-ten-31.vercel.app/

> _(Example: Vercel / Netlify deployment link)_  
> Replace this link with your actual deployed project URL.

---

## 📌 Project Overview

The React To-Do List App helps users:

- Organize daily tasks
- Maintain task priority using move up/down
- Practice React fundamentals with clean code

---

## 🚀 Features

- ➕ Add new tasks
- 🗑️ Delete existing tasks
- ⬆️ Move tasks up in the list
- ⬇️ Move tasks down in the list
- ⛔ Prevents adding empty tasks
- ⚛️ Uses React Functional Components
- 🧠 Uses React Hooks (`useState`)
- 🧼 Clean, readable, and maintainable code

---

## 🛠️ Technologies Used

- **React.js**
- **JavaScript (ES6+)**
- **CSS**
- **Vite** (for fast React setup)
- **Vercel / Netlify** (for deployment)

---


## 📂 Folder Structure
src/
│
├── ToDoList.jsx # Main To-Do List component
├── App.jsx # Root component
├── index.css # Styling
├── main.jsx # Entry point


---

## ⚙️ Core Concepts Used

### 🔹 React Hooks

- `useState` → Used to manage tasks and input state

js
const [tasks, setTasks] = useState([]);
const [newTask, setNewTask] = useState("");
🧠 Application Logic Explained
➕ Add Task

Takes input from the user

Uses trim() to prevent empty tasks

Adds the task to the existing list using spread operator

🗑️ Delete Task

Deletes a task using its index

Uses filter() to keep the state immutable


const updatedTasks = tasks.filter((_, i) => i !== index);



⬆️ Move Task Up

Checks if the task is not already at the top

Swaps the task with the previous one using array destructuring

⬇️ Move Task Down

Checks if the task is not already at the bottom

Swaps the task with the next one safely

🖱️ Event Handling

onChange → Updates input field

onClick → Handles add, delete, move up, move down actions


1️⃣ Clone the Repository


git clone https://github.com/S-R-Daniel-324/todo_app

2️⃣ Go to Project Directory

cd my-react-app

3️⃣ Install Dependencies

npm install

4️⃣ Start Development Server

npm run dev
