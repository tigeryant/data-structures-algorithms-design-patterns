## Algorithms

### Insertion sort
Insertion sort is a simple sorting algorithm that builds the final sorted array one item at a time. This algorithm runs in quadratic time, and can be used when n is low (where n is the number of items to be sorted). Analogous to sorting a card deck with both hands.

</br>

## Data structures

### Stack
* Stack data structure implemented in PHP - functions include: `isEmpty()`, `size()`, `topElement()`, `push()` and `pop()`.
* Stack data structure implemented in Python - functions include: `isEmpty()`, `size()`, `topElement()`, `push()` and `pop()`.

### Queue
Queue data structure implemented in PHP - functions include: `isEmpty()`, `size()`, `frontElement()`, `rearElement()`, `enQueue()` and `deQueue()`.

</br>

## Design patterns

### Singleton
Naive implementation of a singleton in Python that makes use of metaclasses. This is a naive implementation because it does not behave correctly in a multi-threaded environment - that is, multiple threads can call the creation method simultaneously and get several instances of Singleton class.

### Factory method
Basic implementation of the factory method in Python. The user is prompted at runtime to decide which object they want to instantiate. The responsibility of instantiating a concrete class (`Student` or `Teacher`) is delegated to the `PersonFactory` class. `Teacher` and `Student` both implement the `IPerson` interface, which ensures that each of them implement the `person_method()`.
