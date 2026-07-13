# ☕ Java Code Templates

---

# BFS

```java
Queue<Integer> q = new LinkedList<>();

q.offer(start);

while(!q.isEmpty()){

    int node = q.poll();

}
```

---

# DFS

```java
void dfs(int node){

    visited[node] = true;

}
```

---

# Union-Find

```java
int find(int x){

    if(parent[x] != x)

        parent[x] = find(parent[x]);

    return parent[x];

}
```

---

# Dijkstra

```java
PriorityQueue<Pair> pq =
new PriorityQueue<>(
(a,b)->a.dist-b.dist);
```

---

# Topological Sort

```java
Queue<Integer> queue =
new LinkedList<>();
```

---

# Interview Tip

Master these templates before attempting advanced graph problems.