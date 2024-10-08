**Author:** Mackenzie Anderson

**GitHub username:** mkenzieanderson

**Date:** February 2024

The following files contain a python implementation of the binary search tree and AVL tree data structures. Both of these tree implementations utilize additionally defined queue and stack data structures for specific methods within their respective classes. Finally, both tree files contain testing code at the end, which also works as a sample of how these tree data structures could be utilized.

In particular, the AVL tree implementation is height-balanced. The height-balance is maintained by checking the balance factor of any affected nodes after a node removal or insertion. If any balance factor exceeds the absolute value of 1, then one or two rotations are performed to restore height balance. As a result, the standard operations of the AVL tree run at O(log(n)) complexity. The binary search tree is not guaranteed to be height-balanced. Therefore, the binary search tree operations run at best case, O(log(n)), and worst case, O(n).
