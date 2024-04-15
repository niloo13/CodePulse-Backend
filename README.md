# CodePulse - ASP.NET Core Web API

## Introduction
This ASP.NET Core Web API is a backend service designed to support the Angular frontend application. It handles CRUD operations, user authentication, and provides data persistence via Entity Framework Core with a SQL Server database.

## Features
- CRUD operations with HTTP methods GET, POST, PUT, DELETE
- Authentication and authorization with JWT tokens
- Entity Framework Core integration
- Dependency Injection
- Image file handling
- Swagger API documentation

## Prerequisites
- .NET Core SDK
- SQL Server

## Installation
1. Clone the repository:
   ```
   git clone ....
   ```
2. Navigate to the project directory:
   ```
   cd [project-directory]
   ```

## Database Setup
- Ensure SQL Server is running.
- Update the connection string in `appsettings.json`.

## Running the Application
1. Build and run the application:
   ```
   dotnet run
   ```

## Testing the API
- Use Postman or Swagger at `http://localhost:[port]/swagger` to test the API endpoints.

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
Specify the license under which the project is made available.

## Contact
For support or queries, reach out to hamidi.niloofar@gmail.com.
