# 🔁 Recursive Complexity

---

# Why is Recursion Different?

Recursive algorithms use:

- CPU Time
- Stack Memory

Both must be analyzed.

---

# Example

Factorial

```java
int factorial(int n){

    if(n==1)

        return 1;

    return n*factorial(n-1);

}
```

Calls

```
5

↓

4

↓

3

↓

2

↓

1
```

Time Complexity

```
O(n)
```

Space Complexity

```
O(n)
```

---

# Fibonacci

```java
fib(n)

↓

fib(n-1)

↓

fib(n-2)
```

Time Complexity

```
O(2ⁿ)
```

Space

```
O(n)
```

---

# Binary Search

Recursive

Time

```
O(log n)
```

Space

```
O(log n)
```

---

# Merge Sort

Time

```
O(n log n)
```

Space

```
O(n)
```

---

# Interview Tip

Whenever recursion appears,

Always analyze:

- Number of Calls
- Work per Call
- Stack Depth