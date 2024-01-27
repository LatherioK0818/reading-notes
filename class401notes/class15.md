**Trees Cheat Sheet**

This cheat sheet covers the basics of Binary Trees, Binary Search Trees, and K-ary Trees, including common terminology and traversal methods.

---

### Common Terminology
- **Node**: A component containing its own values and references to other nodes.
- **Root**: The beginning node of the tree.
- **K**: In a k-ary tree, the maximum number of children any node may have. For binary trees, k = 2.
- **Left/Right**: In a binary tree, references to the two possible child nodes.
- **Edge**: The link between a parent and a child node.
- **Leaf**: A node without children.
- **Height**: Number of edges from the root to the furthest leaf.

### Tree Traversals

Traversal of trees is essential for searching nodes, printing contents, etc. They are broadly categorized into:

1. **Depth-First Traversals**
   - **Pre-order (Root, Left, Right)**: Visit root, then left subtree, and finally right subtree.
   - **In-order (Left, Root, Right)**: Visit left subtree, root, and then right subtree.
   - **Post-order (Left, Right, Root)**: Visit left subtree, right subtree, and finally the root.

2. **Breadth-First Traversal**
   - Traverses each level of the tree node-by-node.

### Binary Tree vs. K-ary Trees
- **Binary Tree**: Each node has up to two children. There's no specific order for node placement.
- **K-ary Tree**: Nodes can have up to k children. Similar breadth-first traversal approach, but with potentially more children per node.

### Adding a Node
- In a binary tree, add the new node where there's space, often from the top down, filling child spots from left to right.
- The insertion process often uses breadth-first traversal.
- **Big O Complexity**: O(n) for insertion and search due to lack of structure. For insertion, O(w) in space complexity, where w is the tree's width.

### Binary Search Trees (BST)
- Organized so that values less than the root go left, and values greater go right.
- Searching involves comparing the target value to the root or sub-root and choosing the appropriate subtree to continue the search.
- **Big O Complexity**: Time complexity for insertion and search is O(h), where h is the height of the tree. Space complexity during a search is O(1).

### Traversal Pseudocode
- **Pre-order**:
  ```
  ALGORITHM preOrder(root)
      OUTPUT <-- root.value
      if root.left is not NULL
          preOrder(root.left)
      if root.right is not NULL
          preOrder(root.right)
  ```
- **In-order**:
  ```
  ALGORITHM inOrder(root)
      if root.left is not NULL
          inOrder(root.left)
      OUTPUT <-- root.value
      if root.right is not NULL
          inOrder(root.right)
  ```
- **Post-order**:
  ```
  ALGORITHM postOrder(root)
      if root.left is not NULL
          postOrder(root.left)
      if root.right is not NULL
          postOrder(root.right)
      OUTPUT <-- root.value
  ```
- **Breadth-first**:
  ```
  ALGORITHM breadthFirst(root)
      Queue breadth <-- new Queue()
      breadth.enqueue(root)
      while ! breadth.is_empty()
          node front = breadth.dequeue()
          OUTPUT <-- front.value
          if front.left is not NULL
              breadth.enqueue(front.left)
          if front.right is not NULL
              breadth.enqueue(front.right)
  ```
