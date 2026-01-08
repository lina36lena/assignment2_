Assignment 2 – OOP


1. Instruction
This project is a demonstration of basic Object-Oriented Programming principles using cultural objects.
The main goal is to create a system where artworks, artists, and galleries are represented as objects, and their properties can be compared, searched, filtered, and sorted.
The project also demonstrates how abstraction, encapsulation, inheritance, and polymorphism work together in practice.

Implemented concepts:
- Data abstraction using an abstract base class CulturalObject
- Encapsulation through private fields and public methods
- Inheritance by extending the base class
- Polymorphism via overridden getScore() methods
- Data pool management using ArrayList
- Searching, filtering and sorting of objects
- Overriding toString(), equals() and hashCode() methods

## OOP Concepts Demonstrated
- **Abstraction:** The abstract class `CulturalObject` defines common properties and behavior for all objects without specifying the details.
- **Encapsulation:** All object fields are private and accessed only through getter and setter methods, protecting the data.
- **Inheritance:** `Artworks`, `Artist`, and `Gallery` extend `CulturalObject`, reusing common properties and methods.
- **Polymorphism:** The method `getScore()` is implemented differently for each class, but can be called in the same way on any object.


Data Management
All objects are stored in a single data pool (ArrayList<CulturalObject>), which allows unified processing.
          The program can perform:
Search (e.g., by name)
Filter (e.g., score > 50)
Sort (by score or importance)


Demonstration in Main;
Main.java creates multiple objects of different types.
Prints all objects with their information.
Shows comparison of objects using their calculated score or popularity.
Demonstrates filtering, searching, and sorting in a practical example.


Project Goal

The goal of this project is to demonstrate how OOP principles work together in practice, and how collections can be used to manage and process objects efficiently.
It also shows how abstraction, inheritance, encapsulation, and polymorphism make the program organized, reusable, and easy to maintain
