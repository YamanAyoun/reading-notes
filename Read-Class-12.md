# Entity Framework and APIs

## Entity Framework Core

Entity Framework (EF) Core is a lightweight, open-source, cross-platform version of Entity Framework that allows .NET developers to work with databases using .NET objects. 
It eliminates the need for writing repetitive data-access code by providing an object-relational mapping (O/RM) approach.

In EF Core, data access is performed through a model, which consists of entity classes representing database tables and a context object representing a session with the database. 
You can query the database using LINQ to retrieve instances of entity classes and save data by creating, deleting, and modifying instances of entity classes.

## Data seeding
Data seeding is another feature provided by EF Core, which allows you to populate a database with an initial set of data. 
You can associate data seeding with an entity type as part of the model configuration, and EF Core migrations can automatically handle data operations when upgrading the database schema.


## User Secrets
User secrets provide a secure way to store private user information, such as API keys, connection strings, and client secrets.
It allows you to store these sensitive data locally and separate them from the source control. User secrets are typically used to
protect confidential information that should not be exposed to others when using your code base.

To create a simple Web API using ASP.NET MVC, C#, and Visual Studio, you can follow these steps:

1. Create an ASP.NET Web Application project in Visual Studio.
2. Select the Web API template during project creation.
3. Review the project files, including the default controllers and startup configuration.
4. Add a new controller to define the API endpoints and their corresponding methods.
5. Implement the desired functionality in the controller methods.
6. Build and run your project to test the API endpoints.
