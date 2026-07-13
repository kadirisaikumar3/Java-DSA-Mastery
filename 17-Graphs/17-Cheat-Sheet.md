# 📋 Graph Cheat Sheet

## Common Algorithms

- BFS
- DFS
- Topological Sort
- Dijkstra
- Bellman-Ford
- Floyd-Warshall
- Kruskal
- Prim
- Union-Find

---

## Complexity

| Algorithm | Time |
|-----------|------|
| BFS | O(V + E) |
| DFS | O(V + E) |
| Topological Sort | O(V + E) |
| Dijkstra | O(E log V) |
| Kruskal | O(E log E) |
| Prim | O(E log V) |

---

## Pattern Recognition

Need shortest path?

↓

Unweighted → BFS

Positive Weights → Dijkstra

Negative Weights → Bellman-Ford

Need connectivity?

↓

DFS / BFS

Need cycle detection?

↓

DFS / Union-Find

Need dependency order?

↓

Topological Sort

Need minimum cost?

↓

MST

---

## Golden Rule

First identify the graph type, then choose the appropriate algorithm.