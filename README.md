# Low-Level Design (LLD) — System Design Roadmap

A structured, progressive learning path to master Low-Level Design concepts, object-oriented principles, design patterns, and real-world system modeling.

---

## Table of Contents

- [Overview](#overview)
- [Learning Process](#learning-process)
- [Roadmap](#roadmap)
  - [Phase 1 — Foundations](#phase-1--foundations)
  - [Phase 2 — Design Patterns](#phase-2--design-patterns)
  - [Phase 3 — Real-World LLD Problems](#phase-3--real-world-lld-problems)
  - [Phase 4 — Advanced Concepts](#phase-4--advanced-concepts)
- [Repository Structure](#repository-structure)
- [Progress Tracker](#progress-tracker)
- [Tech Stack](#tech-stack)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Low-Level Design (LLD) is the practice of **component-level software design** — translating high-level architectural decisions into concrete class structures, object relationships, design patterns, and maintainable code.

Where High-Level Design answers _"What are we building?"_, LLD answers _"How exactly do we build it?"_

This repository is a self-contained roadmap that covers foundational OOP principles, all major Gang of Four design patterns, and a curated set of real-world system design problems commonly asked in engineering interviews at product-based companies.

---

## Learning Process

### How to Use This Roadmap

This repository is designed as a **progressive, hands-on learning path**. Follow these principles:

#### 1. **Learn in Phase Order**

Complete phases sequentially. Each phase builds upon the previous one:

- **Phase 1** establishes the mental models needed for design
- **Phase 2** teaches reusable patterns built on strong foundations
- **Phase 3** applies patterns to realistic scenarios
- **Phase 4** bridges component design with production engineering

#### 2. **Understand Before Implementing**

For each topic:

1. Read the concept explanation
2. Study the provided diagrams and examples
3. Understand the trade-offs and when to use it
4. Then implement from scratch (without looking at reference code initially)

#### 3. **Code-First Learning**

- **Do not just read**. Write code for every pattern and problem
- Implement in your chosen language (Java, Python, or C++)
- Create unit tests to validate your implementation
- Refactor and optimize after it works

#### 4. **Real-World Context**

Connect theory to practice:

- For Phase 3 problems, start with requirements, not code
- Draw a class diagram before coding
- Identify which patterns apply and why
- Discuss trade-offs with peers or in design reviews

---

### Prerequisites and Setup

**What You Should Know Before Starting**

- **Basic Programming**: Comfortable with OOP concepts (classes, inheritance, interfaces)
- **Data Structures**: Familiarity with arrays, linked lists, trees, hash maps
- **Git**: Basic commands for cloning, committing, and pushing

**Setting Up Locally**

```bash
# 1. Clone this repository
git clone https://github.com/varunsahukar/System-Design-LLD-.git
cd System-Design-LLD-

# 2. Set up your language environment
# For Java: Ensure JDK 11+ and Maven are installed
# For Python: Ensure Python 3.8+ is installed
# For C++: Ensure C++17 compiler and CMake are installed

# 3. Navigate to a problem directory and start coding
cd 03-problems/parking-lot/
```

**Best Practices for This Repository**

- Create a **feature branch** for each problem you solve: `git checkout -b feature/solve-parking-lot`
- Commit incrementally as you make progress
- Push your work regularly to avoid data loss
- Compare your implementation with reference solutions after completing your own version
- Leave detailed comments in your code explaining design decisions

---

### Suggested Learning Timeline

**Recommended Pace: 12–16 Weeks** (assuming 5–10 hours per week)

| Phase   | Topics                            | Suggested Duration | Focus                                         |
| ------- | --------------------------------- | ------------------ | --------------------------------------------- |
| Phase 1 | Foundations (4 topics)            | 2–3 weeks          | Core concepts, mental models                  |
| Phase 2 | Design Patterns (16 patterns)     | 5–6 weeks          | One pattern every 2 days, code examples       |
| Phase 3 | Real-World Problems (15 problems) | 4–5 weeks          | One problem per 4–5 days, full implementation |
| Phase 4 | Advanced Concepts (5 topics)      | 1–2 weeks          | Integration, best practices, optimization     |

**Weekly Study Routine (Suggested)**

**Days 1–2**: Theory

- Read the concept/pattern documentation
- Study provided diagrams and class structures
- Understand the problem statement (for Phase 3)

**Days 3–5**: Implementation

- Design the solution (UML diagram or pseudocode)
- Write code from scratch
- Implement unit tests
- Compare with reference solution

**Days 6–7**: Reflection & Consolidation

- Refactor and optimize your code
- Write a brief summary in comments
- Discuss trade-offs and alternative approaches
- Mark progress in this README

---

### Tips for Success

**Active Learning Strategies**

1. **Teach Others**: Explain concepts to a peer or write a blog post
2. **Implement Variations**: Modify problems slightly to deepen understanding
   - Example: Add multi-threading to the Parking Lot system
   - Example: Add search filters to the Library system
3. **Code Reviews**: Review others' implementations and provide feedback
4. **Interview Simulation**: Time yourself solving Phase 3 problems (1–1.5 hours)
5. **Diagram First**: Always sketch class and sequence diagrams before coding

**Common Pitfalls to Avoid**

- ❌ Reading without coding → Passive learning leads to retention loss
- ❌ Rushing through phases → Weak foundations cause confusion later
- ❌ Ignoring SOLID principles → Code becomes unmaintainable
- ❌ Copying reference solutions directly → Misses learning opportunity
- ❌ Not testing your code → Missing edge cases and bugs

### Assessment Checkpoints

**Milestone 1: End of Phase 1** (Weeks 2–3)

- [ ] Can explain OOP principles with real-world examples
- [ ] Have created 2–3 UML diagrams from scratch
- [ ] Understand when and why to apply SOLID principles

**Milestone 2: Mid-Phase 2** (Week 4)

- [ ] Have implemented 8 creational and structural patterns
- [ ] Can identify patterns in existing codebases
- [ ] Understand trade-offs between similar patterns

**Milestone 3: End of Phase 2** (Week 6)

- [ ] Have implemented all 16 GoF patterns
- [ ] Can explain the difference between each behavioral pattern
- [ ] Comfortable combining multiple patterns in one system

**Milestone 4: Phase 3 Completion** (Week 10)

- [ ] Have fully implemented 8–10 real-world problems
- [ ] Each implementation includes unit tests
- [ ] Can explain pattern choices and trade-offs
- [ ] Solutions handle edge cases robustly

**Milestone 5: Capstone** (Week 12–16)

- [ ] Understand concurrency and thread safety in LLD
- [ ] Can apply clean code principles to large codebases
- [ ] Have written or reviewed refactoring documents
- [ ] Ready for system design interviews

---

## Roadmap

### Phase 1 — Foundations

Build a solid base in object-oriented thinking and modeling before moving to patterns or problems.

| Topic            | Description                                                          | Status |
| ---------------- | -------------------------------------------------------------------- | ------ |
| OOP Principles   | Encapsulation, Abstraction, Inheritance, Polymorphism                | [ ]    |
| SOLID Principles | SRP, OCP, LSP, ISP, DIP with examples                                | [ ]    |
| UML Diagrams     | Class, Sequence, Activity, and Use-case diagrams                     | [ ]    |
| Object Modeling  | Identifying classes, attributes, and relationships from requirements | [ ]    |

---

### Phase 2 — Design Patterns

Based on the Gang of Four (GoF) catalog. Each pattern includes intent, structure, and a coded example.

#### Creational Patterns

| Pattern          | Intent                                                                              | Status |
| ---------------- | ----------------------------------------------------------------------------------- | ------ |
| Singleton        | Guarantee a single instance across the application                                  | [ ]    |
| Factory Method   | Delegate instantiation to subclasses                                                | [ ]    |
| Abstract Factory | Create families of related objects without specifying concrete classes              | [ ]    |
| Builder          | Construct complex objects step by step, separating construction from representation | [ ]    |
| Prototype        | Create new objects by cloning an existing instance                                  | [ ]    |

#### Structural Patterns

| Pattern   | Intent                                                                   | Status |
| --------- | ------------------------------------------------------------------------ | ------ |
| Adapter   | Convert one interface into another that clients expect                   | [ ]    |
| Decorator | Attach additional responsibilities to objects dynamically                | [ ]    |
| Facade    | Provide a simplified interface to a complex subsystem                    | [ ]    |
| Composite | Compose objects into tree structures to represent part-whole hierarchies | [ ]    |
| Proxy     | Control access to another object through a surrogate                     | [ ]    |

#### Behavioral Patterns

| Pattern                 | Intent                                                                      | Status |
| ----------------------- | --------------------------------------------------------------------------- | ------ |
| Observer                | Define a one-to-many dependency so dependents update automatically          | [ ]    |
| Strategy                | Define a family of algorithms and make them interchangeable at runtime      | [ ]    |
| Command                 | Encapsulate a request as an object for parameterization and queuing         | [ ]    |
| State                   | Allow an object to alter its behavior when its internal state changes       | [ ]    |
| Iterator                | Access elements of a collection sequentially without exposing its structure | [ ]    |
| Chain of Responsibility | Pass a request along a chain of handlers until one handles it               | [ ]    |

---

### Phase 3 — Real-World LLD Problems

Each problem includes a requirements breakdown, class diagram, and full implementation.

| Problem                           | Key Patterns Applied           | Status |
| --------------------------------- | ------------------------------ | ------ |
| Parking Lot                       | OOP, State, Strategy           | [ ]    |
| ATM Machine                       | State Machine, Command         | [ ]    |
| Library Management System         | Relationships, SOLID           | [ ]    |
| Hotel Booking System              | Factory, Observer              | [ ]    |
| Chess Game                        | Composite, Strategy            | [ ]    |
| Elevator System                   | State, Chain of Responsibility | [ ]    |
| Ride-Sharing App (Uber/Ola)       | Observer, Strategy, Factory    | [ ]    |
| Food Delivery App (Swiggy/Zomato) | Builder, Observer, State       | [ ]    |
| E-Commerce Cart                   | Composite, Decorator           | [ ]    |
| Notification System               | Observer, Strategy             | [ ]    |
| LRU Cache                         | Design + Data Structures       | [ ]    |
| Rate Limiter                      | Token Bucket, Sliding Window   | [ ]    |
| Task Manager (Trello-like)        | Composite, State, Command      | [ ]    |
| Expense Splitter (Splitwise)      | Graph, SOLID                   | [ ]    |
| Movie Ticket Booking System       | Factory, State, Observer       | [ ]    |

---

### Phase 4 — Advanced Concepts

Topics that bridge clean design with production-grade engineering.

| Topic                    | Description                                             | Status |
| ------------------------ | ------------------------------------------------------- | ------ |
| Concurrency in LLD       | Thread safety, locks, and concurrent design patterns    | [ ]    |
| Clean Code Principles    | Naming conventions, function design, error handling     | [ ]    |
| Refactoring Techniques   | Identifying code smells and applying targeted refactors | [ ]    |
| Test-Driven Design (TDD) | Writing tests first to drive better LLD decisions       | [ ]    |
| LLD + HLD Integration    | How component design feeds into system architecture     | [ ]    |

---

## Repository Structure

```
lld-system-design/
|
|-- 01-foundations/
|   |-- oop-principles/
|   |-- solid-principles/
|   `-- uml-diagrams/
|
|-- 02-design-patterns/
|   |-- creational/
|   |-- structural/
|   `-- behavioral/
|
|-- 03-problems/
|   |-- parking-lot/
|   |-- atm/
|   |-- chess-game/
|   |-- ride-sharing/
|   `-- ...
|
`-- 04-advanced/
    |-- concurrency/
    |-- clean-code/
    `-- tdd/
```

Each problem folder follows a consistent structure:

```
problem-name/
|-- README.md          # Problem statement, requirements, and approach
|-- diagram.png        # UML class diagram
`-- src/               # Implementation
```

---

## Progress Tracker

| Phase                         | Total Topics | Completed | Progress |
| ----------------------------- | ------------ | --------- | -------- |
| Phase 1 — Foundations         | 4            | 0         | 0%       |
| Phase 2 — Design Patterns     | 16           | 0         | 0%       |
| Phase 3 — Real-World Problems | 15           | 0         | 0%       |
| Phase 4 — Advanced Concepts   | 5            | 0         | 0%       |
| **Total**                     | **40**       | **0**     | **0%**   |

Status convention used across all tables:

| Symbol | Meaning     |
| ------ | ----------- |
| [ ]    | Not started |
| [~]    | In progress |
| [x]    | Completed   |

---

## Tech Stack

| Category         | Tools                           |
| ---------------- | ------------------------------- |
| Primary Language | Java / Python / C++             |
| Diagram Tooling  | draw.io, PlantUML, Excalidraw   |
| Testing          | JUnit 5 (Java), pytest (Python) |
| Documentation    | Markdown                        |

---

## Resources

**Books**

- _Design Patterns: Elements of Reusable Object-Oriented Software_ — GoF (Gamma, Helm, Johnson, Vlissides)
- _Head First Design Patterns_ — Freeman & Robson
- _Clean Code_ — Robert C. Martin
- _Refactoring: Improving the Design of Existing Code_ — Martin Fowler

**Online**

- [Refactoring Guru — Design Patterns](https://refactoring.guru/design-patterns)
- [Grokking the Object-Oriented Design Interview — Educative](https://www.educative.io/courses/grokking-the-object-oriented-design-interview)
- [Source Making — Design Patterns](https://sourcemaking.com/design_patterns)

---

## Contributing

Contributions are welcome. If you want to add a new problem, improve an existing solution, or fix a diagram, please follow this workflow:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/add-snake-game-lld`
3. Commit your changes with a clear message.
4. Open a pull request with a description of what was added or changed.

Please ensure every new problem includes a `README.md`, a class diagram, and a working implementation with tests where applicable.

---

## Frequently Asked Questions (FAQ)

**Q: Should I learn all patterns before starting Phase 3 problems?**

A: Yes, it's recommended to complete Phase 2 first. The problems in Phase 3 combine multiple patterns, and having solid pattern knowledge makes them easier to understand and implement.

**Q: Can I skip patterns I already know?**

A: Yes, but ensure you understand each pattern deeply. Even if you've seen a pattern before, implementing it from scratch in this repository reinforces learning. Use your existing knowledge to move faster through those sections.

**Q: How long does each problem typically take to solve?**

A: Phase 3 problems typically take 4–8 hours to complete fully (design + implementation + testing + refactoring). Don't rush; quality implementation is more valuable than speed.

**Q: Should I look at reference solutions?**

A: Implement the problem first without looking at solutions. After completing your version, review reference solutions to learn alternative approaches and identify improvements.

**Q: Can I use different languages for different problems?**

A: Absolutely! This repository supports Java, Python, and C++. Mixing languages deepens your understanding of OOP concepts across different paradigms.

**Q: How do I know if my design is good?**

A: Your design is good if:

- It follows SOLID principles
- Classes have single, well-defined responsibilities
- Relationships between classes are clear and minimal
- It's easy to extend without modifying existing code
- Tests pass and edge cases are handled

**Q: Do I need to memorize all 16 design patterns?**

A: No, but you should understand their intent, trade-offs, and when to apply them. Practical experience (through implementation) makes patterns memorable naturally.

---

## License

This project is licensed under the [MIT License](./LICENSE).

---

_Maintained as an open learning resource for software engineers preparing for system design interviews or deepening their understanding of object-oriented design._
