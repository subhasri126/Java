# Identifiers

## Introduction

An **identifier** is a name given by the programmer to program elements in Java.

Identifiers are used to uniquely identify different elements in a Java program.

---

## Program Elements That Use Identifiers

Identifiers can be used for:

- Variables
- Classes
- Methods
- Interfaces
- Packages
- Enums

### Example

```java
public class Student {

    int age = 20;

    void display() {
        System.out.println(age);
    }
}
```

Here,

- `Student` → Class Identifier
- `age` → Variable Identifier
- `display()` → Method Identifier

---

## Rules for Identifiers

### 1. Must Start with a Letter, `_`, or `$`

An identifier can start with:

- A letter (`A-Z`, `a-z`)
- An underscore (`_`)
- A dollar sign (`$`)

It **cannot** start with a digit.

### Valid

```java
age
_student
$price
```

### Invalid

```java
1age
```

---

### 2. Can Contain Letters, Digits, `_`, and `$`

An identifier may contain:

- Letters
- Digits
- Underscore (`_`)
- Dollar sign (`$`)

### Valid

```java
student1
marks2
student_name
$salary
```

### Invalid

```java
student-name
student@name
student#name
```

Reason:

Special characters such as `-`, `@`, `#`, `%`, and `&` are not allowed.

---

### 3. Cannot Be a Java Keyword

Java keywords are reserved words with predefined meanings.

Therefore, they cannot be used as identifiers.

### Invalid

```java
class
public
while
int
```

---

### 4. Identifiers Are Case-Sensitive

Java treats uppercase and lowercase letters differently.

```java
int age = 20;
int Age = 25;
```

Here,

- `age` and `Age` are two different identifiers.

---

## Best Practices

Although the compiler accepts many valid names, Java developers follow some naming conventions.

### Use Meaningful Names

Choose names that clearly describe the purpose of the program element.

### Good

```java
studentName
employeeId
totalMarks
```

### Poor

```java
a
x
abc
```

Meaningful names make code easier to read and maintain.

---

## Identifier vs Variable

Every **variable name** is an **identifier**.

However, **not every identifier is a variable**.

Example:

```java
class Student {

    int age;

    void display() {

    }
}
```

- `Student` → Identifier (Class)
- `age` → Identifier (Variable)
- `display` → Identifier (Method)

---

## Key Points

- An identifier is a name given to program elements.
- Identifiers are used for variables, methods, classes, interfaces, packages, and enums.
- An identifier cannot start with a digit.
- An identifier can contain letters, digits, `_`, and `$`.
- Java keywords cannot be used as identifiers.
- Identifiers are case-sensitive.
- Use meaningful names for better readability.

---

## Interview Questions

### 1. What is an identifier?

An identifier is a name given by the programmer to program elements such as variables, methods, classes, interfaces, packages, and enums.

---

### 2. Can an identifier start with a digit?

No.

---

### 3. Can Java keywords be used as identifiers?

No.

---

### 4. Are identifiers case-sensitive?

Yes.

Example:

`age` and `Age` are different identifiers.

---

### 5. Is every variable an identifier?

Yes.

---

### 6. Is every identifier a variable?

No.

Variables, classes, methods, interfaces, and packages all use identifiers.