# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force solves the problem using the simplest recursive idea without optimization.

---

# Example

Naive Fibonacci

```java
int fibonacci(int n){

    if(n <= 1)

        return n;

    return fibonacci(n-1) + fibonacci(n-2);

}
```

---

# Recursion Tree

```
F(5)

├── F(4)

│   ├── F(3)

│   └── F(2)

└── F(3)
```

Many subproblems are solved repeatedly.

---

# Complexity

Time

```
O(2ⁿ)
```

Space

```
O(n)
```

---

# Drawbacks

- Duplicate computations
- Slow execution
- Large recursion tree

---

# Interview Tip

Whenever you notice repeated recursive calls, think about Dynamic Programming.