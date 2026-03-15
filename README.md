# 🌳 Maximum Level Sum in a Binary Tree

## 📌 Overview

This project solves the **Maximum Level Sum of a Binary Tree** problem.

The objective is to determine **which level of the binary tree has the maximum sum of node values**.
The solution uses **Breadth First Search (BFS)**, also known as **Level Order Traversal**, to process the tree level by level.

This is a common **Binary Tree problem asked in coding interviews and platforms like LeetCode**.

---

# 🎯 Problem Statement

Given the **root of a binary tree**, compute the **sum of node values at each level** and return the **level number that has the maximum sum**.

Notes:

* Levels are **1-indexed**
* If multiple levels have the same sum, return the **smallest level number**

---

# 🌿 Example

Binary Tree:

```
        1
       / \
      7   0
     / \
    7  -8
```

Level sums:

| Level | Nodes | Sum |
| ----- | ----- | --- |
| 1     | 1     | 1   |
| 2     | 7, 0  | 7   |
| 3     | 7, -8 | -1  |

Result:

```
Level 2 has the maximum sum
```

---

# ⚙️ Approach

The algorithm uses **Breadth First Search (BFS)** with a **Queue**.

Steps:

1. Start traversal from the root node.
2. Process the tree **level by level**.
3. For each level:

   * Calculate the sum of node values.
4. Compare the sum with the current maximum sum.
5. Update the **maximum level** if a larger sum is found.

---

# 🔁 Traversal Strategy

The algorithm follows this workflow:

```
Binary Tree
     ↓
Level Order Traversal (BFS)
     ↓
Compute sum of nodes at each level
     ↓
Track the level with the maximum sum
     ↓
Return the level number
```

---

# ⏱ Time and Space Complexity

| Complexity       | Value |
| ---------------- | ----- |
| Time Complexity  | O(n)  |
| Space Complexity | O(n)  |

Where **n** is the number of nodes in the tree.

---

# 🧠 Concepts Used

* 🌳 Binary Trees
* 🔁 Breadth First Search (BFS)
* 📊 Queue Data Structure
* 📈 Level-based Computation

---

# 🎯 Learning Outcomes

After completing this problem you will understand:

✔ How **Level Order Traversal** works
✔ How to process binary trees **level by level**
✔ How to compute **aggregated values per level**
✔ How BFS helps solve tree problems efficiently

These concepts are frequently used in **DSA interviews and competitive programming**.

---

# 👨‍💻 Author

Developed as part of **Data Structures and Algorithms (DSA) practice** 🚀
