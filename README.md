# Design Principles Practice

Hands-on practice implementing SOLID principles in C# (multi-language support planned)

## Reference(s)

- [SOLID Principles - The Basics](https://www.youtube.com/watch?v=HLFbeC78YlU)
- [SOLID Principles by Uncle Bob](https://www.youtube.com/watch?v=zHiWqnTWsn4)

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
