# Comments in Java

## Introduction

Comments are used to make Java programs easier to read and understand. They are ignored by the Java compiler and do not affect program execution.

---

# Why Do We Use Comments?

- To explain the purpose of the code.
- To improve code readability.
- To make code easier to maintain.
- To temporarily disable a piece of code during testing or debugging.

---

# Types of Comments in Java

Java supports three types of comments:

1. Single-line Comment
2. Multi-line Comment
3. Documentation Comment

---

# 1. Single-line Comment

A single-line comment starts with `//`. Everything after `//` on the same line is treated as a comment.

## Syntax

```java
// This is a single-line comment
```

## Example

```java
// Printing a message
System.out.println("Hello, World!");
```

---

# 2. Multi-line Comment

A multi-line comment starts with `/*` and ends with `*/`. It is used to write comments that span multiple lines.

## Syntax

```java
/*
   Multi-line comment
*/
```

## Example

```java
/*
This program prints
Hello, World!
*/
System.out.println("Hello, World!");
```

---

# 3. Documentation Comment

A documentation comment starts with `/**` and ends with `*/`. It is mainly used to generate API documentation using the Javadoc tool.

## Syntax

```java
/**
 * Documentation Comment
 */
```

## Example

```java
/**
 * This method displays a welcome message.
 */
public static void greet() {
    System.out.println("Welcome");
}
```

---

# Difference Between the Types of Comments

| Type | Symbol | Purpose |
|------|--------|---------|
| Single-line | `//` | Used for a single line of explanation |
| Multi-line | `/* ... */` | Used for multiple lines of explanation |
| Documentation | `/** ... */` | Used to generate Javadoc documentation |

---

# Key Points

- Comments improve the readability of a program.
- Comments are ignored by the Java compiler.
- Single-line comments use `//`.
- Multi-line comments use `/* ... */`.
- Documentation comments use `/** ... */`.
- Documentation comments are used with the Javadoc tool.

---

# Interview Questions

### 1. What is a comment in Java?

A comment is a non-executable statement used to explain the code. It is ignored by the Java compiler.

---

### 2. How many types of comments are available in Java?

There are three types:
- Single-line Comment
- Multi-line Comment
- Documentation Comment

---

### 3. Which comment is used to generate Java documentation?

Documentation comments (`/** ... */`) are used to generate documentation using the Javadoc tool.

---

### 4. Do comments affect program execution?

No. Comments are ignored by the Java compiler and do not affect program execution.