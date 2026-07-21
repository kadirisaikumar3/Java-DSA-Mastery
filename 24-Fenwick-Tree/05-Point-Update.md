# Point Update

A Point Update changes the value of a single element in the array.

After updating an element, all affected cumulative sums stored in the Fenwick Tree must also be updated.

---

## Example

Original Array:

```
2 4 1 7 3
```

Update:

```
Index = 3

Add = 5
```

Updated Array:

```
2 4 6 7 3
```

The Fenwick Tree updates only the required nodes.

---

## Algorithm

```
while(index <= n)
{
    BIT[index] += value;
    index += index & (-index);
}
```

---

## Update Traversal

Suppose:

```
Index = 5
```

Visited nodes:

```
5

↓

6

↓

8

↓

16
```

Each affected node stores updated cumulative information.

---

## Time Complexity

| Operation | Complexity |
|-----------|------------|
| Point Update | O(log n) |

---

Fenwick Trees efficiently propagate updates using binary indexing, avoiding unnecessary recalculations.