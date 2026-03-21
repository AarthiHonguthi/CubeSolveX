# 🧊 CubeState Explorer

A Rubik’s Cube solver built to demonstrate how real-world problems can be modeled, decomposed, and solved using core computer science principles, object-oriented design, and search algorithms.

---

## Overview

This project explores how a physical object like a Rubik’s Cube can be transformed into a computational model. It focuses on breaking down a complex system into manageable components and solving it using algorithmic strategies commonly used in Artificial Intelligence.

---

## Key Learnings

### Modeling Real-World Problems
- Transformed a physical Rubik’s Cube into a structured computational representation.
- Designed abstractions that allow the cube to be manipulated programmatically.

### Problem Decomposition
- Broke down the complete solver into smaller, independent components:
  - Cube representation
  - Solver logic
- Applied modular design to improve clarity and scalability.

---

## Object-Oriented Design

Implemented strong OOP principles throughout the project:

- **Classes and Objects**  
  Represented cube states, moves, and solver logic.

- **Inheritance**  
  Created reusable base classes such as:
  - Rubik’s Cube Base Class
  - Pattern Database Base Class

- **Abstraction & Virtual Functions**  
  Defined abstract behaviors and extended them through derived classes.

- **Operator Overloading**  
  Enabled intuitive manipulation of cube states.

---

## Algorithms and AI Concepts

### Pathfinding Algorithms
Applied classical search algorithms to solve the cube:

- **BFS (Breadth-First Search)**
- **DFS (Depth-First Search)**
- **IDDFS (Iterative Deepening DFS)**
- **IDA\*** (Iterative Deepening A*)

These algorithms demonstrate how search techniques can solve structured state-space problems.

---

### Heuristic Search

- Implemented **A\*** and **IDA\*** for optimized solving.
- Built **Pattern Databases** to improve heuristic accuracy.
- Used heuristics to significantly reduce search space and computation time.

---

## Advanced Concepts

### Custom Data Structures
- Used `unordered_map` with custom objects.
- Designed **custom hash functions** for efficient state lookup.

### Memory Optimization
- Leveraged **bit manipulation** to store cube states compactly.

### File Handling
- Implemented functionality to **save and load pattern databases**.

---

## Black Box Abstraction

Introduced the concept of **Black Boxing**:

- Designed components (like the Permutation Indexer) where:
  - Input is provided
  - Output is expected
  - Internal implementation is abstracted away

This improves modularity and usability.

---

## Conclusion

This project demonstrates how:
- Complex real-world systems can be modeled in software
- Large problems can be broken into smaller, manageable parts
- Core algorithms and data structures can be applied to solve AI-related challenges
- Clean architecture and OOP principles lead to scalable and maintainable systems

---