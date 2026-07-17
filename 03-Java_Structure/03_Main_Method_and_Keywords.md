# Main Method and Keywords

## Introduction

The `main()` method is the entry point of every Java application. The Java Virtual Machine (JVM) starts executing a Java program from this method.

---

# Syntax

```java
public static void main(String[] args) {

}
```

---

# Keywords Used in the main() Method

## 1. public

The `public` keyword is an access modifier. It makes the `main()` method accessible to the JVM from anywhere.

### Example

```java
public static void main(String[] args)
```

---

## 2. static

The `static` keyword allows the JVM to call the `main()` method without creating an object of the class.

### Example

```java
public static void main(String[] args)
```

---

## 3. void

The `void` keyword indicates that the `main()` method does not return any value.

### Example

```java
public static void main(String[] args)
```

---

## 4. main

`main` is the predefined method name recognized by the JVM as the starting point of a Java application.

### Example

```java
public static void main(String[] args)
```

---

## 5. String[] args

`String[] args` is used to receive command-line arguments passed to the Java program.

The parameter name `args` is not mandatory. Any valid identifier can be used.

### Example

```java
public static void main(String[] arguments)
```

or

```java
public static void main(String[] input)
```

---

# How JVM Executes the Program

```text
Java Source File (.java)
          │
          ▼
Compilation (javac)
          │
          ▼
Bytecode (.class)
          │
          ▼
JVM
          │
          ▼
Calls the main() Method
          │
          ▼
Program Execution Starts
```

---

# Key Points

- The `main()` method is the entry point of every Java application.
- The JVM starts execution from the `main()` method.
- `public` allows the JVM to access the method.
- `static` allows the method to be called without creating an object.
- `void` indicates that the method does not return any value.
- `String[] args` stores command-line arguments.
- The parameter name `args` can be changed.

---

# Interview Questions

### 1. Why is the `main()` method declared as `public`?

Because the JVM must be able to access it from outside the class.

---

### 2. Why is the `main()` method declared as `static`?

Because the JVM calls it without creating an object of the class.

---

### 3. Why is the return type `void`?

Because the `main()` method does not return any value.

---

### 4. Can we change the name `args`?

Yes. The parameter name can be changed to any valid identifier.

---

### 5. Where does the JVM start executing a Java program?

The JVM starts executing a Java program from the `main()` method.