# Data Types

## Introduction

A **Data Type** specifies the type of data that a variable can store. It also tells the Java compiler how much memory should be allocated for the variable and what kind of values the variable can hold.

### Example

```java
int age = 20;
double salary = 35000.50;
char grade = 'A';
boolean isPassed = true;
```

---

# Why Do We Need Data Types?

Different types of data require different amounts of memory.

For example:

- Age → Integer
- Salary → Decimal Number
- Grade → Character
- Status → Boolean

Data types help Java allocate memory efficiently and prevent invalid data from being stored.

---

# Binary Representation

A computer understands only two values:

- 0
- 1

These are called **Binary Digits (Bits)**.

All data such as numbers, characters, and boolean values are ultimately represented in binary.

---

# Bit

A **Bit (Binary Digit)** is the smallest unit of memory in a computer.

A bit has only two possible values:

- 0
- 1

Therefore,

```text
1 Bit = 2¹ = 2 Possible Values
```

---

# Byte

A **Byte** consists of **8 Bits**.

```text
1 Byte = 8 Bits
```

Since one bit has two possible values,

```text
2⁸ = 256 Possible Combinations
```

---

# Memory Units

| Unit | Value |
|------|--------|
| 1 Byte (B) | 8 Bits |
| 1 Kilobyte (KB) | 1024 Bytes |
| 1 Megabyte (MB) | 1024 KB |
| 1 Gigabyte (GB) | 1024 MB |
| 1 Terabyte (TB) | 1024 GB |

---

# Signed and Unsigned Integers

In computer systems, integers are generally classified into two types.

## Unsigned Integer

Stores only positive values (including zero).

Example (8-bit):

```text
0 to 255
```

## Signed Integer

Stores both positive and negative values.

The **Most Significant Bit (MSB)** is used as the **Sign Bit**.

- MSB = 0 → Positive
- MSB = 1 → Negative

> **Note:** Java supports only **signed** integer data types (`byte`, `short`, `int`, and `long`).

---

# Why is the Byte Range -128 to 127?

A byte contains **8 bits**.

- 1 bit is used as the sign bit.
- Remaining 7 bits are used to store the value.

Negative Range:

```text
-2⁷ = -128
```

Positive Range:

```text
2⁷ - 1 = 127
```

The `-1` is because **0** is also included in the positive range.

Therefore,

```text
Byte Range = -128 to 127
```

---

# Types of Data Types

Java provides two categories of data types.

## 1. Primitive Data Types

Primitive data types are built into Java and directly store values.

There are **8 Primitive Data Types**.

- byte
- short
- int
- long
- float
- double
- char
- boolean

### Syntax

```java
dataType variableName = value;
```

### Examples

```java
int age = 20;
double salary = 35000.50;
char grade = 'A';
boolean isPassed = true;
```

---

## 2. Reference (Non-Primitive) Data Types

Reference data types store the reference (memory address) of objects.

Examples include:

- String
- Arrays
- Classes
- Interfaces
- Enums

### Syntax

```java
ClassName variableName = new ClassName();
```

### Examples

```java
String name = "Subhasri";

int[] marks = {90, 85, 95};
```

> Primitive data types store values directly, whereas reference data types store the reference (memory address) of objects.

---

# Character Representation

Java uses **Unicode** to represent characters.

```java
char ch = 'A';
```

The character `'A'` has the Unicode value **65**, which is stored internally as binary.

> **Note:** ASCII is a subset of Unicode.

---

# Summary

- A data type specifies what kind of value a variable can store.
- Every value in a computer is represented using binary (0s and 1s).
- A bit is the smallest unit of memory.
- 8 bits make 1 byte.
- Java supports only signed integer data types.
- Java has two categories of data types:
  - Primitive Data Types
  - Reference (Non-Primitive) Data Types.

---

# Interview Questions

### 1. What is a Data Type?

A data type specifies the type of value a variable can store and determines the amount of memory allocated.

### 2. Why are Data Types important?

They help Java allocate memory efficiently, ensure type safety, and prevent invalid data from being stored.

### 3. How many categories of Data Types are there in Java?

There are **two categories**:

- Primitive Data Types
- Reference (Non-Primitive) Data Types

### 4. What is the difference between Primitive and Reference Data Types?

| Primitive Data Types | Reference Data Types |
|----------------------|----------------------|
| Store values directly | Store references (memory addresses) |
| Built into Java | Created using classes and objects |
| Fixed size | Size depends on the object |

### 5. Does Java support unsigned integer data types?

No. Java provides only signed integer primitive data types (`byte`, `short`, `int`, and `long`).

### 6. What is the smallest unit of memory?

A **Bit (Binary Digit)** is the smallest unit of memory.

### 7. How many bits are there in one byte?

One byte consists of **8 bits**.

### 8. What is the difference between ASCII and Unicode?

ASCII represents a limited set of characters, whereas Unicode represents characters from almost all languages. Java uses **Unicode**.
