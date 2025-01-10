# Behavioral Patterns in TypeScript

This folder contains TypeScript implementations of various behavioral design patterns. Behavioral patterns focus on how objects interact and communicate with each other, ensuring flexibility and efficiency in the system design.

## Included Patterns

### 1. **Chain of Responsibility** (`chain-of-responsibility.ts`)
   - Provides a way to pass requests along a chain of handlers.
   - Each handler can either process the request or pass it to the next handler in the chain.

### 2. **Command** (`command.ts`)
   - Encapsulates a request as an object, thereby allowing for parameterization and queuing of requests.
   - Supports undoable operations.

### 3. **Iterator** (`iterator.ts`)
   - Provides a way to access elements of a collection sequentially without exposing the underlying representation.

### 4. **Mediator** (`mediator.ts`)
   - Defines an object that encapsulates how a set of objects interact.
   - Promotes loose coupling by preventing objects from referring to each other explicitly.

### 5. **Memento** (`memento.ts`)
   - Captures and restores an object's state without violating encapsulation.
   - Useful for implementing undo/redo functionality.

### 6. **Observer** (`observer.ts`)
   - Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified.

### 7. **State** (`state.ts`)
   - Allows an object to alter its behavior when its internal state changes.
   - The object appears to change its class.

### 8. **Strategy** (`strategy.ts`)
   - Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
   - Lets the algorithm vary independently from clients that use it.

### 9. **Template Method** (`template-method.ts`)
   - Defines the skeleton of an algorithm in a method, deferring some steps to subclasses.
   - Lets subclasses redefine certain steps of an algorithm without changing its structure.

### 10. **Visitor** (`visitor.ts`)
   - Represents an operation to be performed on elements of an object structure.
   - Allows you to add further operations to the structure without modifying its elements.