# 📚 Call Stack

---

# What is the Call Stack?

The Call Stack is a memory structure used by the program to keep track of active function calls.

Each recursive call creates a new stack frame.

---

# Visualization

Factorial(3)

```
factorial(3)

↓

factorial(2)

↓

factorial(1)

↓

return 1

↓

return 2

↓

return 6
```

---

# Stack Frames

Each function call stores:

- Parameters
- Local Variables
- Return Address

---

# Java Example

```java
int factorial(int n){

    if(n == 1)

        return 1;

    return n * factorial(n - 1);

}
```

---

# Stack Overflow

Too many recursive calls without reaching the base case will cause:

```
StackOverflowError
```

---

# Complexity

Space

```
O(n)
```

because each recursive call occupies stack memory.

---

# Interview Tip

Always consider the recursion depth when analyzing space complexity.