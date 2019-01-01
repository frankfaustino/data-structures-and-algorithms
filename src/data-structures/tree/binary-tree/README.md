## Binary Tree
Trees are commonly represented as **binary trees**, a _rooted_ tree structure in which each node has no more than two children.

<img src="../../../../assets/binary_tree.svg" width="600" />

A **node** of a binary tree is represented by a structure containing **data** and two pointers (__left__ and __right__) to other structures of the same type.

<p align="center">
  <img src="../../../../assets/binary_tree_node.svg" width="300" />
</p>

An example of a node written in JavaScript:
```js
class Node {
  constructor(value = null) {
    this.value = value
    this.left = null
    this.right = null
  }
}
```

<hr>

[← go back to trees](../)