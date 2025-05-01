# 📝 Todo List Web Application — Coding Challenge

This is a full-stack **To-Do List web application** built for a coding challenge using **Blazor WebAssembly**, **ASP.NET Core Web API**, and **Azure SQL**.

It includes a dynamic UI for managing tasks and a connected REST API with cloud database integration, following clean architecture and OOP best practices.

---

## 📌 Features

- ✅ Add new tasks with title, description, due date, and priority
- 🖊️ Edit and update existing tasks
- ❌ Delete tasks
- ✅ Mark tasks as completed
- 🔍 Filter tasks (All / Pending / Completed)
- ☁️ Data persistence using **Azure SQL Database**
- 🧪 Unit tests using `xUnit` and `Moq`
- 🚀 Blazor frontend connected to RESTful API

---

## 🧱 Tech Stack

| Layer        | Tech                                           |
|--------------|------------------------------------------------|
| Frontend     | Blazor WebAssembly                             |
| Backend API  | ASP.NET Core Web API                           |
| Database     | Azure SQL Database                             |
| Architecture | Repository Pattern, OOP, DI (Singletons)       |
| Testing      | xUnit, Moq                                     |
| Deployment   | Hosted locally / SQL hosted on Azure           |

---

## 🛠️ Setup Instructions

### 1. Clone the Project

```bash
git clone https://github.com/your-username/todo-challenge.git
cd todo-challenge
