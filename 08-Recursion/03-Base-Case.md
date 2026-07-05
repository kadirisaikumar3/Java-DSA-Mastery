# 🛑 Base Case

---

# What is a Base Case?

The Base Case is the stopping condition of recursion.

Without a Base Case, recursion never ends.

---

# Example

Factorial

```java
int factorial(int n){

    if(n == 0)

        return 1;

    return n * factorial(n - 1);

}
```

---

# Why is it Important?

Without a Base Case:

```
Function

↓

Calls Itself

↓

Calls Itself

↓

...

↓

Stack Overflow
```

---

# Good Base Case

- Simple
- Easy to reach
- Returns immediately

---

# Bad Base Case

- Never reached
- Wrong condition
- Infinite recursion

---

# Common Base Cases

- n == 0
- n == 1
- left > right
- root == null
- index == length

---

# Interview Tip

Before writing the recursive call, write the base case first.