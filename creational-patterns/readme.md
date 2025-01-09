# Creational Design Patterns in TypeScript

This repository contains implementations of various creational design patterns in TypeScript. Creational patterns are used to define the process of object creation, abstracting the instantiation logic, and making the code more flexible and reusable.

## Patterns Included

### 1. Abstract Factory
File: `abstract-factory.ts`

The **Abstract Factory** pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes.

#### Key Features:
- Encapsulates object creation logic.
- Ensures consistency in the objects that are created together.

#### Use Cases:
- When the system needs to be independent of how its objects are created.
- When you want to create families of related objects.

---

### 2. Builder
File: `builder.ts`

The **Builder** pattern separates the construction of a complex object from its representation, allowing the same construction process to create different representations.

#### Key Features:
- Focuses on step-by-step object construction.
- Useful for constructing objects with many optional fields or configurations.

#### Use Cases:
- When creating complex objects with numerous configurations.
- When the construction process needs to be reusable across different types of objects.

---

### 3. Factory Method
File: `factory-method.ts`

The **Factory Method** pattern defines an interface for creating an object but allows subclasses to alter the type of objects that will be created.

#### Key Features:
- Provides a single method to create objects.
- Promotes loose coupling by delegating object instantiation to subclasses.

#### Use Cases:
- When a class cannot anticipate the type of objects it needs to create.
- When you want to provide a hook for subclasses to specify the objects to be created.

---

### 4. Prototype
File: `prototype.ts`

The **Prototype** pattern creates new objects by copying an existing object, known as the prototype.

#### Key Features:
- Reduces the cost of creating objects by reusing existing instances.
- Allows for object customization without relying on inheritance.

#### Use Cases:
- When creating objects is expensive or resource-intensive.
- When you want to avoid creating a hierarchy of factory classes.

---

### 5. Singleton
File: `singleton.ts`

The **Singleton** pattern ensures a class has only one instance and provides a global point of access to it.

#### Key Features:
- Restricts instantiation of a class to a single object.
- Useful for shared resources like configuration, logging, etc.

#### Use Cases:
- When you need exactly one instance of a class globally.
- When the instance needs to be shared across multiple parts of the application.

---

