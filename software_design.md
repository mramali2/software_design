# Software Design

## What do we mean by coupling and cohesion when discussing structured design?

Coupling refers to how well connected  different software modules are. High coupling indicates modules that are closely connected and affect one another, whereas low coupling indicates independent modules which do not impact one another.
Cohesion refers to the extent that elements within a module work together in order to carry out a single purpose. High cohesion indicates elements that work together closely for a single purpose, whereas low cohesion indicates elements that are loosely related and serve multiple purposes.

## What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

In top down design the design starts with a high-level overview of the system as a whole. This is then divided into the smaller sub sections of the system with increasing detail.
In bottom up design the system is broken down into individual detailde parts. These are then linked together to build larger components, until the complete system is designed. 
Function orientated design describes a top down approach.

## In which design methodology would a class diagram be most useful?

A class diagram is most useful in object oriented design, as it clearly maps out each individual class and operation, and shows their relationships with one another.

## What are the four pillars of object oriented programming? Give a single-sentence description of each.

Encapsulation - the internal representation of an object is hidden from view outside the object's definition by restricting access to accessors and mutators.

Abstraction - is a concept which is not associated  with a particular instance. Abstract classes show the intent of a class rather than their actual implementation.

Inheritance - shows an 'is-a' or 'has-a'  relationship between objects, and results in dervies classses, subclasses or child classes.

Polymorphism - describes one name, many form. This can be achieved throguh overloading in static polymorphism and overriding in dynamic polymorphism.

## What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

Strategy pattern is a behvaioural design pattern which allows you to dynamically change the behaviour of an object. An object is able to choose from multiple algorithms at runtime. In a functional system, strategy pattern is implemented with higher-order funcitons, not through classes. The function accepts a particular strategy and exectures it. Whereas in an object oriented system, context classes would have reference to a strategy interface, which can switch between different strategies in implementation.

## Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I would select an object oriented design for a payment system that needs to work well for various use cases. The modular nature of OOP will allow you to easily expand your payment system as different sectors are introduced, without needing to change the entire system.

