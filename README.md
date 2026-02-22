
 Height of a Binary Tree in C

This project implements a C program to calculate the **height of a binary tree** using recursion.

It demonstrates core concepts of tree data structures, dynamic memory allocation, and recursive algorithms.

---

 Concept Overview

 Binary Tree

A Binary Tree is a hierarchical data structure in which:

- Each node contains data
- Each node has at most two children:
  - Left child
  - Right child

---

 Definition of Height

The **height of a binary tree** is defined as:

> The number of edges in the longest path from the root node to a leaf node.

In this implementation:

- Height of an empty tree = **-1**
- Height of a single-node tree = **0**

---

 🧠 Algorithm Used

The height is calculated using recursion.
 Steps:

1. If the node is `NULL`, return `-1`.
2. Recursively calculate:
   - Height of left subtree
   - Height of right subtree
3. Return the maximum of the two heights + 1.

