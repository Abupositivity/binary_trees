Binary Tree

A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child. The topmost node in the tree is called the root node, and each node in the tree can have zero, one, or two children nodes.

The main difference between a binary tree and a Binary Search Tree (BST) lies in the organization of nodes and the rules governing their arrangement:

In a binary tree, nodes are organized in a hierarchical structure without any specific order. There are no restrictions on how nodes are placed relative to each other.
In a Binary Search Tree (BST), nodes are organized in such a way that for each node:
All nodes in the left subtree have values less than the node's value.
All nodes in the right subtree have values greater than the node's value.
This organization enables efficient searching, insertion, and deletion operations, as it allows for binary search techniques to be applied.
The possible gain in terms of time complexity compared to linked lists depends on the operation being performed:

For searching, insertion, and deletion operations, Binary Search Trees (BSTs) offer a time complexity of O(log n) on average, where n is the number of nodes in the tree. This is significantly faster than linear search operations on linked lists, which have a time complexity of O(n).
However, the time complexity of BST operations can degrade to O(n) in the worst-case scenario if the tree becomes unbalanced.
The depth of a binary tree is the length of the longest path from the root node to a leaf node. The height of a binary tree is the length of the longest path from the root node to the deepest leaf node. The size of a binary tree is the total number of nodes in the tree.

Different traversal methods to go through a binary tree include:

Inorder Traversal: Visit the left subtree, then the root node, and finally the right subtree.
Preorder Traversal: Visit the root node, then the left subtree, and finally the right subtree.
Postorder Traversal: Visit the left subtree, then the right subtree, and finally the root node.
Level-order Traversal (Breadth-First Traversal): Visit nodes level by level, starting from the root node and moving to the next level before traversing deeper.
A complete binary tree is a binary tree in which every level, except possibly the last, is completely filled, and all nodes are as far left as possible. A full binary tree is a binary tree in which every node has either zero or two children. A perfect binary tree is a binary tree in which all internal nodes have exactly two children, and all leaf nodes are at the same level. A balanced binary tree is a binary tree in which the height of the left and right subtrees of every node differs by no more than one.





