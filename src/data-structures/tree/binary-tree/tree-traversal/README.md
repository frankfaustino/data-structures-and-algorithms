# Tree Traversal
**Tree traversal** (tree search) refers to the process of visiting each node in a tree exactly once.

Because from a given node there is more than one possible next node (not a linear data structure), then, assuming sequential computation (not parallel), some nodes _must_ be deferred—stored in some way for later visiting. This is often done via a [stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) (LIFO) or [queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) (FIFO). As a tree is a self-referential (recursively defined) data structure, traversal can be done by recursion or [corecursion](https://en.wikipedia.org/wiki/Corecursion); in these the cases the deferred nodes are stored implicitly in the [call stack](https://en.wikipedia.org/wiki/Call_stack).

**Depth-first search** is easily implemented via a stack, including recursively (via the call stack), while **breadth-first search** is easily implemented via a queue, including corecursively.

### Depth-first search (DFS)
There are three common ways to traverse a binary tree in depth-first order: **in-order**, **pre-order** and **post-order**.

#### In-order

<img src="../../../../../assets/tree_traversal_DFS_inorder.png" />



<hr>

[← go back to trees](../../)