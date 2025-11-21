# Acxiom17
📘 CRM Management System – ASP.NET Core MVC

A complete Customer Relationship Management (CRM) System built with ASP.NET Core MVC, designed to manage Customer & Employee records efficiently with a modern dashboard, live search, statistics, and real-time insights.

This project is suitable for company internal management, small businesses, or learning ASP.NET Core architecture.

⭐ Features
📊 1. Dashboard Overview

A clean, responsive dashboard displaying:

Total Customers

Total Employees

New Customers Today

New Employees Today

Recent Customers Table

Recent Employees Table

🔍 2. Smart Search System

Search any Customer or Employee by:

Name

Email

Phone

✔ Instant live search (AJAX)
✔ Shows complete details in a Bootstrap modal popup

👥 3. Customer Module

Add Customer

Edit Customer

Delete Customer

View All Customers

Recent Customer Activity

💼 4. Employee Module

Add Employee

Update Employee

Delete Employee

View All Employees

Position & Contact Details

📄 5. Reports Module

(If enabled in your project)

Daily Insights

Summary Reports

Activity Tracking

🛠️ Tech Stack
Technology	Purpose
ASP.NET Core MVC	Main application framework
Entity Framework Core	ORM for Database
SQL Server	Database
Bootstrap 5	Modern UI components
JavaScript + Fetch API	Live Search + AJAX
LINQ	Data filtering & queries
📁 Project Structure
├── Controllers
│     ├── DashboardController.cs
│     ├── CustomerController.cs
│     ├── EmployeeController.cs
│
├── Views
│     ├── Dashboard
│     │     ├── Index.cshtml
│     │     ├── _CustomerDetails.cshtml
│     │     ├── _EmployeeDetails.cshtml
│     ├── Customer
│     ├── Employee
│
├── Models
│     ├── Customer.cs
│     ├── Employee.cs
│     ├── Report.cs
│
├── wwwroot
│     ├── css
│     ├── js
│     ├── libs

🚀 How to Run the Project (Step-by-Step)
1️⃣ Clone the Repository
git clone https://github.com/yourusername/repository-name.git

2️⃣ Open Project

Open the .sln file in Visual Studio 2022 or later.

3️⃣ Configure Database

Open appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Your SQL Server Connection String"
}

4️⃣ Run Migrations

(Optional if DB not created)

Update-Database

5️⃣ Run the Project
dotnet run


OR press F5 in Visual Studio.

🔍 Search System Overview (How It Works)

Search Bar → API Endpoint → Filter Result → JSON → Show Results → View Details Modal

Technologies used:

Fetch API

Bootstrap 5 Modals

Partial Views

Fast, smooth, and no page reloads.
