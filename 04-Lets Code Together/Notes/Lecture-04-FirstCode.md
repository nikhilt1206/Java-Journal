# Java MasterClass – Lecture 4: Packages, Class Structure & Variables

> Personal notes — Date: 9/8/26

## 1. Code Block

A **code block** is anything enclosed within `{ }` (curly braces). It's an anonymous block of code.

```java
{
    // Code Block -> anonymous code block
}
```

## 2. Class & Main Method Structure

```java
public class Example1 {   // start of the class
    ...
}                          // End of the class

public static void main(String[] args) {
    ...
}
```

- `main(String[] args)` → `args` are **Runtime Arguments**.
- In order to execute a program, Java requires a `main` method. The main method indicates the **start of the program**.
- The main method signature will **always** be: `public static void main`
- The **name of the class must always match the name of the file** (mandatory).

## 3. Packages

- Java files (under `src`) have the `.java` extension.
- Inside `src`, we can create **packages**.
    - Purpose of a package → to **manage/organize** Java files.
- Package names usually start with a **lowercase letter**.

### Example

```java
package example1;   // information: package created with name "example1" (scope: public)

public class Example1 {

    public static void main(String[] args) {

    }
}
```

- `package`, `public`, `class`, `static`, `void` → these are **Reserved Keywords**.
    - They help **Java understand our program**.

**Open question:** Can we create a private class?

## 4. Variables — Declaration & Assignment

```java
int a;      // declaration
a = 20;     // assignment (LHS = RHS)
```

- `a` holds the value `20`, occupying **4 bytes**.
- `20` → is it an Integer Literal? → **Yes**
- Two things to check for any variable: (1) the literal/value, (2) the **Data Type** of the variable.

## 5. Sample Data Type Declarations

```java
package example1;

public class Example1 {

    public static void main(String[] args) {

        int a;              // declaration
        a = 20;              // assignment

        long x = 2000;
        char gender = 'm';
        float percentage = 33.23f;
        boolean isPresent = false;
    }
}
```

| Variable     | Data Type | Value    |
|--------------|-----------|----------|
| `a`          | `int`     | `20`     |
| `x`          | `long`    | `2000`   |
| `gender`     | `char`    | `'m'`    |
| `percentage` | `float`   | `33.23f` |
| `isPresent`  | `boolean` | `false`  |

`long`, `char`, `float`, `boolean` etc. are examples of **non-primitive / reference data types** context noted alongside primitives — to revisit and clarify further.

---

### To Revisit / Open Questions
- [ ] Can we create a private class in Java?
- [ ] Clarify primitive vs non-primitive/reference data type distinction from the top of the notes.
