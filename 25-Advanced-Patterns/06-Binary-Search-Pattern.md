# Binary Search Pattern

Binary Search is used to efficiently search within sorted data by repeatedly dividing the search space in half.

---

## When to Use

Use Binary Search when:

- Array is sorted
- Search space is monotonic
- Finding first/last occurrence
- Answer lies in a numeric range

---

## Example

Array:

```
2 5 8 12 16 20 25
```

Target:

```
16
```

Search:

```
Middle → Compare

↓

Discard Half

↓

Repeat
```

---

## Common Problems

- Binary Search
- Search Insert Position
- First Bad Version
- Koko Eating Bananas
- Capacity To Ship Packages
- Median of Two Sorted Arrays

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(log n) |
| Space | O(1) |

---

## Key Idea

Each comparison eliminates half of the remaining search space, making Binary Search one of the fastest searching techniques.