# Data Structures and Algorithms Practice 2 


### 1. **Find the Shortest Path in a Maze:**

---

**Problem:**

Given a 2D maze, find the shortest path from the top-left corner to the bottom-right corner. You can move in four directions: up, down, left, and right. The maze is represented by a matrix where 0 represents an open cell and 1 represents a wall.

**Sample Input:**

```
[[0, 1, 0, 0, 0],
 [0, 1, 0, 1, 0],
 [0, 0, 0, 1, 0],
 [1, 1, 1, 0, 0],
 [0, 0, 0, 0, 0]]
```

**Expected Output:**

```
Shortest Path: [(0, 0), (1, 0), (2, 0), (2, 1), (2, 2), (2, 3), (2, 4), (3, 4), (4, 4)]
```

### 2. **LRU Cache Implementation:**

---

**Problem:**

Implement an LRU (Least Recently Used) cache. It should support get and put operations. When the cache reaches its capacity, it should evict the least recently used item before inserting a new item.

**Sample Input:**

```
Cache capacity: 3
cache.put(1, 1)
cache.put(2, 2)
cache.put(3, 3)
cache.get(2)
cache.put(4, 4)
cache.get(1)
```

**Expected Output:**

```
Cache State: {3: 3, 2: 2, 4: 4}
Cache Hit: 2
```

### 3. **Detect a Cycle in a Directed Graph:**

---

**Problem:**

Given a directed graph, detect if there is a cycle in it.

**Sample Input:**

```
Graph:
0 -> 1, 1 -> 2, 2 -> 0
```

**Expected Output:**

```
Cycle Detected!
```

### 4. **Longest Increasing Subsequence:**

---

**Problem:**

Given an unsorted array of integers, find the length of the longest increasing subsequence.

**Sample Input:**

```
[10, 22, 9, 33, 21, 50, 41, 60, 80]
```

**Expected Output:**

```
Length of LIS: 6 (The LIS is [10, 22, 33, 50, 60, 80])
```

### 5. **Minimum Spanning Tree:**

---

**Problem:**

Given an undirected graph and its edge weights, find the minimum spanning tree using Kruskal's or Prim's algorithm.

**Sample Input:**

```
Graph:
0 --2-- 1
|      /|
4-9-3--5
|   | /
7--6
```

**Expected Output:**

```
Minimum Spanning Tree Edges: [(0, 1), (1, 2), (2, 3), (2, 5), (3, 4), (4, 7), (5, 6)]
```

Feel free to dive into these problems and implement solutions!
