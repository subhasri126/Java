# Java Program Structure

## Introduction

Every Java program follows a specific structure. Understanding this structure helps in writing, reading, and maintaining Java programs effectively.

---

# Basic Structure of a Java Program

A Java program generally consists of the following components:

1. Package Declaration (Optional)
2. Import Statements (Optional)
3. Class Declaration
4. main() Method
5. Program Statements

---

# Structure of a Java Program

```java
package mypackage;      // Optional

import java.util.Scanner;   // Optional

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello, World!");

    }

}
```

---

# Components of a Java Program

## 1. Package Declaration

A package declaration specifies the package to which the class belongs.

Example:

```java
package mypackage;
```

---

## 2. Import Statement

The import statement is used to access classes from another package.

Example:

```java
import java.util.Scanner;
```

---

## 3. Class Declaration

Every Java program must contain at least one class.

Syntax:

```java
public class Hello {

}
```

> **Note:** If the class is declared as `public`, the file name must be the same as the class name.

Example:

```
File Name : Hello.java
Class Name : Hello
```

---

## 4. main() Method

The `main()` method is the entry point of every Java application. The JVM starts executing the program from this method.

Syntax:

```java
public static void main(String[] args) {

}
```

---

## 5. Program Statements

The executable statements are written inside the `main()` method.

Example:

```java
System.out.println("Hello, World!");
```

---

# Curly Braces `{ }`

Curly braces define the beginning and ending scope of a class or method.

Example:

```java
public class Hello {

    public static void main(String[] args) {

    }

}
```

---

# Semicolon (;)

A semicolon marks the end of a Java statement.

Example:

```java
int age = 20;
System.out.println(age);
```

---

# Key Points

- Every Java program contains at least one class.
- The JVM starts execution from the `main()` method.
- Package and import statements are optional.
- Curly braces define the scope of a class or method.
- A semicolon (`;`) indicates the end of a statement.
- If a class is declared as `public`, the file name and class name must be the same.

---

# Interview Questions

### 1. What is the structure of a Java program?

A Java program consists of a package declaration (optional), import statements (optional), class declaration, main() method, and program statements.

### 2. Is the package declaration mandatory?

No. It is optional.

### 3. Is the import statement mandatory?

No. It is required only when classes from other packages are used.

### 4. Where does the JVM start executing a Java program?

The JVM starts executing a Java program from the `main()` method.

### 5. Why is a semicolon used in Java?

A semicolon marks the end of a statement.