# Java Design Patterns

## Introduction
This repository contains source code from book [Head First Design Patterns.](https://www.oreilly.com/library/view/head-first-design/0596007124/) Organised in convenient maven project for ease of compilation and packaging.

## Design Principals

### Design Principal 1
> Identify the aspects of your application that vary and separate them from what stays the same.  Here’s another way to think about this principle: take the parts that vary and encapsulate them, so that later you can alter or extend the parts that vary without affecting those that don’t.

### Design Principal 2
> Program to an interface, not an implementation.

### Design Principal 3
> Favour composition over inheritance

### Design Principal 4
> Strive for loosely coupled designs between objects that interact.

### Design Principal 5
> Classes should be open for extension, but closed for modification.

### Design Principal 6
> Depend upon abstractions. Do not depend upon concrete classes.

### Design Principal 7
> Principle of Least Knowledge -  talk only to your immediate friends.

### Design Principal 8
> The Hollywood Principle. Don’t call us, we’ll call you.

## [Creation Patterns](src/main/java/designpatterns/creational)
### [The Factory Method Pattern](src/main/java/designpatterns/creational/factory/pizzafm)
> Deﬁnes an interface for creating an object, but lets subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.

### [The Abstract Factory Pattern](src/main/java/designpatterns/creational/factory/pizzaaf)
> Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

### [The Singleton Pattern](src/main/java/designpatterns/creational/singleton)
> Ensures a class has only one instance, and provides a global point of access to it.

## [Structural Patterns](src/main/java/designpatterns/structural)
### [The Adapter Pattern](src/main/java/designpatterns/structural/adapter)
> Converts the interface of a class into another interface the clients expect.  Adapter lets classes work together that couldn’t otherwise because of incompatible interfaces.

### [The Facade Pattern](src/main/java/designpatterns/structural/facade)
> Provides a unified interface to a set of interfaces in a subsytem.  Facade defi nes a higherlevel interface that makes the subsystem easier to use.

### [The Composite Pattern](src/main/java/designpatterns/structural/composite)
> Allows you to compose objects into tree structures to represent part-whole hierarchies.  Composite lets clients treat individual objects and compositions of objects uniformly.

### [The Proxy Pattern](src/main/java/designpatterns/structural/proxy)
> Provides a surrogate or placeholder for another object to control access to it.

**Explanation**
> The Composite Pattern allows us to build structures of objects in the form of trees that contain both compositions of objects and individual objects as nodes. Using a composite structure, we can apply the same operations over both composites and individual objects.  In other words, in most cases we can ignore the differences between compositions of objects and individual objects.

### [The Decorator Pattern](src/main/java/designpatterns/structural/decorator)
> Attaches additional responsibilities to an object dynamically.  Decorators provide a flexible alternative to subclassing for extending functionality

## [Behavioral Patterns](src/main/java/designpatterns/behavioral)

### [The Strategy Pattern](src/main/java/designpatterns/behavioral/strategy)
> Deﬁnes a family of algorithms, encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently from clients that use it.

### [The Observer Pattern](src/main/java/designpatterns/behavioral/observer)
> Deﬁnes a one-to-many dependency between objects so that when one object changes state, all of its dependents are notiﬁed and updated automatically.

### [The Command Pattern](src/main/java/designpatterns/behavioral/command)
> Encapsulates a request as an object, thereby letting you parameterize other objects with different requests, queue or log requests, and support undoable operations.

### [The Template Method Pattern](src/main/java/designpatterns/behavioral/templatemethod)
> Defines the skeleton of an algorithm in a method, deferring some steps to subclasses.  Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm’s structure.

### [The Iterator Pattern](src/main/java/designpatterns/behavioral/iterator)
> Provides a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

**Explanation**
> Allows traversal of the elements of an aggregate without exposing the underlying implementation. It also places the task of traversal on the iterator object, not on the aggregate, which simplifies the aggregate interface and implementation, and places the responsibility where it should be.

**Explanation**
> Cohesion is a term you’ll hear used as a measure of how closely a class or a module supports a single purpose or responsibility. Head First OO Glue We say that a module or class has high cohesion when it is designed around a set of related functions, and we say it has low cohesion when it is designed around a set of unrelated functions.

### [The State Pattern](src/main/java/designpatterns/behavioral/state)
> Allows an object to alter its behavior when its internal state changes.  The object will appear to change its class.


## Resources
Links to various design pattern resources
- [Refactoring Guru Design Patterns.](https://refactoring.guru/design-patterns)