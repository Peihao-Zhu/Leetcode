# 7.2日刷题

今天的做题感觉还可以，主要是树相关的题目，遍历题（preorder，inorder，postorder），构建一棵树。



个人总结：关于树的题目基本都是dfs/bfs，用的方法可以是递归或者是迭代。

​	dfs：统计路径，判断树是否平衡

​	bfs：树的层次遍历，求最短路径

​	递归：代码很短，构建树的时候，经常需要使用分治的方法，找到root，划分左子树和右子树，不断使用递归。

​	迭代：，迭代的速度会比递归快，因为不用保存系统栈，树的三种遍历方式要掌握迭代。



**注意：第114题希望日后能好好重温一下，感觉这个思路很神奇，自己没有很好的掌握。**

| 编号 | 题目                                                       | 解体方法                                                     |
| ---- | ---------------------------------------------------------- | ------------------------------------------------------------ |
| 102  | Binary Tree Level Order Traversal                          | BFS                                                          |
| 101  | Symmetric Tree                                             | 用DFS和BFS（BFS节点放入队列的顺序要注意）                    |
| 105  | Construct Binary Tree from Preorder and Inorder Traversal  | 分治法，不断将区间划分为左子树和柚子树                       |
| 106  | Construct Binary Tree from Inorder and Postorder Traversal | 思路和105一样，唯一的区别就是postorder的最后一个节点是根节点 |
| 108  | Convert Sorted Array to Binary Search Tree                 | 将中间节点作为跟节点，然后划分左右子树。这样BST是平衡的      |
| 109  | Convert Sorted List to Binary Search Tree                  | 和108的区别是数组变成了链表，唯一的区别就是找中点的方式，使用快慢指针，每次用head和tail分割左右子树，其中[head,tail),最后slow就是中点 |
| 110  | Balanced Binary Tree                                       | dfs                                                          |
| 113  | Path Sum II                                                | Dfs+剪枝                                                     |
| 114  | Flatten Binary Tree to Linked List                         | 这题我没有做出来。后续有时间在看看。两种方法，迭代的和递归的，1.迭代：root的左子树接到root的右边，原来root的右子树接到左子树的最右边那个节点处，root=root.right 不断的重复上述步骤2.递归，本身是先序遍历，这题防止将前一个节点的右孩子指向当前节点时，丢失前一个节点本来的右孩子。所以使用后序遍历的更改版本，right,left,root 的顺序访问，当前节点的右孩子为前一个节点。 |

