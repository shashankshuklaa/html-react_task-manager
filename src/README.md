# 📝 React Task Manager Application

A task management web application built using **React.js** that allows users to add, delete, and mark tasks as completed. The application uses **React Hooks** and **Local Storage** to persist data across browser refreshes.

This project is developed as part of **Week 7 – Introduction to React.js** under *The Developers Arena Internship Program*.

---

## 📌 Project Overview

The React Task Manager demonstrates the use of component-based architecture, state management, and side effects in React. Users can efficiently manage daily tasks with real-time UI updates and persistent storage.

---

## 🚀 Features

- Add new tasks
- Delete existing tasks
- Mark tasks as completed
- Persist tasks using Local Storage
- Component-based React architecture
- Clean and responsive UI

---

## 🛠️ Technologies Used

- React.js (Functional Components)
- JavaScript (ES6+)
- HTML5
- CSS3
- Local Storage API

---

## 📂 Project Structure
task-manager/ ├── public/ │ └── index.html ├── src/ │ ├── components/ │ │ ├── TaskInput.js │ │ ├── TaskList.js │ │ └── TaskItem.js │ ├── App.js │ ├── App.css │ └── index.js ├── package.json └── README.md

---

## ⚙️ Setup Instructions

1. Install Node.js (LTS recommended)
2. Clone or download the repository
3. Open the project folder in VS Code
4. Run the application:

```bash
npm start


Open browser at:  http://localhost:3000

💾 Local Storage Implementation
Task data is stored in browser Local Storage.
On application load, tasks are initialized from Local Storage using useState.
Any updates to tasks are automatically synced using useEffect.

🧪 Testing
Tested task creation, deletion, and completion
Verified persistence after browser refresh
Checked console for runtime errors
Tested responsiveness on different screen sizes

👤 Author
Shashank Shukla
Web Development Intern
The Developers Arena
