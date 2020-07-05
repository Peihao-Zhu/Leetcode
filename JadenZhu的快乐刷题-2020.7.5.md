# 7月4日

今天题目基本都是回溯法，所以基本上对这种体型有一种感觉了，希望再接再厉！

75题Sort Colors的快排的partition方法比较神奇，需要好好揣摩。

关于回溯的题目，还下面这些比较有代表性的题目。

![image-20200705094504756](/Users/zhupeihao/Library/Application Support/typora-user-images/image-20200705094504756.png)

| 编号 | 题目              | 解题方法                                                     |
| ---- | ----------------- | ------------------------------------------------------------ |
| 55   | Jump Game         | 用回溯法gg了，原来一次遍历就能直接求出来，只要判断能到达的最远距离就可以了。 |
| 73   | Set Matrix Zeroes | 使用常数空间，就把原矩阵的第一行和第一列作为其他部分的标记，那第一行和第一列可以单独用一个变量来判断是否需要置0 |
| 75   | Sort Colors       | 遍历一边的方法，要熟悉快排的partition，![image-20200705094409137](/Users/zhupeihao/Library/Application Support/typora-user-images/image-20200705094409137.png) |
| 78   | Subsets           | 依旧用回溯                                                   |
| 79   | Word Search       | 回溯                                                         |
| 91   | Decode Ways       | 1.用dfs需要剪枝，不然会超时2.dp没有搞懂，有时间在看          |

