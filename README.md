﻿# 📝 NotesAPI

A simple ASP.NET Core 8 Web API for managing notes.  
Built with **Entity Framework Core** and **SQL Server**.

---

## 🚀 Features
- Create, read, update, and delete notes
- Connected to SQL Server using EF Core
- Built-in Swagger UI for testing endpoints
- Clean architecture with Models, Data, and Controllers

---

## ⚙️ Technologies Used
- ASP.NET Core 8
- Entity Framework Core
- SQL Server
- Swagger / OpenAPI

---

## 🧩 Endpoints (via Swagger)
- `GET /api/notes` — Get all notes  
- `GET /api/notes/{id}` — Get a note by ID  
- `POST /api/notes` — Create a new note  
- `PUT /api/notes/{id}` — Update a note  
- `DELETE /api/notes/{id}` — Delete a note  

---

## 🛠️ Run Locally

### 1️ Clone the project
```bash
git clone https://github.com/Tala-yus/NotesAPI.git
cd NotesAPI

### 2️ Update Database

Copy code
dotnet ef database update

### 3️ Run the project

Copy code
dotnet run
Open in browser:
👉 https://localhost:5001/swagger