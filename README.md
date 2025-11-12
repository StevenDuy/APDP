
---

## 🧠 README for Main APDP Project

```markdown
# APDP - Course Project

## 📖 Overview
This is the main project for the **Applied Programming and Design Principles (APDP)** course. It demonstrates the integration of OOP, design patterns, and database management in a real-world application.

## 🛠 Technologies Used
- **IDE**: Visual Studio Community 2022
- **Language**: C#
- **Framework**: .NET 6.0
- **Database**: SQL Server (via Entity Framework Core)
- **ORM**: Entity Framework Core with Code-First Migrations

## 📂 Project Structure
- `Models/`: Entity classes representing database tables
- `Data/Migrations/`: EF Core migration files for database schema
- `Controllers/`: Business logic and data access
- `Views/`: UI components (if using MVC)
- `appsettings.json`: Configuration file including database connection string

## 🧩 Database Setup
1. Open `appsettings.json` and update the connection string:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=SIMS_DB;Trusted_Connection=True;"
   }
