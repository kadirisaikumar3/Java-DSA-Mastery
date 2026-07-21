# Bit Manipulation Logic

The efficiency of a Fenwick Tree comes from one simple bit operation:

```
index & (-index)
```

This expression extracts the **Least Significant Set Bit (LSB)** of an index.

---

## Example 1

```
Index = 12

Binary:

1100

-Index (Two's Complement):

0100

Result:

1100
&
0100

=

0100

Decimal = 4
```

---

## Example 2

```
Index = 10

Binary:

1010

LSB:

0010

Decimal = 2
```

---

## Query Movement

```
index -= index & (-index)
```

Moves upward toward the root while collecting prefix sums.

Example:

```
13

↓

12

↓

8

↓

0
```

---

## Update Movement

```
index += index & (-index)
```

Moves to parent nodes to update cumulative values.

Example:

```
5

↓

6

↓

8

↓

16
```

---

## Why This Works

The Least Significant Set Bit determines the size of the interval represented by each node.

By adding or removing the LSB, the algorithm quickly jumps between relevant ranges without visiting every element.

---

Understanding `index & (-index)` is the key to mastering Fenwick Trees and many advanced bit manipulation techniques.