# 📖 String Concepts

---

# What is a String?

A String is a sequence of characters.

Example

```java
String name = "Google";
```

---

# Characteristics

- Immutable
- Object in Java
- Stored in String Pool
- Zero-based indexing
- Supports Unicode

---

# Memory Representation

```
Index

0 1 2 3 4 5

Value

G o o g l e
```

---

# Declaration

```java
String s1 = "Hello";
```

---

# Creating with new

```java
String s2 = new String("Hello");
```

---

# String Pool

```
String s1 = "Java";

String s2 = "Java";
```

Both reference the same object in the String Pool.

---

# Immutability

```java
String s = "Java";

s = s + " DSA";
```

A new String object is created.

The original object remains unchanged.

---

# Advantages

- Secure
- Thread-safe
- Memory Efficient
- Easy to use

---

# Disadvantages

- Cannot modify existing String
- Frequent concatenation creates new objects

---

# Common Methods

```java
length()

charAt()

substring()

equals()

compareTo()

contains()

replace()

split()

trim()

toLowerCase()

toUpperCase()
```

---

# Interview Tip

Always remember:

Strings are immutable.

This is one of the most frequently asked Java interview questions.