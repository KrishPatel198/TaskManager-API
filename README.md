
# 🧠 TaskManager API

A simple and modern .NET 9 Web API to manage personal tasks.  
Built using Entity Framework Core with SQLite for persistence and tested via Swagger UI.

## 🚀 Features
- Full CRUD operations (Create, Read, Update, Delete)
- RESTful endpoints with ASP.NET Core Web API
- Persistent SQLite backend via EF Core
- Swagger UI for easy API testing
- Built with the latest minimal hosting model

## 🛠 Getting Started

```bash
git clone https://github.com/KrishPatel198/TaskManager-API.git
cd TaskManager-API
dotnet restore
dotnet ef database update
dotnet run --urls "http://localhost:5000;https://localhost:5001"
````

Then visit: [https://localhost:5001/swagger/index.html](https://localhost:5001/swagger/index.html)

## 🧰 Tech Stack

* .NET 9
* ASP.NET Core
* Entity Framework Core
* SQLite
* Swagger (Swashbuckle)

## 📂 Folder Structure

```
TaskManager/
├── Controllers/
│   └── TasksController.cs
├── Models/
│   ├── TaskItem.cs
│   └── TaskContext.cs
├── Program.cs
└── tasks.db (auto-created at runtime)
```

## 📜 License

MIT

