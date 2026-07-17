# Output Methods

## Introduction

Java provides different output methods to display data on the console. The most commonly used methods are `print()`, `println()`, and `printf()`.

---

# System.out

Before understanding the output methods, let's understand `System.out`.

- `System` is a predefined class available in the `java.lang` package.
- `out` is a static object of the `PrintStream` class.
- `print()`, `println()`, and `printf()` are methods of the `PrintStream` class.

### Flow

```text
System (Class)
      │
      ▼
out (Static Object)
      │
      ▼
PrintStream Class
      │
      ▼
print(), println(), printf()
```

---

# print()

## Definition

The `print()` method displays the output on the console without moving the cursor to the next line.

## Syntax

```java
System.out.print(data);
```

## Example

```java
System.out.print("Hello");
System.out.print(" World");
```

### Output

```
Hello World
```

---

# println()

## Definition

The `println()` method displays the output and moves the cursor to the next line.

## Syntax

```java
System.out.println(data);
```

## Example

```java
System.out.println("Hello");
System.out.println("World");
```

### Output

```
Hello
World
```

---

# printf()

## Definition

The `printf()` method is used to display formatted output.

## Syntax

```java
System.out.printf("Format", values);
```

## Example

```java
int age = 20;

System.out.printf("Age = %d", age);
```

### Output

```
Age = 20
```

---

# Common Format Specifiers

| Specifier | Description |
|-----------|-------------|
| `%d` | Integer |
| `%f` | Floating-point number |
| `%c` | Character |
| `%s` | String |
| `%b` | Boolean |
| `%n` | New Line |

---

# Difference Between print(), println() and printf()

| Method | New Line | Formatting |
|---------|----------|------------|
| `print()` | ❌ No | ❌ No |
| `println()` | ✅ Yes | ❌ No |
| `printf()` | ❌ No (Use `%n`) | ✅ Yes |

---

# Key Points

- `System` is a predefined class in the `java.lang` package.
- `out` is a static object of the `PrintStream` class.
- `print()`, `println()`, and `printf()` are methods of the `PrintStream` class.
- `print()` prints the output on the same line.
- `println()` prints the output on a new line.
- `printf()` is used for formatted output.

---

# Interview Questions

### 1. What is `System.out`?

`System` is a predefined class, and `out` is a static object of the `PrintStream` class.

---

### 2. What is the difference between `print()` and `println()`?

`print()` displays the output on the same line, whereas `println()` moves the cursor to the next line after printing.

---

### 3. Why do we use `printf()`?

`printf()` is used to display formatted output using format specifiers.

---

### 4. Which package contains the `System` class?

The `System` class belongs to the `java.lang` package.