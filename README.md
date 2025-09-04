# 🎓 Student Management REST API

A simple **Student Management System** built with **ASP.NET Core Web API**, following a clean layered architecture:
**Controller → Business Layer → Data Access Layer → Database**.

## 🚀 Features
- ✅ **GET /api/students/all** → Retrieve all students  
- ✅ **GET /api/students/passed** → Get all students who passed  
- ✅ **GET /api/students/averagegrade** → Calculate the average grade  
- ✅ **GET /api/students/{id}** → Retrieve a student by ID  
- ✅ **POST /api/students** → Add a new student  
- ✅ **PUT /api/students/{id}** → Update student details  
- ✅ **DELETE /api/students/{id}** → Delete a student  

## 🛠 Tech Stack
- **ASP.NET Core 7.0** – Web API framework  
- **C# DTO & Business Layer** – Clean separation of concerns  
- **Microsoft SQL Server** – Database (with Stored Procedures)  
- **Entity-like Manual Data Access** – Using `SqlConnection`, `SqlCommand`  


