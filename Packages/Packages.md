# Packages in Java

## Introduction

A **package** in Java is a namespace used to organize related classes, interfaces, enums, annotations, and sub-packages. It helps developers organize code into logical groups, making applications easier to develop and maintain.

---

# Why Do We Need Packages?

Packages provide several advantages:

- Organize related classes together.
- Avoid naming conflicts between classes.
- Improve code readability and maintainability.
- Support modular programming.
- Provide access protection.

---

# Types of Packages

Java provides two types of packages:

1. Built-in Packages
2. User-defined Packages

---

# 1. Built-in Packages

Built-in packages are predefined packages provided by Java. They contain ready-to-use classes and interfaces.

Some commonly used built-in packages are:

| Package | Purpose |
|----------|---------|
| `java.lang` | Basic language classes |
| `java.util` | Utility classes like Scanner, ArrayList, HashMap |
| `java.io` | Input and Output operations |
| `java.net` | Networking |
| `java.sql` | Database connectivity |

### Example

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
    }
}
```

---

# 2. User-defined Packages

A user-defined package is created by the programmer to organize their own classes.

### Syntax

```java
package packageName;
```

### Example

```java
package student;

public class Student {
    void display() {
        System.out.println("Hello");
    }
}
```

---

# Importing Packages

To use a class from another package, use the `import` keyword.

### Syntax

```java
import packageName.ClassName;
```

### Example

```java
import student.Student;
```

---

# Importing All Classes

To import all classes from a package:

```java
import java.util.*;
```

> **Note:** `*` imports all classes and interfaces from the package, **not methods**.

---

# Package Naming Conventions

Package names should:

- Be written in lowercase.
- Be meaningful.
- Follow reverse domain naming for large projects.

Examples:

```text
com.company.project
com.google.firebase
org.apache.commons
```

---

# Default Package

If no package is declared, the class belongs to the **Default Package**.

Example:

```java
public class Demo {

}
```

---

## Understanding the Example

### Example 1

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
    }
}
```

### Explanation

| Component | Type |
|----------|------|
| `java.util` | Package |
| `Scanner` | Class |
| `Main` | Class |
| `main()` | Method |
| `sc` | Object (Reference Variable) |
| `new Scanner(System.in)` | Object Creation |
| `System` | Class |
| `in` | Static Field |
| `System.in` | Input Stream Object |

---

### Example 2

```java
System.out.println("Hello, World!");
```

### Explanation

| Component | Type |
|----------|------|
| `System` | Class |
| `out` | Static Field (PrintStream Object) |
| `println()` | Method |

---

### Example 3

```java
Math.sqrt(25);
```

### Explanation

| Component | Type |
|----------|------|
| `Math` | Class |
| `sqrt()` | Static Method |

# Commonly Used Packages

| Package | Common Classes |
|----------|----------------|
| `java.lang` | System, Math, String |
| `java.util` | Scanner, ArrayList, HashMap |
| `java.io` | File, FileReader |
| `java.time` | LocalDate, LocalTime |
| `java.sql` | Connection, Statement |

---

# Advantages of Packages

- Better code organization.
- Prevents class name conflicts.
- Easier maintenance.
- Improves code reusability.
- Supports access control.

---


# Summary

- A package is used to organize related classes and interfaces.
- Java provides built-in and user-defined packages.
- The `import` keyword is used to access classes from another package.
- Package names are usually written in lowercase.
- Packages improve code organization and maintainability.

---

# Interview Questions

### 1. What is a package in Java?

A package is a namespace used to organize related classes, interfaces, enums, annotations, and sub-packages.

---

### 2. What are the types of packages?

- Built-in Packages
- User-defined Packages

---

### 3. What is the purpose of the `import` keyword?

The `import` keyword allows a class to use classes from another package.

---

### 4. What is the default package?

If a Java file does not contain a `package` declaration, it belongs to the Default Package.

---

### 5. What does `import java.util.*;` do?

It imports all classes and interfaces available in the `java.util` package.

---

### 6. Is `Scanner` a package or a class?

`Scanner` is a **class** in the `java.util` package.

---

### 7. Does `*` import methods?

No. It imports all classes and interfaces from the package, not methods.
