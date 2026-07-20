# Variables in Java

## Introduction

A variable is a named memory location used to store data.

Variables allow a program to store, retrieve, and manipulate data during execution.

---

## Why Do We Need Variables?

Programs work with data such as:

- Numbers
- Characters
- Strings
- Boolean values

Variables help us store these values in memory for later use.

---

## Variable Declaration

A variable declaration tells Java the variable's data type and name.

### Syntax

```java
dataType variableName;
```

### Example

```java
int age;
```

---

## Variable Initialization

Initialization means assigning a value to a variable.

### Syntax

```java
variableName = value;
```

### Example

```java
age = 20;
```

---

## Declaration and Initialization

Both can be done together.

### Syntax

```java
dataType variableName = value;
```

### Example

```java
int age = 20;
```

---

## How Variables Work

When a variable is created:

1. Java allocates memory.
2. The value is stored in that memory.
3. Whenever the variable is used, Java accesses the stored value.

Example:

```java
int marks = 95;

System.out.println(marks);
```

**Output**

```text
95
```

---

## Java is a Statically Typed Language

Java requires every variable to have a data type.

The data type must be declared before using the variable.

Example:

```java
int age = 20;
```

---

## One Variable Can Store Only One Data Type

A variable can store only values of its declared data type.

### Valid

```java
int number = 10;
```

### Invalid

```java
int number = 10;

number = "Subha";
```

**Output**

```text
Compile Time Error
```

Reason:

`number` is declared as an `int`, so it cannot store a `String`.

---

## Naming Rules

- Variable names can contain letters, digits, `_`, and `$`.
- Variable names cannot start with a digit.
- Java keywords cannot be used as variable names.
- Variable names are case-sensitive.

### Valid

```java
age
studentName
_marks
$count
```

### Invalid

```java
1age
class
int
```

---

## Key Points

- A variable is a named memory location.
- Variables are used to store data.
- Every variable must have a data type.
- Java is a statically typed language.
- Declaration and initialization are different concepts.
- A variable can store only values of its declared data type.

---

## Interview Questions

### 1. What is a variable?

A variable is a named memory location used to store data.

---

### 2. What is variable declaration?

Declaring a variable means specifying its data type and name.

---

### 3. What is variable initialization?

Initialization is the process of assigning a value to a variable.

---

### 4. Why is Java called a statically typed language?

Because every variable must have a data type, and type checking is performed at compile time.

---

### 5. Can one variable store multiple data types?

No. A variable can store only values of its declared data type.