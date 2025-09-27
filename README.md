# Blazor ToDo App 📝

A simple **ToDo application** built with **Blazor Server**, **.NET 8**, and **PostgreSQL**.  
This project is created as a portfolio sample to demonstrate CRUD operations, clean architecture, and integration with a relational database.

---

## ✨ Features
- Add new tasks
- Edit tasks
- Mark tasks as completed ✅
- Delete tasks
- Data stored in **PostgreSQL** using Entity Framework Core

---

## 🛠️ Tech Stack
- [Blazor Server](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
- [.NET 8](https://dotnet.microsoft.com/)
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/) (optional for running DB)

---

## 🚀 Getting Started

### Prerequisites
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or later
- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [PostgreSQL](https://www.postgresql.org/download/) installed locally  
  or use Docker:

```bash
docker run --name todo-postgres -e POSTGRES_PASSWORD=123456 -p 5432:5432 -d postgres:15

