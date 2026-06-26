# 📊 Complexity Analysis

---

# What is Complexity Analysis?

Complexity Analysis is the process of determining how efficiently an algorithm performs.

We analyze:

- Time Complexity
- Space Complexity

---

# Rules

## Rule 1

Ignore Constants

```
O(5n)

↓

O(n)
```

---

## Rule 2

Ignore Lower Order Terms

```
O(n²+n)

↓

O(n²)
```

---

## Rule 3

Nested Loops Multiply

```java
for(...)
    for(...)
```

```
O(n²)
```

---

## Rule 4

Consecutive Loops Add

```java
for(...)

for(...)
```

```
O(n+n)

↓

O(n)
```

---

## Rule 5

Conditional Statements

Choose the maximum complexity.

```
if

↓

O(n)

else

↓

O(log n)
```

Overall

```
O(n)
```

---

# Examples

Single Loop

```
O(n)
```

Double Loop

```
O(n²)
```

Triple Loop

```
O(n³)
```

Binary Search

```
O(log n)
```

Merge Sort

```
O(n log n)
```

---

# Interview Tip

Always explain

"What contributes most to the complexity?"

instead of directly saying

"O(n²)."