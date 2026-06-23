# Studio de Beleza

[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

## Table of Contents

- [Context](#-context)
- [Software features](#-software-features)
- [Technologies and tools](#-technologies-and-tools)
- [Architecture](#-architecture)
- [Repository structure](#-repository-structure)
- [Requirements](#-requirements)
- [How to run](#-how-to-run)
- [Author](#-author)

# 📌 Context 

This project consists of a desktop management system designed for a fictitious beauty salon (Studio de Beleza). It allows managing clients, employees, inventory, payroll, cash flow, and schedules.

## 🚀 Software features

- **Employee Management:** Manage employees and log attendance.
- **Client & Provider Management:** Register and edit clients and suppliers.
- **Inventory Control:** Monitor product stock levels.
- **Financial Flow:** Track cash flow, expenses, payroll, and orders.
- **Database Connection:** Connected to a MySQL database to persist all data.

## 🛠️ Technologies and tools

- C# (.NET Framework)
- Windows Forms (UI)
- MySQL (Database)

## 📋 Architecture

No specific architecture defined.

## 📂 Repository structure

```text
- 📂 desktop-projeto-integrador2018/
  - 📂 ProjetoADM/
    - 📄 ProjetoADM.sln (Solution file)
    - 📂 ProjetoADM/ (Main project folder)
      - 📄 App.config
      - 📄 Program.cs
      - 📄 ProjetoADM.csproj
      - 📂 Codigos/
        - 📂 BASE/
          - 📄 Connection.cs (Database connection settings)
          - 📄 Database.cs (Helper database class)
        - 📄 Script do banco.txt (Database schema script)
        - 📄 script de inserts.txt (Initial data scripts)
      - 📂 Telas/ (User interface forms)
```

## 📦 Requirements

- Visual Studio 2022 or higher
- MySQL Workbench
- MySQL Server (XAMPP, WampServer, or local MySQL instance)
- .NET Framework 4.7.2 or higher

## ⚙️ How to run

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/MatheusRodri/desktop-projeto-integrador2018.git
cd desktop-projeto-integrador2018
```

### 2. Database Configuration
1. Ensure your local MySQL server is running.
2. Open **MySQL Workbench**.
3. Locate the SQL script file: `ProjetoADM/ProjetoADM/Codigos/Script do banco.txt`.
4. Copy and execute its contents in MySQL Workbench to create the database tables.
5. (Optional) Run the inserts script from `ProjetoADM/ProjetoADM/Codigos/script de inserts.txt` to seed the database.

### 3. Connection Configuration
1. Open the solution file `ProjetoADM/ProjetoADM.sln` in **Visual Studio**.
2. Navigate to `ProjetoADM/ProjetoADM/Codigos/BASE/Connection.cs` inside the Solution Explorer.
3. Modify the connection string credentials (specifically `password`) to match your local MySQL configuration.

### 4. Build and Run
1. Restore NuGet packages if necessary.
2. Build and run the project from Visual Studio by pressing **F5** or clicking the **Start** button.

## 👤 Author

Matheus Rodrigues 
[LinkedIn](https://linkedin.com/in/matheus-rodrigues-mrj) [GitHub](https://github.com/MatheusRodri)