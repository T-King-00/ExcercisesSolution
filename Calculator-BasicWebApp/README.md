# 📘 .NET Minimal API – Calculator Web Application

A simple .NET Minimal API project created as part of an exercise to learn how to build lightweight web applications using ASP.NET Core
that provides a basic calculator API with four mathematical operations. 
This project was built starting from an Empty project template as part of a .NET exercise.

The application exposes four mathematical operations as HTTP endpoints: Add, Subtract, Multiply, and Divide.

## Project Architecture  
This solution is organized into two separate projects to keep the application clean, modular, and easy to maintain:  
-  ### Calculator Logic Project (Class Library)
   A dedicated project that contains all core calculator logic.
-  ### Web API Project (Minimal API)  
      A .NET Minimal API project responsible for exposing the calculator operations as HTTP endpoints.  
      This project references the calculator logic project and uses it to process incoming requests.
   
## 📘 Swagger API Documentation  
### Swagger (OpenAPI) is enabled in the Web API project to provide:  

1- Interactive API documentation

2- A built‑in UI for testing endpoints

3- Automatic request/response visualization

After running the project, you can access Swagger UI at:

 ` "http://localhost:<port>/swagger" `
