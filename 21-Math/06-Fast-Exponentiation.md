# ⚡ Fast Exponentiation

---

# Problem

Compute

```
a^b
```

efficiently.

---

# Idea

Use Binary Exponentiation by repeatedly squaring the base.

---

# Java Template

```java
long power(long a, long b){

    long result = 1;

    while(b > 0){

        if((b & 1) == 1){

            result *= a;

        }

        a *= a;

        b >>= 1;

    }

    return result;

}
```

---

# Complexity

```
O(log b)
```

---

# Applications

- Modular Exponentiation
- Cryptography
- Matrix Exponentiation

---

# Interview Tip

If the exponent is very large, think **Binary Exponentiation** instead of repeated multiplication.