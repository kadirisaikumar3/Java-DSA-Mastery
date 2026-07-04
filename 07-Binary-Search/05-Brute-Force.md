# ❌ Brute Force Approach

---

# What is Brute Force?

Brute Force checks every possible answer one by one.

---

# Example

## Search Element

```java
for(int i = 0; i < arr.length; i++){

    if(arr[i] == target)

        return i;

}

return -1;
```

---

# Example

## Koko Eating Bananas

Try every possible eating speed.

```
1

2

3

...

MaxPile
```

---

# Complexity

Time

```
O(n)
```

or worse depending on the problem.

---

# Drawbacks

- Slow
- Repeated work
- Not suitable for large inputs

---

# Why Optimize?

Binary Search reduces many linear searches to logarithmic time.

```
O(n)

↓

O(log n)
```

---

# Interview Tip

Always begin with the brute-force solution before optimizing.