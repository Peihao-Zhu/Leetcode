# 7.1日刷题

今天题目做的云里雾里的，看了两波电影 妇联3和美队3。主要是被最后一题搞得头晕了， easy题弄的心态很崩。

**注意：最后一题的环状替换法，有空要重温一下，感觉看了人家的题解以后能写出来，自己还没有真正的掌握**

| 编号 | 题目                          | 解体方法                                                     |
| ---- | ----------------------------- | ------------------------------------------------------------ |
| 94   | Binary Tree Inorder Traversal | 递归方式比较简单迭代方式要掌握，用颜色标记法                 |
| 98   | Validate Binary Search Tree   | 中序遍历的结果是递增的，按照中序遍历，用一个常数变量pre记录前一个节点，和当前节点比较 |
| 162  | Find Peak Element             | 二分的简单变种                                               |
| 200  | Number of Islands             | Dfs/bfs                                                      |
| 179  | Largest Number                | 用sort，自定义一个比较器，使用String 的CompareTo进行比较     |
| 169  | Majority Element              | 摩尔投票法：count表示众数相对于其他数出现的次数，candidate为该众数。遍历的时候，如果count=0，新来的那个数就是candidate，如果candidate和新来的数相等，count++，否则count--；hash表：key是值 value是值出现的次数 |
| 189  | Rotate Array                  | 暴力/使用额外数组/环状替换/反转数组                          |

