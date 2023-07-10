# Leetcode 111. Minimum Depth of Binary Tree (Easy)

# Problem 

Given a binary tree, find its minimum depth.

The minimum depth is the number of nodes along the shortest path from the root node down to the nearest leaf node.

Note: A leaf is a node with no children.

# Solution O(N)

Using BFS I check each level of the tree for leaf nodes, adding child nodes to the queue to check in the next levelin case there are no leaf nodes at that depth,
if there are no leaf nodes increment depth by one and check the next level
