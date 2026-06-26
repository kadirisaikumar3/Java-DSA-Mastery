# 💾 Space Complexity

---

# What is Space Complexity?

Space Complexity measures the total amount of memory required by an algorithm during execution.

It includes:

- Input Space
- Auxiliary Space (Extra Memory)

Interviewers usually ask for **Auxiliary Space Complexity**.

---

# Components of Space Complexity

## 1. Input Space

Memory required to store the input.

Example:

```
int[] arr = new int[n];
```

Input Space

```
O(n)
```

---

## 2. Auxiliary Space

Extra memory used by the algorithm.

Example:

```
int sum = 0;
```

Auxiliary Space

```
O(1)
```

---

# Examples

## Example 1

Finding Maximum Element

```java
int max = arr[0];

for(int num : arr){
    if(num > max)
        max = num;
}
```

Extra Variables

```
max
num
```

Auxiliary Space

```
O(1)
```

---

## Example 2

Copy Array

```java
int[] copy = new int[n];

for(int i=0;i<n;i++)
    copy[i]=arr[i];
```

Extra Array

```
n elements
```

Auxiliary Space

```
O(n)
```

---

## Example 3

Matrix

```java
int[][] matrix = new int[n][n];
```

Auxiliary Space

```
O(n²)
```

---

# Recursive Space

Every recursive call occupies stack memory.

Example

```java
factorial(n)
```

Stack Frames

```
n
```

Auxiliary Space

```
O(n)
```

---

# Interview Tip

Always specify:

Time Complexity

AND

Auxiliary Space Complexity.

---

# Summary

| Algorithm | Auxiliary Space |
|------------|-----------------|
| Linear Search | O(1) |
| Binary Search (Iterative) | O(1) |
| Binary Search (Recursive) | O(log n) |
| Merge Sort | O(n) |
| Quick Sort | O(log n) Average |