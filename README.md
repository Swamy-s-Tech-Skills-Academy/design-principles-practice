# Design Principles Practice

Hands-on practice implementing SOLID principles in C# (multi-language support planned)

## Learning Path

### 🧱 **Phase 1: Object-Oriented Foundations**

Start with core OOP concepts before diving into SOLID.

1. [Object-oriented Programming in C#](https://app.pluralsight.com/library/courses/c-sharp-10-object-oriented-programming/table-of-contents) - Pluralsight
2. [Object-oriented Programming in Java](https://app.pluralsight.com/library/courses/java-se-17-object-oriented-programming/table-of-contents) - Pluralsight
3. [Fundamentals of Object Oriented Programming in Java](https://app.pluralsight.com/library/courses/fundamentals-object-oriented-programming-java/table-of-contents) - Pluralsight
4. [Advanced Perspective of Classes and Object-Oriented Programming in Python](https://app.pluralsight.com/ilx/advanced-perspective-of-classes-and-object-oriented-programming-in-python/table-of-content) - Pluralsight

### 🧠 **Phase 2: Design Principles & SOLID Introduction**

Now that you understand OOP, explore design principles and SOLID.

5. [SOLID Principles - The Basics](https://www.youtube.com/watch?v=HLFbeC78YlU) - YouTube
6. [SOLID Principles by Uncle Bob](https://www.youtube.com/watch?v=zHiWqnTWsn4) - YouTube
7. [Object-oriented Design with C#](https://app.pluralsight.com/library/courses/c-sharp-10-object-oriented-design/table-of-contents) - Pluralsight

### 🛠️ **Phase 3: Applying SOLID in Practice**

Learn how to apply SOLID principles in real-world C# and Java projects.

8. [SOLID Principles for C# Developers](https://app.pluralsight.com/library/courses/csharp-solid-principles/table-of-contents) - Pluralsight
9. [SOLID Software Design Principles in Java 8](https://app.pluralsight.com/library/courses/solid-software-design-principles-java/table-of-contents) - Pluralsight
10. [Mastering Object-oriented Programming in Java 8](https://app.pluralsight.com/library/courses/object-oriented-programming-java/table-of-contents) - Pluralsight

### 🔧 **Phase 4: Refactoring with SOLID**

Refactor legacy codebases using SOLID principles.

11. [Refactoring to SOLID C# Code](https://app.pluralsight.com/library/courses/refactoring-solid-c-sharp-code/table-of-contents) - Pluralsight
12. [Refactoring to SOLID Java](https://app.pluralsight.com/library/courses/java-se-17-refactoring-solid-code/table-of-contents) - Pluralsight

## SOLID Acronym

- **S** - Single Responsibility Principle (SRP)
- **O** - Open/Closed Principle (OCP)
- **L** - Liskov Substitution Principle (LSP)
- **I** - Interface Segregation Principle (ISP)
- **D** - Dependency Inversion Principle (DIP)

| Principle                     | Description                                   | Benefit                     |
| ----------------------------- | --------------------------------------------- | --------------------------- |
| **S** - Single Responsibility | One class, one job                            | Easier to maintain and test |
| **O** - Open/Closed           | Open for extension, closed for modification   | Safe feature addition       |
| **L** - Liskov Substitution   | Subtypes must be substitutable for base types | Reliable inheritance        |
| **I** - Interface Segregation | Many specific interfaces vs one general       | Reduced coupling            |
| **D** - Dependency Inversion  | Depend on abstractions, not concretions       | Flexible architecture       |

---

## Folder Structure

```text
design-principles-practice/
├── LICENSE
├── README.md
├── docs/
│   └── images/
├── src/
│   └── csharp/
│       └── solid-principles/
│           ├── dependency-inversion/
│           ├── interface-segregation/
│           ├── liskov-substitution/
│           ├── open-closed/
│           └── single-responsibility/
└── tests/
    └── csharp/
```
