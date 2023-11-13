# Introduction to Databases
## Database 
Database:  is a collection of related data and data is a collection of facts and figures that can be processed to produce information.

**Some attributes used for Databases in C#:** <br />
* DataType attribute: Specifies a more specific data type than the database intrinsic type for a property. It allows you to provide additional constraints or information about the data type.

* StringLength attribute: Sets the maximum length for a string property in the database. It also provides client-side and server-side validation for ASP.NET Core MVC, ensuring that the length of the input falls within the specified limit.

* Required attribute: Marks properties as required fields, indicating that they must have a value. If a property has a non-nullable data type, it is automatically treated as a required field.

* Display attribute: Specifies the caption or display name for a property in a user interface. It is used to provide a more user-friendly name for a property that will be displayed in forms or views.

* A database management system (DBMS) stores data in such a way that it becomes easier to retrieve, manipulate, and produce information.


## Database Schema
A database schema is an abstract design that defines the structure and organization of data in a database. 
It serves as a blueprint or architecture for how the data will be stored and how different tables or models relate to each other. 

Database schema will include:

1. All important or relevant data
2. Consistent formatting for all data entries
3. Unique keys for all entries and database objects
4. Each column in a table has a name and data type


## Database Keys
A key in DBMS is an attribute or a set of attributes that help to uniquely identify a row in a relation (or table). Keys are also used to establish relationships between the different tables and columns of a relational database.

More details about each one:
1. Primary Key<br />
A primary key is a column of a table or a set of columns that helps to identify every record present in that table uniquely. There can be only one primary Key in a table. Also, the primary Key cannot have the same values repeating for any row. Every value of the primary key has to be different with no repetitions.

2. Foreign Key<br />
Foreign Key is used to establish relationships between two tables. A foreign key will require each value in a column or set of columns to match the Primary Key of the referential table. Foreign keys help to maintain data and referential integrity. 

3. Composite Key<br />
Composite Key is a set of two or more attributes that help identify each tuple in a table uniquely. The attributes in the set may not be unique when considered separately.

## Types of Database Relationships
1. One to One Relationship:<br />
It is used to create a relationship between two tables in which a single row of the first table can only be related to one and only one records of a second table. Similarly, the row of a second table can also be related to anyone row of the first table.

2. One to Many Relationship:<br />
It is used to create a relationship between two tables. Any single rows of the first table can be related to one or more rows of the second tables, but the rows of second tables can only relate to the only row in the first table. It is also known as a many to one relationship.

3. Many to Many Relationship:<br />
It is many to many relationships that create a relationship between two tables. Each record of the first table can relate to any records (or no records) in the second table. Similarly, each record of the second table can also relate to more than one record of the first table.
