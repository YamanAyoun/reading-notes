# Object Oriented Principles

**What is Object-Oriented Programming(OOP)**

 It is a programming paradigm that organizes code and data into reusable structures called objects. Objects are instances of classes, which serve as blueprints for creating objects with specific attributes (data) and behaviors (methods).




Object-oriented programming in the context of C# and focuses on the four fundamental principles of object-oriented programming: abstraction, encapsulation, inheritance, and polymorphism.

***Abstract*** and virtual methods are important in inheritance. A virtual method in a base class can be overridden in a derived class with its own implementation. An abstract method in a base class must be implemented in any non-abstract class that directly inherits from it. Abstract classes can be used as blueprints for derived classes and cannot be instantiated directly. An abstract class cannot be instantiated. The purpose of an abstract class is to provide a common definition of a base class that multiple derived classes can share.

A sealed class cannot be used as a base class. For this reason, it cannot also be an abstract class. Sealed classes prevent derivation. Because they can never be used as a base class, some run-time optimizations can make calling sealed class members slightly faster.


***Encapsulation*** emphasizes hiding the internal state and implementation details of an object and providing controlled access through a set of public functions. This protects the integrity of the object's data and provides a clear interface for interacting with the object.

***Inheritance*** is a core feature of object-oriented programming where one class can inherit the properties and methods of another class. The class being inherited from is called the base class or superclass, and the class inheriting from it is called the derived class or subclass. A derived class can have only one direct base class, but inheritance can be transitive, allowing multiple levels of inheritance.

***Polymorphism*** is a fundamental concept in object-oriented programming that allows objects of different types to be treated as instances of a common base type. It enables objects to exhibit different behaviors based on their specific types or classes.
