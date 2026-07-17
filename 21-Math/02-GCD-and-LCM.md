# 🔢 GCD and LCM

---

# GCD (Greatest Common Divisor)

The largest number that divides both numbers.

Example

```
GCD(12, 18) = 6
```

---

# Euclidean Algorithm

Formula

```
gcd(a, b)

↓

gcd(b, a % b)
```

---

# Java Template

```java
int gcd(int a, int b){

    while(b != 0){

        int temp = b;

        b = a % b;

        a = temp;

    }

    return a;

}
```

---

# LCM

Formula

```
LCM(a, b)

=

(a × b) / GCD(a, b)
```

---

# Complexity

```
O(log n)
```

---

# Interview Tip

Always compute LCM using GCD to avoid unnecessary calculations.