# 🔄 Tail Recursion

---

# What is Tail Recursion?

A recursive function where the recursive call is the last operation.

---

# Example

```java
int factorial(int n, int result){

    if(n == 0)

        return result;

    return factorial(n - 1, result * n);

}
```

---

# Normal Recursion

```
return n * factorial(n-1);
```

Needs additional work after recursion returns.

---

# Tail Recursion

```
return factorial(n-1, result*n);
```

No additional work after the recursive call.

---

# Advantages

- Cleaner recursion
- Easier to convert into iteration
- Better optimization in some languages

---

# Java Note

Java **does not perform Tail Call Optimization (TCO)**.

So Tail Recursion still consumes stack memory.

---

# Complexity

Time

```
O(n)
```

Space

```
O(n)
```

---

# Interview Tip

Know the difference between normal recursion and tail recursion, even though Java doesn't optimize tail calls.