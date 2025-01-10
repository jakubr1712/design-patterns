# Structural Design Patterns in TypeScript

This repository contains implementations of common **Structural Design Patterns** in TypeScript. Structural patterns are design patterns that ease the design by identifying a simple way to realize relationships among entities. Each file provides a practical example of how to use a specific pattern.

## Patterns Overview

### 1. **Adapter** (`adapter.ts`)
The Adapter pattern bridges the gap between two incompatible interfaces. It allows objects with incompatible interfaces to collaborate by converting one interface into another.

### 2. **Bridge** (`bridge.ts`)
The Bridge pattern separates an abstraction from its implementation, allowing them to vary independently. This is useful for managing changes in both abstraction and implementation hierarchies.

### 3. **Composite** (`composite.ts`)
The Composite pattern composes objects into tree-like structures to represent part-whole hierarchies. It enables clients to treat individual objects and compositions of objects uniformly.

### 4. **Decorator** (`decorator.ts`)
The Decorator pattern dynamically adds new behavior to objects without altering their structure. It provides a flexible alternative to subclassing for extending functionality.

### 5. **Facade** (`facade.ts`)
The Facade pattern provides a simplified interface to a larger body of code, making the subsystem easier to use and reducing dependencies on the underlying implementation.

### 6. **Flyweight** (`flyweight.ts`)
The Flyweight pattern minimizes memory usage by sharing as much data as possible between similar objects. It is useful for managing a large number of fine-grained objects efficiently.

### 7. **Proxy** (`proxy.ts`)
The Proxy pattern provides a placeholder or surrogate for another object to control access to it. This can include adding functionality like lazy initialization, access control, or logging.
