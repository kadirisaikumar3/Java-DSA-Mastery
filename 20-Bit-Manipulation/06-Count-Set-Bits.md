# 🔢 Count Set Bits

---

# Problem

Count the number of `1`s in the binary representation.

---

# Brute Force

Check every bit.

Complexity

```
O(32)
```

---

# Brian Kernighan's Algorithm

```java
while(n != 0){

    n = n & (n - 1);

    count++;

}
```

---

# Complexity

```
O(Number of Set Bits)
```

---

# Example

```
13

1101
```

Iterations

```
1101

↓

1100

↓

1000

↓

0000
```

Count = 3

---

# Interview Tip

Brian Kernighan's Algorithm is the preferred interview solution.