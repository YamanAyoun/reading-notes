# Interface

In object-oriented programming, an interface is a way to define a set of related functionalities that a class or struct must implement. 
It serves as a contract, specifying the methods that must be implemented by the implementing class or struct. 
An interface can also include static methods with an implementation.

**What is interface**

In C#, interfaces cannot have instance data such as fields, auto-implemented properties, or property-like events. 
Instead, they focus solely on defining the behavior or functionality that the implementing types must provide.

The use of interfaces is particularly significant in C# because the language doesn't support multiple inheritance of classes. 
By implementing interfaces, a class can incorporate behavior from multiple sources, effectively achieving a form of multiple inheritance.

Interfaces also play a role in struct inheritance in C#. Since structs cannot directly inherit from other structs or classes, 
interfaces allow structs to simulate inheritance by implementing the interface's members.

**Static abstract and virtual members**
It's important to note that static virtual and static abstract methods in interfaces are resolved at compile time, 
unlike virtual or abstract methods in classes which are resolved at runtime through dynamic dispatch. 
The compiler uses the available type information at compile time to resolve calls to static virtual and static abstract methods.

**Interface inheritance**
interfaces do not allow the declaration of instance fields or instance auto-properties. 
This restriction is in place because interfaces are intended to define contracts and behaviors rather than containing state. 
While static fields are now allowed in interfaces, they are not associated with any specific instance and are shared among all implementing types.

