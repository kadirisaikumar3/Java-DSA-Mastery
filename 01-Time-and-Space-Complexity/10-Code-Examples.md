# 📈 Amortized Analysis

---

# What is Amortized Analysis?

Some operations are occasionally expensive.

But over many operations,

their average cost remains low.

This average cost is called

Amortized Complexity.

---

# Example

ArrayList

Adding elements

Normally

```
O(1)
```

When capacity is full

Resize

Copy Elements

```
O(n)
```

---

# Why is Add Still O(1)?

Resizing happens rarely.

Most insertions take constant time.

Average Complexity

```
O(1)
```

Amortized.

---

# Another Example

Stack Push

```
O(1)
```

Queue Enqueue

```
O(1)
```

Dynamic Array Resize

```
Amortized O(1)
```

---

# Interview Tip

If asked

"Why is ArrayList.add() O(1)?"

Answer

"It is Amortized O(1)."

Not Worst Case O(1).