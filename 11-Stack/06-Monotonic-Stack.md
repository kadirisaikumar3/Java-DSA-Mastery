# 📈 Monotonic Stack

---

# What is a Monotonic Stack?

A Monotonic Stack stores elements in increasing or decreasing order.

It helps solve nearest greater/smaller element problems efficiently.

---

# Types

## Increasing Stack

```
1

2

4

7
```

Each new element is greater than or equal to the previous one.

---

## Decreasing Stack

```
9

7

5

2
```

Each new element is smaller than or equal to the previous one.

---

# Applications

- Next Greater Element
- Previous Greater Element
- Next Smaller Element
- Previous Smaller Element
- Largest Rectangle in Histogram
- Daily Temperatures

---

# Complexity

Time

```
O(n)
```

Each element is pushed and popped at most once.

---

# Interview Tip

If a problem asks for the **nearest greater/smaller** element, consider using a Monotonic Stack.