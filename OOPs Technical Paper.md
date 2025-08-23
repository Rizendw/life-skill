# Object Oriented Programming (OOPs)

## Abstract
Object-Oriented Programming (OOPs) is one of the most widely used programming paradigms in modern software development. It organises programs into reusable objects that combine data and behaviour. This paper provides a foundational overview of OOPs, detailing its core principles—encapsulation, inheritance, polymorphism, and abstraction. It explores the practical implementation of these concepts through simple examples and discusses the continued relevance and criticisms of OOPs in modern software engineering. The objective is to establish a clear, conceptual understanding of why OOP remains a critical tool for managing complexity in large-scale software projects.

## Introduction
- As software systems grow in size and complexity, the need for organised, maintainable, and scalable code becomes inevitable. The procedural programming paradigm, which structures code as a sequence of instructions, often struggles with this complexity OOPs is a programming model that is based on the concept of "objects" Instead of writing code as a series of procedures, OOPs focuses on objects that represent entities in the real world, such as students, books, or bank accounts.
- Languages like Java, C++, Python, and C# are commonly used for OOPs. It helps in writing modular, reusable, and maintainable code.
- Java is considered a partial OOPs language, while languages like Python are considered fully OOPs.

## Key concept and pillars of OOPs

### 1. Class
- A class is a blueprint for creating objects.
- Example: A "Car" class may have attributes like colour and speed, and methods like start() or brake().

### 2. Objects
- An object is an instance of a class.
- If "Car" is a class, then a "Porsche Silver 911" is an object.

### 3. Abstraction
- It is the concept of hiding complex implementation details and showing only the essential features of an object.
- It focuses on what an object does instead of how it does it. This is typically achieved using abstract classes and interfaces.
- Example: A "Car" interface may allow accelerate() and brake() methods without showing how they are implemented.

### 4. Encapsulation
- Wrapping data members(variables) and methods(functions) together into a single unit.
- Protects data by allowing controlled access through getters and setters.
- By using access modifiers, this ensures data security by preventing direct modification from outside the class.

### 5. Inheritance
- The ability of one class to acquire properties and methods of another class.
- To promote code reusability. Common logic can be written once in a base class and then extended or specialised by derived classes, eliminating redundant code.
- Example: A "SuperCar" class can inherit from the "Car" class.

### 6. Polymorphism
- Polymorphism means ‘many forms. The ability of different classes to provide different implementations of the same method.
- It is most commonly implemented through method overriding and method overloading.
- A start() method may be defined differently in "ICE", "Hybrid" and "Electric" classes.

## Advantages of OOPs
- Code reusability through inheritance.
- Better organisation and readability.
- Easier maintenance and debugging.
- Supports modular programming.
- Closer representation of real-world entities.

## Applications of OOPs
- Software Development: Used in building desktop, mobile and web applications.
- Game Development: Objects represent players, enemies, and items.
- Database Systems: Entities are modelled as classes and objects.
- Simulation & AI: Helps in creating realistic models.

## Relevance and Criticisms in Modern Development
OOPs is not a silver bullet. Its relevance is strongest in large, complex applications like graphical user interfaces (GUIs), game development (where game entities are natural objects), and enterprise software. Frameworks like Java's Spring or .NET are built on OOP principles.

### However, OOPs faces valid criticisms:
- Over-Engineering: Simple programs can become unnecessarily complex with deep inheritance hierarchies.
- Tight Coupling: Poorly designed class hierarchies can lead to tightly coupled code, making changes difficult.
- The Rise of Alternatives: Paradigms like Functional Programming (FP) are gaining popularity for their strengths in concurrent processing and data transformation pipelines, often leading to more predictable and testable code.
- Modern development often adopts a multi-paradigm approach. Languages like JavaScript, Python, and C# allow developers to blend OOP with functional and procedural styles, using the right tool for the right job.

## Conclusion
The OOPs principle has transformed the way we design and develop software. Focusing on objects provides a powerful way to organise complex programs into manageable blocks. Its power lies in providing a mental model and a set of tools like encapsulation, inheritance, polymorphism, and abstraction, to manage complexity by mirroring the real world.
While it has its critics and is often used alongside other paradigms, understanding OOPs is essential for any developer aiming to build robust, scalable, and maintainable software systems. The key to effective OOPs is applying its principles judiciously to reduce complexity, not introduce it.

## References
1. Documentation [W3Schools](w3schoolsua.github.io/hyperskill/OOPs-intro_en.html#gsc.tab=0)
2. [GFG](https://www.geeksforgeeks.org/cpp/object-oriented-programming-in-cpp/)
3. Notes [CodeWithHarry](https://www.codewithharry.com/tutorial/cpp-OOPs-basics)
4. YouTube Video [CodeWithHarry ](https://www.youtube.com/@CodeWithHarry)
5. Compilation [DeepSeek](https://chat.deepseek.com/)