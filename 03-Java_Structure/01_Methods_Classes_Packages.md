# Methods, Classes and Packages

## Introduction

Methods, classes, and packages are the basic building blocks of every Java program. Understanding these concepts helps in writing organized, reusable, and maintainable code.

---

# Method

## Definition

A **method** is a block of code that performs a specific task. It is written once and can be called whenever required.

## Why do we use Methods?

- To avoid writing the same code multiple times.
- To make the program easier to read and maintain.
- To divide a large program into smaller, manageable parts.
- To improve code reusability.

## Syntax

```java
returnType methodName() {
    // Statements
}
```

## Example

```java
public static void greet() {
    System.out.println("Welcome to Java");
}
```

---

# Class

## Definition

A **class** is a blueprint (template) used to create objects. It contains variables (properties) and methods (behaviors).

## Why do we use Classes?

- To represent real-world objects.
- To organize related data and methods together.
- To support Object-Oriented Programming (OOP).

## Syntax

```java
class Student {

}
```

---

# Package

## Definition

A **package** is a collection of related classes and interfaces used to organize Java programs.

Packages help avoid naming conflicts and make programs easier to manage.

## Advantages of Packages

- Organizes Java classes.
- Improves code readability.
- Avoids class name conflicts.
- Makes code reusable.

## Common Java Packages

| Package | Purpose |
|---------|---------|
| java.lang | Basic Java classes (System, String, Math, Object) |
| java.util | Utility classes (Scanner, ArrayList, Collections) |
| java.io | Input and Output classes |
| java.net | Networking classes |

## Example

```java
import java.util.Scanner;
```

---

# Key Points

- A **method** is a block of code that performs a specific task.
- A **class** is a blueprint for creating objects.
- A **package** is a collection of related classes and interfaces.
- `Scanner` belongs to the **java.util** package.
- `System` belongs to the **java.lang** package.

---

# Interview Questions

### 1. What is a method?

A method is a block of code that performs a specific task and can be called whenever required.

### 2. What is a class?

A class is a blueprint used to create objects.

### 3. What is a package?

A package is a collection of related classes and interfaces used to organize Java programs.