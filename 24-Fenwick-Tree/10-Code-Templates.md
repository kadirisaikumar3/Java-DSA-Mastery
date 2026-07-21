# Java Code Templates

## Fenwick Tree Implementation

```java
class FenwickTree {

    private int[] bit;
    private int n;

    public FenwickTree(int size) {
        n = size;
        bit = new int[n + 1];
    }

    public void update(int index, int value) {
        while (index <= n) {
            bit[index] += value;
            index += index & (-index);
        }
    }

    public int query(int index) {
        int sum = 0;

        while (index > 0) {
            sum += bit[index];
            index -= index & (-index);
        }

        return sum;
    }

    public int rangeQuery(int left, int right) {
        return query(right) - query(left - 1);
    }
}
```

---

## Example Usage

```java
FenwickTree tree = new FenwickTree(5);

tree.update(1, 2);
tree.update(2, 4);
tree.update(3, 1);
tree.update(4, 7);
tree.update(5, 3);

System.out.println(tree.query(5));

System.out.println(tree.rangeQuery(2, 4));
```