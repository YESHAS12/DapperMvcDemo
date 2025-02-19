# DapperMvcDemo

DotNet Core MVC CRUD With Dapper

Overview

This project demonstrates how to implement CRUD (Create, Read, Update, Delete) operations in a .NET Core MVC application using Dapper, a lightweight ORM (Object-Relational Mapping) tool.

Features

Setting up a .NET Core MVC project

Configuring a SQL Server database

Implementing Dapper for efficient database operations

Performing CRUD operations:

Create: Add new records to the database

Read: Retrieve and display data

Update: Modify existing records

Delete: Remove records

Setting up Controllers and Views for data interaction

Prerequisites

.NET Core SDK

SQL Server

Visual Studio or VS Code with C# extensions

Installation

Clone the repository:

git clone https://github.com/yourusername/dotnet-core-dapper-crud.git

Navigate to the project folder:

cd dotnet-core-dapper-crud

Install dependencies:

dotnet restore

Configure the database connection string in appsettings.json:

"ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=YOUR_DB;User Id=YOUR_USER;Password=YOUR_PASSWORD;"
}

Run the application:

dotnet run

Usage

Open the application in a browser.

Use the UI to perform CRUD operations.

Data is managed through SQL Server with Dapper handling the database interactions efficiently.

Technologies Used

.NET Core MVC

Dapper (Micro-ORM)

SQL Server

C#

Contributing

Contributions are welcome! Please open an issue or submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.
