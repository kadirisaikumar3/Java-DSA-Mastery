# ☕ Java Code Templates

---

# Check Power of Two

```java
boolean isPowerOfTwo(int n){

    return n > 0 &&

    (n & (n - 1)) == 0;

}
```

---

# Count Set Bits

```java
int count = 0;

while(n != 0){

    n = n & (n - 1);

    count++;

}
```

---

# Check ith Bit

```java
boolean check =

(n & (1 << i)) != 0;
```

---

# Toggle ith Bit

```java
n ^= (1 << i);
```

---

# Set ith Bit

```java
n |= (1 << i);
```

---

# Clear ith Bit

```java
n &= ~(1 << i);
```

---

# Interview Tip

Memorize these templates—they solve a large percentage of Bit Manipulation questions.