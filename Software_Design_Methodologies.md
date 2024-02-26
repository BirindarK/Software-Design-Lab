# Software Design Methodologies 

## Introduction to Design Strategies 

**Structured Design**: is a system design strategy that primarily about breaking down large problems into several well organised componenets, using a divide and conquer technique by solving the smaller components individually to solve the overall problem.

**Function Oriented Design**: is a system design strategy comprised of many functions (smaller sub-systems). These functions have the capability of performing significant task in the system. It is related to the Structured Design Strategy as it also implements the divide and conquer technique.

**Object Oriented Design**: is a system design strategy that works around the characteristics and entities rather than the functions involved in the system. Solutions using this design strategy revolve around the engagement of entities. The important concepts of object oriented design are: Objects, Classes, Abstraction, Encapsulation, Inheritance and Polymorphism. 


## Research into each Design Strategy

**1. What do we mean by *coupling* and *cohesion* when disscussing structured design?**

When discussing structured design coupling and cohesion are two key concepts used to measure the quality of a sofware's system design. 

**Coupling** is the degree of interdependence between software modules (whole programmes or applications). Coupling can either be high or low, where: 
High coupling - modules are closely connected, where changes in one module potentially affects the other modules.
Low coupling - modules are indepedent, where  changes in one module have little impact on other modules.

**Cohesion** is the degree to which elements within a module work together to fulfill a single, well-defined purpose. 
High cohesion - elements are closely related and focused on a single purpose. 
Low cohesion - elements are loosely related and serve multiple purposes.

**NB** Coupling and Cohesion are significant in determining the maintainability, scalability, and reliability of a software system. If there is high coupling and low cohesion it makes a system difficult to change and test. If there is low coupling and high cohesion it makes a system easier to maintain and improve.

**2.What is the difference between *top-down* and *bottom-up* design? Which best describes a function oriented design?**
The top-down and the bottom-up are design techniques that are used to approach any software engineering problem.

The top-down approach is known as the "divide and conquer" approach involving the design of the overall architecture and then breaking it down into smaller components. This method emphasizes a high-level view of the system and starts with the implementation details after the system's structure, interfaces, and interactions are defined. 

The bottom-up approach takes an opposite approaach to the top-down approach, where it starts with the smaller, self-contained components and then combines them to form the larger system. This method emphasizes code reusability
and focuses on the development of easily integrable components. 

In comparing the definitions of the function oriented design structure and each of the design techniques, I found that the top-down design approach best describes function oriented design, since it is defined as the "divide and conquer" approach that is used in function oriented design. 

**3.In which design methodology would a *class diagram* be most useful?**

Classes are one of the key concepts in Object Oriented Design (OOD). The class diagram can be useful in OOD as they are able to map out the structure of a system through modelling its classes, attributes, operations, and relationships between objects. Therefore, a class diagram would be most useful in OOD due to the nature of the methodology. 

**4.What are the *four pillars of object oriented programming*? Give a single-sentence description of each.**
The four pillars of Object Oriented Programming are: Inheritance, Encapsulation, Abstraction, Polymorphism. 

Inheritance (the sharing of information) - Allows for code to be adaptible and reusable as classes inherit methods and properties of another class.

Encapsulation (the grouping of information) - Keeps code organised and separated by using classes to contain codes related to a specific subject.

Abstraction (the hiding of information) - Hiding of internal details or processes from the user by creating classes to represent real world objects and their attributes.

Polymorphism (the redefining of information) - Allows for multiple methods with the same name to be implemented in a variety of ways, making the system more understandable, flexible, and maintainable.

**5.What is the *strategy pattern*? How would its implementation differ between a functional and object oriented system?**

The strategy design pattern is a behavioural design pattern, that allows you to dynamically change the behaviour of an object by encapsulating it into different design strategies. In simpler terms, it provides a way to extract the behaviour of an object into separate classes that can be swapped at runtime, allowing the object to be more flexible and reusable.

The strategy pattern is implemented in the functional system by using higher-order functions, where different functions are used to represent the strategies. This allows the functional system to handle different scenarios by applying different strategies through functional calls.

The strategy pattern is implemented in the object oriented system by defining a set of related algorithms or behaviours in separated classes, where each class is used to represent a strategy and implements a common interface. This allows the object oriented system to handle varying requirements by employing different strategies through applying the methods used by the common interface. 

Strategy Pattern in Object Oriented Design

**6.Imagine you are creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**

To create an adaptable and maintainable online payment system, I would suggest following an Object Oriented Design method. This is because using the four pillars of OOD (Abstraction, Encapsulation, Inheritance, and Polymorphism) to organise the system into objects with their own properties and behaviours, allows developers to create robust and maintainable code that can create a scalable online payment system that can be used in more than one sector, thus achieving its goal in gaining maximum market share.



