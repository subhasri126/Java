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

# Computer Stores Everything in Binary

A computer understands only two values:

- 0
- 1

These values are called **Binary Digits (Bits)**.

Every value in Java, such as integers, decimal numbers, characters, and boolean values, is ultimately stored in binary.

---

# Bit

A **Bit (Binary Digit)** is the smallest unit of memory in a computer.

A bit can store only one of two values.

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

Since each bit has two possible values,

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

# Binary Combinations

Each bit has two possible values:

- 0
- 1

If there are **n bits**, the total number of possible combinations is:

```text
2ⁿ
```

Example:

| Bits | Possible Combinations |
|------|------------------------|
| 1 | 2¹ = 2 |
| 2 | 2² = 4 |
| 3 | 2³ = 8 |
| 8 | 2⁸ = 256 |

---

# Signed and Unsigned Integers

Generally, integers are classified into two types.

## Unsigned Integer

Stores only positive numbers (including zero).

Example (8-bit):

```text
0 to 255
```

---

## Signed Integer

Stores both positive and negative numbers.

The **Most Significant Bit (MSB)** is reserved as the sign bit.

- MSB = 0 → Positive
- MSB = 1 → Negative

> **Note:** Java supports only **signed integer** primitive data types (`byte`, `short`, `int`, and `long`).

---

# Why is the Byte Range -128 to 127?

A byte contains **8 bits**.

- 1 bit is reserved for the sign.
- Remaining 7 bits store the value.

Negative range:

```text
-2⁷ = -128
```

Positive range:

```text
2⁷ − 1 = 127
```

The **-1** is because **0** is also included in the positive range.

Therefore,

```text
Byte Range = -128 to 127
```

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

| Data Type | Size | Range | Default Value |
|-----------|------|------------------------------|---------------|
| byte | 1 Byte | -128 to 127 | 0 |
| short | 2 Bytes | -32,768 to 32,767 | 0 |
| int | 4 Bytes | -2,147,483,648 to 2,147,483,647 | 0 |
| long | 8 Bytes | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 | 0L |
| float | 4 Bytes | Approximately ±3.4 × 10³⁸ | 0.0f |
| double | 8 Bytes | Approximately ±1.8 × 10³⁰⁸ | 0.0d |
| char | 2 Bytes | 0 to 65,535 (Unicode) | '\u0000' |
| boolean | JVM-dependent | true or false | false |

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