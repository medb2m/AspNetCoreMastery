# ASP.NET Core RealWorld Example (Learning Project)

This project is a personal implementation of the [RealWorld](https://github.com/gothinkster/realworld) API using **ASP.NET Core**.  
I built it from scratch to understand how to design and develop a complete backend application following modern .NET practices.

## Overview

The goal of this project was to recreate the RealWorld backend using ASP.NET Core, while applying concepts like:
- CRUD operations  
- Authentication with JWT  
- Routing and pagination  
- Separation of concerns  
- Clean and maintainable code organization

Through this process, I focused on learning how professional ASP.NET Core applications are structured and how to apply best practices for scalability and readability.

## What I Learned

While building this project, I learned how to:
- Use **CQRS** and **MediatR** to simplify communication between layers and keep controllers clean.  
- Implement **AutoMapper** to handle object mapping efficiently.  
- Validate data using **FluentValidation**.  
- Organize the solution using **feature folders** and **vertical slices** instead of the traditional layered approach.  
- Work with **Entity Framework Core** and use **SQLite** as a lightweight database for testing.  
- Configure **JWT authentication** for secure login and user management.  
- Document and test APIs using **Swagger**.  
- Apply consistent code style with `.editorconfig` and automated formatting tools.

## Running the Project

To run the project locally:
1. Make sure you have the **.NET SDK** installed.  
2. Run the following command from the terminal:  
   ```
   dotnet run
   ```
3. Open your browser at:  
   ```
   http://localhost:5000/swagger
   ```
   to explore the API documentation.

## Purpose

This repository is part of my personal learning journey to master ASP.NET Core backend development.  
It helped me understand not only the technical tools, but also the architecture and mindset required to build real-world applications.
