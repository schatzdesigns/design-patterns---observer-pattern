# Design Patterns in Object Oriented Programming

# Observer Pattern

From [Wikipedia](https://en.wikipedia.org/wiki/Observer_pattern):
The observer pattern is a software design pattern in which an object, called the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

It is mainly used to implement distributed event handling systems, in "event driven" software. 

#### What problems can the Observer design pattern solve?
The Observer pattern addresses the following problems:

- A one-to-many dependency between objects should be defined without making the objects tightly coupled.
- It should be ensured that when one object changes state an open-ended number of dependent objects are updated automatically.
- It should be possible that one object can notify an open-ended number of other objects.

Defining a one-to-many dependency between objects by defining one object (subject) that updates the state of dependent objects directly is inflexible because it couples the subject to particular dependent objects. Tightly coupled objects are hard to implement, change, test, and reuse because they refer to and know about (how to update) many different objects with different interfaces.

#### What solution does the Observer design pattern describe?
- Define **Subject** and **Observer** objects.
- so that when a subject changes state, all registered observers are notified and updated automatically.

### [Branch without-observer-pattern](https://github.com/schatzdesigns/design-patterns---observer-pattern/tree/without-observer-pattern)
Shows the code without the implementation of the Observer Pattern.

### [Branch with-observer-pattern](https://github.com/schatzdesigns/design-patterns---observer-pattern/tree/with-observer-pattern)
Shows the code with the implementation of the Observer Pattern.
