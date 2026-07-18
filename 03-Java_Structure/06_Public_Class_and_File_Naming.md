# Public Class and File Naming Rule in Java

## What is the Rule?

If a Java source file contains a **public class**, the **file name must be the same as the public class name**.

### Example

```java
public class Student {

    public static void main(String[] args) {
        System.out.println("Hello");
    }

}
```

**File Name:**

```
Student.java
```

---

## Why is this Rule Important?

Java follows this rule to:

- Uniquely identify the public class.
- Keep the project organized.
- Avoid confusion for developers.
- Help the compiler verify the source file before compilation.

---

## If the File Name is Different

```java
// File Name: College.java

public class Student {

}
```

❌ Compilation Error

Reason:
- Public class name = `Student`
- File name = `College.java`

Both must be the same.

---

## Can We Create a Class Without `public`?

Yes.

```java
class Student {

}
```

This is valid.

In this case, the file name **does not have to match** the class name.

Example:

```
Test.java
```

```java
class Student {

}

class Employee {

}
```

✔️ Valid

---

## Can Multiple Classes Be Written in One File?

Yes.

```java
class Student {

}

class Teacher {

}

class Employee {

}
```

This is valid because none of the classes are `public`.

---

## Can Multiple Public Classes Be Written in One File?

No.

```java
public class Student {

}

public class Employee {

}
```

❌ Invalid

A Java source file can contain **only one public class**.

---

## Accessing Classes

### Same Package

Classes without the `public` keyword can be accessed by other classes **within the same package**.

Example:

```
college/
    Student.java
    Teacher.java
    Employee.java
```

```java
package college;

class Student {

}
```

```java
package college;

class Teacher {

    Student s = new Student();

}
```

✔️ Valid

---

### Different Package

Classes without the `public` keyword **cannot be accessed from another package**.

```java
package school;

import college.Student;
```

❌ Invalid (if `Student` is not public)

If `Student` is declared as `public`, then it can be accessed from other packages.

---

## Key Points

- If a class is `public`, the file name must match the class name.
- Only one `public` class is allowed in a Java source file.
- A class without `public` is accessible only within the same package.
- Multiple non-public classes can be written in a single file.
- In real-world projects, one class per file is the recommended practice.

---

## Interview Questions

### 1. Why should the file name match the public class name?

Java requires the file name to match the public class name to uniquely identify the public class and maintain a well-organized project structure.

---

### 2. Is a public class mandatory in Java?

No. A Java program can be written without a public class.

---

### 3. Can a Java file contain multiple public classes?

No. Only one public class is allowed in a Java source file.

---

### 4. Can multiple non-public classes be written in one file?

Yes. Multiple non-public classes can be declared in the same Java source file.

---

### 5. Can a non-public class be accessed from another package?

No. A non-public (package-private) class can only be accessed within the same package.