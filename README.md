# 🗒️ NotesAPI

A simple yet professional **ASP.NET Core Web API** built with **.NET 8**, **Entity Framework Core**, and **SQL Server**.  
This API allows users to **create, read, update, and delete (CRUD)** notes, demonstrating clean architecture, database integration, and RESTful design.

---

## 🚀 Features

- ✅ Create new notes  
- 📖 Retrieve all notes  
- ✏️ Update existing notes  
- ❌ Delete notes  
- 🧩 Connected to SQL Server using Entity Framework Core  
- 🧠 Clean Git workflow with feature branches  
- 🧪 Tested with Swagger (OpenAPI)

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|-------------|
| Language | C# (.NET 8) |
| Framework | ASP.NET Core Web API |
| ORM | Entity Framework Core |
| Database | Microsoft SQL Server |
| API Testing | Swagger UI |
| Version Control | Git & GitHub |

---

## 🧰 Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/NotesAPI.git
cd NotesAPI
```

### 2. Create a local database connection
Edit the `appsettings.json` file:
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost\\SQLEXPRESS;Database=NotesDB;Trusted_Connection=True;TrustServerCertificate=True;"
}
```

> 💡 Adjust the server name if your SQL instance is different (e.g., `MSSQLSERVER` or another name).

### 3. Apply migrations & update the database
Run in **Package Manager Console**:
```powershell
Add-Migration InitialCreate
Update-Database
```

### 4. Run the project
Press **F5** or run:
dotnet run
```

Open your browser at:
```
https://localhost:5001/swagger


## 🧩 API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | `/api/notes` | Get all notes |
| GET | `/api/notes/{id}` | Get a note by ID |
| POST | `/api/notes` | Create a new note |
| PUT | `/api/notes/{id}` | Update an existing note |
| DELETE | `/api/notes/{id}` | Delete a note |

---

## 🧠 Learning Highlights

This project demonstrates:

- Clean architecture using controllers and models  
- Dependency injection and `DbContext` usage  
- CRUD operations with EF Core  
- Proper branching workflow with Git (`main`, `dev`, `feature/*`)  
- Professional README structure suitable for portfolios  

---

## 🧑‍💻 Git Workflow

# Create feature branch
git checkout -b feature/your-feature-name

# Stage & commit changes
git add .
git commit -m "feat: describe your feature"

# Push branch
git push -u origin feature/your-feature-name

# After merge, delete branch
git branch -d feature/your-feature-name
git push origin --delete feature/your-feature-name
```




