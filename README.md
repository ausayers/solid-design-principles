# Solid Design Principles

An exploration of the SOLID design principles using the C++ programming language. 

## Why Be Concerned About Design?

Software is often very complex, but by utilizing Object Oriented Analysis and Design (OOAD) principles like SOLID we can:

- Deal with complexity by using abstraction and a "dive-and-conquer" approach.

- Manage changes to software without having to refactor existing functionality.

- Provide functional, simple, and efficient code.

## Symptoms of Bad Designs

Without utilzing OOAD principles like SOLID, your software can end up:

- **Rigid** - *Rigidity* is the tendency for software to be difficult to change, even in simple ways. 

- **Fragile** - *Fragility* is the tendency of the software to break in many places every time it is changed. This is also referred to as being brittle. 

- **Immobile** - *Immobility* is the inability to reuse software from other projects or from parts of the same project. 

## What is SOLID Design?

The SOLID design principles are five principles intended to make object-oriented designs more understandable, flexible, and maintainable. They were first introduced in 2000 by American software engineer Robert C. Martin, and it has become one of the most widespread set of design principles in the software engineering industry. The SOLID principles are:

- **S**ingle-responsibility principle

- **O**pen-closed principle

- **L**iskov substitution principle

- **I**nterface segregation principle

- **D**ependency inversion principle



#### Single-Responsibility Principle

The Single-Responsibility Principle states that **a class should only have one responsibility**. A *responsibility* can be defined as a reason for change. Therefore, *there should never be more than one reason for a class to change.*



#### Open-Closed Principle

The Open-Closed Principle states that **software entities (classes, structs, functions, etc.) should be open for extension and closed for modification.** This means that *classes and functions should be designed in a way that when a new functionality is needed, you don't have to modify any existing code but rather write new code that extends on the existing code base. *



#### Liskov Substitution Principle

The Liskov Substitution Principle states that **a child class should never break the parent class's type definitions.** Therefore, *a class should be able to be replaced by any of its subclasses in all practical usage scenarios*. 



#### Interface Segregation Principle

The Interface Segregation Principle states that **many client specific interfaces (e.g., sub-classes) are better than one general purpose interface (e.g., a parent-class).** This design principle can be acomplished by implementing inheritance. *Inheritance is when a class derives from another class.* You supply one general-interface parent class, and utilize a child class that inherits all the public and protected properties and methods from the parent class and has its own unique properties and methods. 



#### Dependency Inversion Principle

The Dependency Inversion Principle consists of two distinct statements:

- High-level modules hsould not depend on low-level modules. Buth should depend on abstractions

- Abstractions should not depend on details. Details should depend on abstractions.

In essence, this principle aims to reduce coupling (*the degree of interdependence between modules*). This is done by introducing abstractions like interfaces so the classes do not directly depend on each other. 


