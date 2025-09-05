# task-manager-auth

# ✅ Task Manager with User Authentication

A **Python-based task manager** that allows users to securely log in, register, and manage their personal tasks. Each user has a **separate task list** stored persistently via file handling. The system provides an **interactive, menu-driven interface** where authenticated users can add, view, complete, and delete tasks.

---

## 📌 Problem Statement
In today’s world, individuals often need to keep track of various tasks in a structured way.  
This project implements a **Task Manager** with built-in **user authentication**. Each user logs in with a username and password, ensuring that **only the authenticated user** can access and manage their own tasks.

---

## 🎯 Objectives
1. Implement a **user authentication system** with login and registration  
2. Create a **task management system** that allows users to:  
   - Add tasks  
   - View tasks  
   - Mark tasks as completed  
   - Delete tasks  
3. Use **file handling** to store user credentials and tasks persistently  
4. Provide an **interactive, menu-driven interface** for task management  

---

## 🛠 Features
- **User Authentication** → Secure login and registration  
- **Task Management** → Add, view, complete, and delete tasks  
- **Persistent Storage** → Credentials and tasks stored in files per user  
- **Menu-Driven Interface** → Simple and interactive CLI  

---

## 🚀 Steps Implemented
1. **User Authentication**  
   - Registration: Save username and password to a file  
   - Login: Verify credentials before accessing tasks  

2. **Task Operations**  
   - Add new tasks with description  
   - View pending and completed tasks  
   - Mark tasks as completed  
   - Delete tasks from the list  

3. **File Handling**  
   - Store each user’s tasks in a separate file  
   - Load tasks when the user logs in  

4. **Menu System**  
   - Options: Add | View | Complete | Delete | Logout  
   - Menu-driven loop for user interaction  

---


