# 📖 Introduction to Time and Space Complexity

---

# What is an Algorithm?

An algorithm is a finite sequence of well-defined steps used to solve a problem.

Example:

Finding the largest number in an array.

Different algorithms can solve the same problem with different efficiencies.

---

# Why Study Complexity?

Suppose two students solve the same problem.

Student A

```
Time Complexity

O(n²)
```

Student B

```
Time Complexity

O(n)
```

Both produce correct answers.

Who gets selected?

Student B.

Because their solution scales much better.

---

# What is Complexity Analysis?

Complexity Analysis measures how an algorithm performs as the input size increases.

Instead of measuring:

- Seconds
- Milliseconds

We measure:

- Number of Operations

---

# Types of Complexity

## 1. Time Complexity

Measures how execution time grows.

Example:

```
Input = 10

Operations = 10
```

```
Input = 100

Operations = 100
```

Complexity

```
O(n)
```

---

## 2. Space Complexity

Measures how much additional memory an algorithm requires.

Example:

Using one extra array of size n.

Space Complexity

```
O(n)
```

---

# Why Not Measure Time Directly?

Execution time depends on:

- CPU Speed
- RAM
- Operating System
- Compiler
- Programming Language

Complexity avoids these factors and provides a machine-independent measure.

---

# Example

Linear Search

```
1

2

3

4

5
```

Searching for

```
5
```

Operations

```
5
```

Searching for

```
2
```

Operations

```
2
```

Complexity

```
O(n)
```

---

# Interview Tip

Whenever you finish writing code, immediately ask yourself:

- What is the Time Complexity?
- What is the Space Complexity?

This habit is expected in coding interviews.

---

# Summary

Complexity Analysis helps us:

- Compare algorithms
- Improve efficiency
- Reduce execution time
- Save memory
- Build scalable software