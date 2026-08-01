# Non-Primitive Data Types

## Introduction

Non-Primitive Data Types are also called **Reference Data Types**.

Unlike Primitive Data Types, Non-Primitive Data Types do **not store the actual value directly**. Instead, they store the **reference (memory address)** of an object.

These data types are mainly used to store complex data and support Object-Oriented Programming (OOP).

---

# Why Do We Need Non-Primitive Data Types?

Primitive Data Types can store only simple values such as numbers, characters, and boolean values.

However, real-world applications deal with complex data.

For example, consider a **Student**.

A student has:

- Name
- Age
- Department
- CGPA

These values cannot be stored together using a single primitive data type.

To represent such real-world entities, Java provides **Non-Primitive Data Types**.

---

# Characteristics of Non-Primitive Data Types

- Store the reference (memory address) of an object.
- Can store `null`.
- Size is not fixed.
- Created using classes.
- Support Object-Oriented Programming.
- Can contain both data and methods.

---

# Types of Non-Primitive Data Types

Java provides several Non-Primitive Data Types.

- String
- Array
- Class
- Interface
- Enum

---

# 1. String

A **String** is a sequence of characters.

### Syntax

```java
String name = "Subhasri";
```

### Real-World Example

A person's name is made up of multiple characters.

Example:

```
Subhasri
```

Instead of storing each character separately, Java stores them together as a String.

---

# 2. Array

An **Array** is used to store multiple values of the same data type.

### Syntax

```java
int[] marks = {90, 85, 95};
```

### Real-World Example

A teacher wants to store the marks of all students.

Instead of creating multiple variables,

```java
int mark1;
int mark2;
int mark3;
```

we can use an array.

```java
int[] marks = {90, 85, 95};
```

---

# 3. Class

A **Class** is a blueprint or template used to create objects.

### Syntax

```java
class Student {

}
```

Creating an object:

```java
Student s = new Student();
```

### Real-World Example

A house blueprint is a **Class**.

Every house built using that blueprint is an **Object**.

```
Blueprint (Class)
        │
        ├── House 1 (Object)
        ├── House 2 (Object)
        └── House 3 (Object)
```

---

# 4. Interface

An **Interface** is a contract that specifies what methods a class must implement.

### Syntax

```java
interface Animal {

    void sound();

}
```

### Real-World Example

A USB Type-C charging standard defines rules that every compatible mobile phone must follow.

```
USB-C Standard (Interface)
            │
      ┌─────┼─────┐
      │     │     │
 Samsung  Motorola  Google
```

Every company follows the same charging standard.

---

# 5. Enum

An **Enum** is used to represent a fixed set of constants.

### Syntax

```java
enum Signal {

    RED,
    YELLOW,
    GREEN

}
```

### Real-World Example

Traffic signals always have fixed colors.

- RED
- YELLOW
- GREEN

No other values are allowed.

Another example:

Days of the week.

- Monday
- Tuesday
- Wednesday
- Thursday
- Friday
- Saturday
- Sunday

---

# Memory Representation

Primitive Data Type

```java
int age = 20;
```

```
age
 │
20
```

The value is stored directly.

---

Non-Primitive Data Type

```java
Student s = new Student();
```

```
s
 │
 ▼
Student Object
```

The variable stores only the **reference (memory address)** of the object.

---

# Primitive vs Non-Primitive Data Types

| Primitive Data Types | Non-Primitive Data Types |
|----------------------|--------------------------|
| Store actual values | Store references (memory addresses) |
| Fixed size | Size is not fixed |
| Cannot store `null` | Can store `null` |
| Built into Java | Created using classes or provided by Java |
| Faster | Comparatively slower |

---

# Advantages of Non-Primitive Data Types

- Can represent real-world objects.
- Support Object-Oriented Programming.
- Easy to reuse.
- Easy to maintain.
- Allow dynamic memory allocation.

---

# Summary

- Non-Primitive Data Types are also called Reference Data Types.
- They store the reference (memory address) of an object.
- They are used to represent complex data.
- Common examples are String, Array, Class, Interface, and Enum.

---

# Interview Questions

### 1. What are Non-Primitive Data Types?

### 2. Why are they called Reference Data Types?

### 3. What is the difference between Primitive and Non-Primitive Data Types?

### 4. Can Non-Primitive Data Types store `null`?

### 5. Give some examples of Non-Primitive Data Types.

### 6. Why do we need Non-Primitive Data Types?

### 7. Explain the difference between a Class and an Object.

### 8. What is an Interface?

### 9. What is an Enum?

### 10. Is String a Primitive Data Type?