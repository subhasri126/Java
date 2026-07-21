# Variable Naming Conventions

## Introduction

Variable Naming Conventions are the recommended rules and best practices for naming variables in Java.

Following these conventions makes code more readable, maintainable, and easier to understand.

---

## Rules for Naming Variables

### 1. A Variable Name Must Start with a Letter, `_`, or `$`

A variable name can start with:
- A letter (`A-Z`, `a-z`)
- An underscore (`_`)
- A dollar sign (`$`)

It **cannot** start with a digit.

### Valid

```java
int age = 20;
int _count = 10;
int $salary = 50000;
```

### Invalid

```java
int 1age = 20;
```

Reason:

A variable name cannot start with a digit.

---

### 2. A Variable Name Can Contain Letters, Digits, `_`, and `$`

A variable name may contain:

- Letters
- Digits
- Underscore (`_`)
- Dollar sign (`$`)

### Valid

```java
student1
student_name
$price
_count
```

### Invalid

```java
student-name
student@name
student#name
```

Reason:

Special characters such as `-`, `@`, `#`, `%`, `&` are not allowed.

---

### 3. Variable Names Cannot Be Java Keywords

Java keywords are reserved words with predefined meanings.

Therefore, they cannot be used as variable names.

### Invalid

```java
int class = 10;
int public = 20;
int while = 30;
```

---

### 4. Variable Names Are Case-Sensitive

Uppercase and lowercase letters are treated differently.

```java
int age = 20;
int Age = 30;
```

Here,

- `age` and `Age` are two different variables.

---

## Naming Conventions (Best Practices)

These are **best practices** followed by Java developers.

The compiler does **not** enforce these conventions, but following them improves code quality.

---

### 1. Use Meaningful Variable Names

Choose names that clearly describe the purpose of the variable.

### Good

```java
studentName
ticketPrice
height
weight
```

### Poor

```java
a
x
abc
```

Meaningful names make programs easier to read and maintain.

---

### 2. Follow camelCase

Variables in Java follow the **camelCase** naming convention.

Rules:

- The first word starts with a lowercase letter.
- Each new word starts with an uppercase letter.

### Examples

```java
studentName
employeeId
ticketPrice
totalMarks
```

---

### 3. Keep Variable Names Short but Descriptive

Choose names that are easy to understand without making them unnecessarily long.

### Good

```java
address
employeeId
bookPrice
```

### Avoid

```java
addressOfTheEmployeeWorkingInCompany
```

---

### 4. Constants Use UPPER_SNAKE_CASE

Constants declared using the `final` keyword are written in uppercase with underscores.

```java
final double PI = 3.14159;
final int MAX_SIZE = 100;
```

---

## Rules vs Naming Conventions

| Rules | Naming Conventions |
|-------|--------------------|
| Enforced by the Java compiler | Recommended by Java developers |
| Violating a rule causes a compile-time error | Violating a convention does not cause an error |
| Mandatory | Best Practice |

---

## Key Points

- Variable names should start with a letter, `_`, or `$`.
- Variable names cannot start with a digit.
- Java keywords cannot be used as variable names.
- Variable names are case-sensitive.
- Use meaningful variable names.
- Follow the camelCase naming convention.
- Constants use UPPER_SNAKE_CASE.

---

## Interview Questions

### 1. What are Variable Naming Conventions?

Variable Naming Conventions are the recommended rules and best practices for naming variables in Java.

---

### 2. Can a variable name start with a digit?

No.

---

### 3. Can Java keywords be used as variable names?

No.

---

### 4. Are variable names case-sensitive?

Yes.

Example:

`age` and `Age` are different variables.

---

### 5. What naming convention is used for Java variables?

camelCase

---

### 6. What naming convention is used for constants?

UPPER_SNAKE_CASE