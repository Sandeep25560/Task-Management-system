# Task Management System

A full-stack task management system built with **React + Vite (TypeScript)** for the frontend and **ASP.NET Core Web API** for the backend, using **SQL Server** for the database.

---

## 🚀 Getting Started

### 📚 Table of Contents
- [Prerequisites](#prerequisites)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Tech Stack](#tech-stack)

---

## ✅ Prerequisites

Ensure the following tools are installed:

- [.NET SDK](https://dotnet.microsoft.com/en-us/download) (version 6.0 or later)
- [Node.js](https://nodejs.org/) (version 14 or later)
- npm (comes with Node.js)
- SQL Server or another compatible database

---

## 🛠️ Backend Setup

### 1. Clone the repository
```bash
git clone https://github.com/Sandeep25560/Task-Management-system.git

### 2. Configure the database:
- Update the `appsettings.json` file with your database connection string.
- Example `appsettings.json`:
  ```json
  {
    "ConnectionStrings": {
      "DefaultConnection": "Server=your_server_name;Database=your_database_name;User Id=your_username;Password=your_password;"
    },
    ...
  }
  ```

### 3. Run Entity Framework migrations:
```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
```

### 4. Install dependencies:
```bash
dotnet restore
```

### 5. Running the Backend
```bash
dotnet run
```
The backend API will be available at `http://localhost:5068`


## Frontend Setup
### 1. Navigate to the frontend directory:
```bash
cd ../../frontend
```

### 2. Install dependencies:
```bash
npm install
```


### 3. Running the Frontend
```bash
npm start
```
The frontend will be available at ` http://localhost:5173/`.


# Tech Stack:
Following Tech Stack is being implemented:
- React + Typescript for frontend
- ASP.NET Core Web Api
- SQL Server Management Studio for database
- Redux for state management in React
- Serilog for Application logging (to be implemented)
- xUnit for unit testing (to be implemented)
- SonarQube for analyzing code quality (to be implemented)
