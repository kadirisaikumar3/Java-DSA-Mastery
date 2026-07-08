# 🚀 Optimal Approach

---

# What is the Optimal Approach?

Use a Stack to avoid repeated comparisons and process each element efficiently.

---

# General Idea

```
Traverse Array

↓

Maintain Stack

↓

Remove Invalid Elements

↓

Answer in O(n)
```

---

# Example

Next Greater Element

Instead of scanning repeatedly,

use a Monotonic Stack.

---

# Complexity

| Problem | Time | Space |
|----------|------|-------|
| Next Greater Element | O(n) | O(n) |
| Daily Temperatures | O(n) | O(n) |
| Largest Rectangle | O(n) | O(n) |

---

# Advantages

- Single traversal
- Efficient comparisons
- Eliminates repeated work

---

# Interview Tip

Whenever you repeatedly search to the left or right,

think:

**Stack**