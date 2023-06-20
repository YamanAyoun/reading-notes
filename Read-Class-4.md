
**Object-Oriented Programming:** (OOP) is a programming approach that revolves around objects, which are instances of classes. OOP imitates real-world entities by representing them as objects with specific properties and behaviors. Classes serve as blueprints for creating objects, defining their structure and behavior.

**Classes:** is a blueprint or template that defines the properties, methods, and behavior that objects of that class will have. It specifies the structure and behavior of the objects and serves as a blueprint for creating instances (objects) of that class.

**Constructors:** are special methods found within a class, responsible for initializing objects during their creation. They establish the requirements and initial state of an object.

**Properties:** in C# allow classes to expose a public way to get and set values while hiding the implementation details. They consist of get and set accessors, where the get accessor retrieves the property value and the set accessor assigns a new value.

Properties can be read-write (having both get and set accessors), read-only (having only a get accessor), or write-only (having only a set accessor). The accessibility of the accessors can be controlled to restrict access if needed.

The value keyword is used in the set or init accessor to represent the value being assigned. It allows you to perform validation or additional logic before assigning the value.

**Garbage collection:** is an automatic memory management feature in the common language runtime (CLR) that eliminates the need for manual memory allocation and deallocation in languages like C#. It simplifies memory management for developers by automatically tracking and releasing memory that is no longer in use.

Garbage collection is an automatic memory management feature in the CLR that eliminates the need for manual memory allocation and deallocation. It simplifies memory management for developers by automatically tracking and releasing unused memory.

The key points about garbage collection are:

It prevents memory leaks and accessing freed memory.
Memory is divided into the stack and the managed heap.
Garbage collection occurs when certain conditions are met.
Objects are allocated on the managed heap and organized into generations.
The garbage collection process involves marking live objects and reclaiming memory.
Finalization allows objects to perform cleanup operations before collection.
Developers have limited control over the garbage collector's behavior.


