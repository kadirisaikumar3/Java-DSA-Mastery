# ☕ Java Code Templates

---

# Min Heap

```java
PriorityQueue<Integer> minHeap = new PriorityQueue<>();

minHeap.offer(5);
minHeap.offer(2);
minHeap.offer(8);

System.out.println(minHeap.poll());
```

---

# Max Heap

```java
PriorityQueue<Integer> maxHeap =
    new PriorityQueue<>(Collections.reverseOrder());

maxHeap.offer(5);
maxHeap.offer(2);
maxHeap.offer(8);

System.out.println(maxHeap.poll());
```

---

# K Largest Elements

```java
PriorityQueue<Integer> minHeap = new PriorityQueue<>();

for(int num : nums){

    minHeap.offer(num);

    if(minHeap.size() > k)

        minHeap.poll();

}
```

---

# Heap Sort (Concept)

```java
PriorityQueue<Integer> heap = new PriorityQueue<>();

for(int num : nums)

    heap.offer(num);

while(!heap.isEmpty())

    System.out.print(heap.poll() + " ");
```

---

# Interview Tip

For Top-K problems:

- K Largest → Min Heap
- K Smallest → Max Heap