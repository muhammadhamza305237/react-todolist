# 📋 iTask — React Todo App

A responsive task management web application built with **React**, **Tailwind CSS**, **React Icons**, **UUID**, and **Vite**, featuring task creation, completion toggling, editing, deletion, finished-task filtering, and `localStorage` persistence.

**Live Demo:** https://todo-list-steel-psi-83.vercel.app

## 🛠️ Tech Stack
- **Frontend:** React 18 (Vite), Tailwind CSS
- **Icons & Utilities:** `react-icons` (`FaEdit`, `AiFillDelete`), `uuid` (`uuidv4`)
- **Persistence:** Browser `localStorage`

## ✨ Key Features
- **Add & Edit Todos:** Add new tasks with minimum character validation and load existing tasks back into the input field to edit and save.
- **Completion Toggle & Finished Filter:** Mark tasks complete with strikethrough styling and toggle visibility of completed items via **Show Finished**.
- **Delete & Empty State:** Remove individual tasks by ID and display a clear empty-state message when no todos are present.
- **LocalStorage Persistence:** Automatically loads saved tasks on startup and saves updates to `localStorage`.

## 🚀 How to run locally
1. Clone the repository
2. Run `npm install`
3. Run `npm run dev`