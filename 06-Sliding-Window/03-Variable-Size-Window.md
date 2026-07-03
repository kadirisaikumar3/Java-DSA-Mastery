# 📐 Variable Size Window

---

# What is a Variable Size Window?

The window expands and shrinks depending on the problem constraints.

---

# Visualization

```
[a b c]

↓

[a b c d]

↓

[b c d]
```

---

# Algorithm

1. Expand the window.
2. Check condition.
3. Shrink if necessary.
4. Continue until the end.

---

# Java Template

```java
int left = 0;

for(int right = 0; right < n; right++){

    // Expand window

    while(condition){

        // Shrink window

        left++;

    }

}
```

---

# Applications

- Longest Substring Without Repeating Characters
- Minimum Window Substring
- Fruit Into Baskets
- Longest Repeating Character Replacement

---

# Complexity

Time

```
O(n)
```

Space

Depends on the problem.

---

# Interview Tip

If the window size changes dynamically, think Variable Size Window.