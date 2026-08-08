# Java MasterClass — Lecture 3: Literals

## What is a Literal?

A **literal** is a fixed, constant value that is **explicitly assigned to a variable** — it represents raw data written directly in the source code (as opposed to a variable, which is a name/reference to data).

```java
int a = 42;
```

| Part | Meaning |
|---|---|
| `int` | Datatype |
| `a` | Variable name |
| `=` | Assignment operator |
| `42` | Literal (Integer literal), also called a primitive value |

- **Datatype** → `int`, `byte`, `short`, `long`, etc.
- **Value** → the literal itself, here it's an **Integer Literal**
- Memory representation example: `42` stored as a 4-byte `int`.

---

## Types of Literals in Java (6 Types)

### 1. Integer Literals
Whole numbers, positive or negative, no decimal point.

```java
int a = 42;
```
Examples: `42, 0, -7, 88`

---

### 2. Floating Point Literals
Numbers with decimal points, used for precision values.

```java
float pi = 3.142f;
double interest = 5.02;
```
Examples: `3.142f, 3.00001029, 0.00000012`

> `f` suffix is required for `float` literals (default floating point literals are treated as `double`).

---

### 3. Character Literals
A single character enclosed in single quotes `' '`.

```java
char gender = 'm';
```
Examples: `'a', 'b', '%', 'A', 'B', 'Z', ' '`

---

### 4. Boolean Literals
Only two possible values: `true` or `false`.

```java
boolean isPresent = false;
```

---

### 5. String Literals *(Non-Primitive / Class type)*
A sequence of characters enclosed in double quotes `" "`.

```java
String name = "Jatin";
```
Examples: `"Jatin", "7085267"`

---

### 6. Null Literal *(Non-Primitive / Reference type)*
Represents the absence of a value — used for reference/object variables.

```java
Bank b = null;
```

---

## Quick Recap Table

| # | Literal Type | Category | Example |
|---|---|---|---|
| 1 | Integer | Primitive | `int a = 42;` |
| 2 | Floating Point | Primitive | `float pi = 3.142f;` |
| 3 | Character | Primitive | `char gender = 'm';` |
| 4 | Boolean | Primitive | `boolean isPresent = false;` |
| 5 | String | Non-Primitive (Class) | `String name = "Jatin";` |
| 6 | Null | Non-Primitive (Reference) | `Bank b = null;` |

---

📅 *Lecture Date: 8/8/26 — Java MasterClass Series*
