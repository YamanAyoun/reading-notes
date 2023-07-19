# Dependency Injection & Repository patterns

## Dependency Injection
Dependency Injection (DI) is a technique that facilitates Inversion of Control (IOC) between classes and their dependencies. When implementing services with dependency injection, 
it's essential to avoid stateful, static classes and members, as well as creating global state. Instead, design applications to use singleton services. Additionally, 
direct instantiation of dependent classes within services should be avoided to prevent tight coupling to specific implementations. 
It's recommended to create small, well-factored, and easily testable services.

## Repository pattern
The Repository pattern involves encapsulating data access logic in classes or components called repositories. 
These repositories centralize common data access functionality, promoting better maintainability and decoupling the database access infrastructure or technology from the domain model layer. 
By adopting the repository pattern, it becomes easier to test applications using unit tests.

## SOLID principles
SOLID principles are a set of five guidelines in software development introduced by Robert "Uncle Bob" Martin. These principles aim to help software developers create well-designed, high-quality, and easily maintainable software. They were proposed in the early 2000s and have become a fundamental concept in modern software development, particularly in Test-Driven Development (TDD).

## Why SOLID Matters?
SOLID Principles is a coding standard that all developers should have a clear concept for developing software properly to avoid a bad design. They are to help you make your code easy to adjust, extend and test with little to no problems.

## SOLID stands for:

1. Single Responsibility Principle (SRP): This principle emphasizes that a class should have a single responsibility or purpose, focusing on a specific functionality. By adhering to this principle, classes become more manageable and less prone to change when modifications are needed.

2. Open/Close Principle (OCP): The OCP suggests that software entities, whether classes or methods, should be open for extension but closed for modification. This means that new functionality can be added without altering existing code, promoting code reusability and maintainability.

3. Liskov Substitution Principle (LSP): The LSP states that objects of derived classes should be substitutable for objects of the base class without affecting the correctness of the program. This principle encourages the use of polymorphism and inheritance in a way that does not break the behavior of the program.

4. Interface Segregation Principle (ISP): According to ISP, clients should not be forced to depend on interfaces they don't use. It advocates for creating fine-grained interfaces tailored to the specific needs of clients, promoting more cohesive and decoupled designs.

5. Dependency Inversion Principle (DIP): DIP suggests that high-level modules/classes should not depend on low-level modules/classes directly. Instead, both should depend on abstractions. This principle encourages the use of dependency injection to decouple components and enhance flexibility.
