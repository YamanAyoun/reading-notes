## Data Transfer Objects
A Data Transfer Object (commonly known as a DTO) is usually an instance of a POCO (plain old CLR object) class used as a 
container to encapsulate data and pass it from one layer of the application to another.
The biggest advantage of using DTOs is decoupling clients from your internal data structures.

## Immutability of DTOs
A DTO is meant to transport data from one layer of an application to another layer. 
The consumer of a DTO might be built in .NET/C#/Java or even JavaScript/TypeScript. 
A DTO is often serialized so that it can be independent of the technology used in the receiver.
