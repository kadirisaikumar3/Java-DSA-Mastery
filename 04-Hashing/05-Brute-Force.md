# ❌ Brute Force Approach

---

# What is Brute Force?

A brute-force solution checks every possibility without optimization.

It is useful as a starting point before improving the solution.

---

# Example 1

## Contains Duplicate

Brute Force

```java
for(int i = 0; i < arr.length; i++){

    for(int j = i + 1; j < arr.length; j++){

        if(arr[i] == arr[j])

            return true;

    }

}

return false;
```

Time

```
O(n²)
```

---

# Example 2

## Two Sum

Check every pair.

Time

```
O(n²)
```

---

# Example 3

## Frequency Count

For every element, scan the entire array.

Time

```
O(n²)
```

---

# Why Optimize?

Nested loops become inefficient for large datasets.

Hashing reduces many O(n²) solutions to O(n).

---

# Interview Tip

Explain the brute-force approach first, then introduce HashMap or HashSet for optimization.