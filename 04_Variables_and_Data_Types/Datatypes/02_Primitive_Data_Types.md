# Primitive Data Types

## Introduction

Primitive Data Types are the built-in data types provided by Java. They are predefined by the Java language and are used to store simple values directly in memory.

Java provides **8 primitive data types**.

---

# Why Do We Need Primitive Data Types?

Every program stores data such as numbers, characters, and logical values.

To store these values efficiently, Java provides primitive data types.

Each primitive data type has:

- A fixed size
- A fixed range
- A specific purpose

---


# Categories of Primitive Data Types

Primitive data types are divided into four categories.

## 1. Integer Data Types

Used to store whole numbers.

- byte
- short
- int
- long

### Example

```java
byte age = 20;
short year = 2026;
int salary = 50000;
long population = 1420000000L;
```

---

## 2. Floating-Point Data Types

Used to store decimal numbers.

- float
- double

### Example

```java
float temperature = 36.5f;
double pi = 3.141592653589793;
```

---

## 3. Character Data Type

Used to store a single Unicode character.

- char

### Example

```java
char grade = 'A';
```

---

## 4. Boolean Data Type

Used to store logical values.

- boolean

### Example

```java
boolean isPassed = true;
```

---

# Primitive Data Types

| Data Type | Size | Range (Power of 2) | Default Value |
|-----------|------|--------------------|---------------|
| `byte` | 1 Byte (8 bits) | **-2⁷ to 2⁷ - 1** | `0` |
| `short` | 2 Bytes (16 bits) | **-2¹⁵ to 2¹⁵ - 1** | `0` |
| `int` | 4 Bytes (32 bits) | **-2³¹ to 2³¹ - 1** | `0` |
| `long` | 8 Bytes (64 bits) | **-2⁶³ to 2⁶³ - 1** | `0L` |
| `float` | 4 Bytes (32 bits) | Approximately **±2¹²⁸** (IEEE 754) | `0.0f` |
| `double` | 8 Bytes (64 bits) | Approximately **±2¹⁰²⁴** (IEEE 754) | `0.0d` |
| `char` | 2 Bytes (16 bits) | **0 to 2¹⁶ − 1** | `'\u0000'` |
| `boolean` | JVM-dependent | `true` or `false` | `false` |

---



# Character Representation

Characters are stored using **Unicode**.

Example:

```java
char ch = 'A';
```

Internally,

```text
'A' → Unicode Value (65) → Binary
```

> ASCII is a subset of Unicode.

---

# Advantages of Primitive Data Types

- Faster execution.
- Uses less memory.
- Fixed size.
- Efficient for storing simple values.
- Built into Java.

---

# Summary

- Primitive Data Types are built into Java.
- Java provides **8 Primitive Data Types**.
- They store values directly in memory.
- Computers store everything in binary.
- Java supports only signed integer primitive data types.
- Primitive Data Types are classified into Integer, Floating-Point, Character, and Boolean.

---

# Interview Questions

### 1. What are Primitive Data Types?

### 2. Why do we need Primitive Data Types?

### 3. How many Primitive Data Types are available in Java?

### 4. What is the smallest unit of memory?

### 5. What is the difference between Bit and Byte?

### 6. What is the difference between Signed and Unsigned Integers?

### 7. Why does Java support only signed integers?

### 8. Why is the range of byte -128 to 127?

### 9. What are the four categories of Primitive Data Types?

### 10. Does Java use ASCII or Unicode?