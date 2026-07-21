# Frequently Asked Questions (FAQs)

## 1. Is Fenwick Tree better than Segment Tree?

For prefix sum queries and point updates, Fenwick Tree is usually simpler and uses less memory.

---

## 2. Why is Fenwick Tree faster to implement?

It uses a single array and simple bit manipulation instead of explicit tree nodes.

---

## 3. Can it perform range sum queries?

Yes.

Using:

```
Prefix(R)

-

Prefix(L-1)
```

---

## 4. Does it support minimum queries?

No.

Fenwick Trees are mainly designed for cumulative operations like sums and frequencies.

---

## 5. Why use bit manipulation?

To efficiently move between parent and child ranges using the Least Significant Set Bit (LSB).

---

## 6. Is Fenwick Tree asked in interviews?

Yes.

Especially in companies that focus on advanced data structures and optimization techniques.

---

## 7. Which is easier?

Fenwick Tree is generally easier than Segment Tree for prefix sum problems.

---

## 8. Time Complexity Summary

| Operation | Complexity |
|-----------|------------|
| Query | O(log n) |
| Update | O(log n) |
| Space | O(n) |