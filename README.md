# Bulky_MVC

**E-Commerce ASP.NET Core MVC project demonstrating clean architecture, CRUD operations, and common web dev patterns.**

## Overview
Bulky_MVC is an ASP.NET Core MVC web application structured using N-tier architecture. It implements core patterns such as Repository, Unit of Work, and utilizes Entity Framework Core for data access. The app features CRUD functionality for products and categories, and follows best practices for maintainable ASP.NET projects.

## Features
- CRUD operations
- N-tier architecture 
- Repository & Unit of Work patterns
- Entity Framework Core + SQL Server integration
- ASP.NET Core Identity for user authentication
- Role-based authorization 
- Razor views with Bootstrap for responsive UI
- Notification system using Toastr 

## Installation & Run
1. Clone the repository:
   git clone https://github.com/EEyad77/Bulky_MVC.git
   cd Bulky_MVC
2. Open the solution file (Bulky.sln) in your IDE.
3. Update the connection string in appsettings.json to point to your database.
4. If you have a DbInitializer:
    dotnet run --project BulkyWeb
    or start via Visual Studio—this should create the database and seed data.
5. Register a new user, or seed an initial admin user manually.


