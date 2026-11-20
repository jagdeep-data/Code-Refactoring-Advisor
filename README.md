# Code Refactoring Advisor

An interactive browser-based static code analysis tool that detects code smells, computes software quality metrics, and generates refactoring suggestions for improving maintainability and code quality.

## Project Overview

Code Refactoring Advisor is a single-page web application designed to help developers and students analyze source code quality using software engineering principles. The system performs static code analysis, computes Halstead metrics, detects common code smells, and provides actionable refactoring recommendations with before/after comparisons.

The project focuses on improving code maintainability, modularity, readability, and software quality while also serving as an educational tool for understanding software metrics and refactoring techniques.

---

# Features

- Static code analysis for Python, Java, and C programs
- Halstead software metrics computation
- Maintainability Index (MI) calculation
- Detection of 7 major code smells:
  - Long Method
  - God Class
  - Dead Code
  - Long Parameter List
  - Duplicate Code
  - Magic Numbers
  - Deeply Nested Code
- Interactive dashboard visualization
- Before/After refactoring suggestions
- PDF and HTML report export
- Syntax highlighting for code diffs
- Browser-based execution with no server dependency

---

# Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- jsPDF
- highlight.js

---

# Software Engineering Concepts Implemented

- Static Code Analysis
- Software Metrics
- Code Smell Detection
- Refactoring Techniques
- Modular Architecture
- UML Modelling
- Black Box Testing
- White Box Testing
- Maintainability Analysis

---

# Project Architecture

The application consists of the following major modules:

- `tokeniser.js`
  - Tokenizes source code and generates operator/operand maps

- `halstead.js`
  - Computes Halstead metrics including Volume, Difficulty, Effort, and Maintainability Index

- `smellDetector.js`
  - Detects rule-based code smells

- `refactorAdvisor.js`
  - Generates refactoring recommendations and before/after suggestions

- `scoreEngine.js`
  - Computes overall code quality score

- `reportGenerator.js`
  - Exports analysis reports as PDF or HTML

- `config/smellRules.json`
  - Stores configurable smell detection rules

---

# Metrics Computed

The system computes:

- Program Vocabulary
- Program Length
- Volume (V)
- Difficulty (D)
- Effort (E)
- Maintainability Index (MI)

---

# Refactoring Techniques Used

- Extract Method
- Replace Magic Number with Constant
- Modularization
- Lazy Rendering
- Memoization
- Single Responsibility Principle (SRP)

---

# Testing Performed

## Black Box Testing
- Equivalence Class Partitioning
- Boundary Value Analysis
- Decision Table Testing

## White Box Testing
- Path Testing
- Data Flow Testing

---

# Key Highlights

- Fully browser-based implementation
- No backend or server dependency
- Supports multiple programming languages
- Interactive and educational dashboard
- Modular and maintainable architecture
- Exportable analysis reports

---

# Future Enhancements

- AI-based refactoring suggestions
- Additional programming language support
- Cloud integration
- Real-time collaborative analysis
- Advanced AST-based parsing
- IDE integration

---

# How to Run

1. Clone the repository

```bash
git clone git clone https://github.com/jagdeep-data/Code-Refactoring-Advisor.git
```

2. Open the project folder

3. Run `index.html` in a browser

---

# Author

Jagdeep Singh
B.Tech CSE 

---

# References

- IEEE Std 830-1998
- Halstead Software Science
- Refactoring by Martin Fowler
- Software Engineering Principles
