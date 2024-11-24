# Red-Black Trees

## Overview
A **Red-Black Tree** is a type of self-balancing binary search tree used to maintain sorted data efficiently. It ensures the tree's height is kept logarithmic, providing consistent performance for common operations like insertion, deletion, and search.

---

## Key Properties
1. **Node Colors**: Each node is either `Red` or `Black`.
2. **Root Node**: The root node is always `Black`.
3. **Red Rule**: No two consecutive red nodes appear on a single path (i.e., a red node cannot have a red parent or child).
4. **Black Height**: Every path from a node to its descendant `null` nodes has the same number of black nodes.
5. **Balanced**: The longest path in the tree is at most twice as long as the shortest path.

---

## Operations
### 1. **Search**
   - Follows the standard binary search tree traversal.
   - Time complexity: `O(log n)`.

### 2. **Insertion**
   - Insert like a binary search tree.
   - Adjust colors and rotate to maintain properties.

### 3. **Deletion**
   - Remove the node like a binary search tree.
   - Rebalance by adjusting colors and rotations.

---

## Rotations
- **Left Rotation**: Moves a node to the left to rebalance.
- **Right Rotation**: Moves a node to the right to rebalance.

---

## Use Cases
1. **Databases**: Used in implementations of maps, sets, and associative arrays (e.g., Java's `TreeMap` and `TreeSet`).
2. **Operating Systems**: Used in Linux's Completely Fair Scheduler (CFS).
3. **Networking**: Efficiently manage routing tables.

---

## Advantages
- Guaranteed `O(log n)` complexity for search, insert, and delete.
- Maintains a relatively balanced tree structure.



