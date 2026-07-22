# Merge Intervals

The **Merge Intervals Pattern** is used when working with overlapping intervals.

The intervals are first sorted, then merged wherever they overlap.

---

## When to Use

Apply this pattern for:

- Calendar scheduling
- Meeting rooms
- Interval merging
- Resource allocation
- Time ranges

---

## Example

Intervals:

```
[1,3]
[2,6]
[8,10]
[15,18]
```

Merged Result:

```
[1,6]
[8,10]
[15,18]
```

---

## Algorithm

1. Sort intervals by start time.
2. Compare the current interval with the previous one.
3. Merge if overlapping.
4. Otherwise, store the interval.

---

## Common Problems

- Merge Intervals
- Insert Interval
- Non-overlapping Intervals
- Meeting Rooms I & II
- Employee Free Time

---

## Complexity

| Operation | Complexity |
|-----------|------------|
| Time | O(n log n) |
| Space | O(n) |

---

## Key Idea

Sorting simplifies overlap detection, allowing a single pass to merge all intervals.