# 🔧 Heapify

---

# What is Heapify?

Heapify is the process of restoring the Heap Property after insertion, deletion, or modification of elements.

---

# Types of Heapify

- Heapify Up (Bottom-Up)
- Heapify Down (Top-Down)

---

# Heapify Up

Used after inserting a new element.

Steps

1. Insert at the last position.
2. Compare with parent.
3. Swap if Heap Property is violated.
4. Repeat until the root or Heap Property is satisfied.

---

# Heapify Down

Used after deleting the root.

Steps

1. Move the last element to the root.
2. Compare with children.
3. Swap with the appropriate child.
4. Repeat until Heap Property is restored.

---

# Complexity

| Operation | Time |
|-----------|------|
| Heapify Up | O(log n) |
| Heapify Down | O(log n) |

---

# Interview Tip

Heapify only follows one path from root to leaf (or leaf to root), making it logarithmic.