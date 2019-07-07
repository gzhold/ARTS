#ARTS
1.Algorithm：每周至少做一个 leetcode 的算法题
2.Review：阅读并点评至少一篇英文技术文章
3.Tip：学习至少一个技术技巧
4.Share：分享一篇有观点和思考的技术文章


第一周打卡：
binary search : https://www.jianshu.com/p/b8cb09357f54

第二周打卡：
btrace & Arthas : https://tech.meituan.com/2019/02/28/java-dynamic-trace.html
hashtable : https://www.jianshu.com/p/b8e2945253b4

第三周打卡:
leetcode: https://leetcode.com/problems/majority-element/
求众数，两种实现方式：
1 hashmap
2 先排序，再取下标为len/2的值

分享：spark shuffle  https://wongxingjun.github.io/2016/05/27/Spark%E6%9E%B6%E6%9E%84%E4%B9%8Bshuffle/
      https://gregable.com/2013/10/majority-vote-algorithm-find-majority.html
算法：
 朴素贝叶斯 https://www.jianshu.com/p/0eb79c2dcbd0
 决策树 https://www.jianshu.com/p/d3c3cc6d6be6

第四周打卡：
leetcode：https://leetcode.com/problems/first-missing-positive/submissions/
缺失的最小正整数：部分数据比较并替换，排好序后再依次遍历。
share: spark memory management https://0x0fff.com/spark-memory-management/
svm demo : https://www.jianshu.com/p/40a99cdb05fd

第五周打卡：
knn： https://www.jianshu.com/p/216ce159674a
leetcode: 这周主要是练习链表操作，完成leetcode 206， 141， 21

第六周打卡
leetcode: 实现876    整理代码：https://github.com/gzhold/LeetCode
k-means: https://www.jianshu.com/u/33ecd2f36973
代码实现都保存在本地，未开放出来，等后续整理好一起提交。

第七周打卡：
leetcode： https://leetcode.com/problems/design-circular-deque/  双链表实现
学习xpath的使用，python实现微博自动化关注

第八周打卡：
leetcode: Climbing Stairs 数组实现，递归实现leetcode提交超时，本地单元测试可以，运行速度较慢
词云的demo实现以及图形化展示，python的列表和元组重新学习

第九周打卡：
leetcode：Climbing Stairs  python数组实现
Sliding Window Maximum：python双端队列实现

信用卡违约分析： python比较各个算法的准确率（svm，决策树，随机森林，adaboost，knn）
信用卡诈骗分析： python逻辑回归实现

第十周打卡：
leetcode:  
1 Kth Largest Element in an Array  快排的思路， 分区+ 递归实现（另一种：min heap）
2 Merge k Sorted Lists    min heap（另一种：数组+排序）

study： https://www.kaggle.com/learn-forum/53782 （roc & auc）

实现demo：
沪市指数走势预测，使用时间序列 ARMA  

第十一周打卡：
这周主要是数据结构的练习
（1）Remove Duplicates from Sorted Array  通过比较临近的两个元素，不想等就替换值
（2）Missing Number 高斯函数
（3）Kth Largest Element in an Array 快排，取下表len（nums）-k的值

第十二周：
1 Longest Substring Without Repeating Characters    python  字典实现
2 Pow(x, n)   二分查找实现

3 java AQS实现原理
4 java  线程池实现原理。

第十三周：
1 Path Sum     递归实现,思路：sum-val 递归递减，直到为0
2 Validate Binary Search Tree 递归实现,思路：max, min
3 Maximum Depth of Binary Tree   递归实现， 思路：max(left, right)+1
4 classload理解
5 jdk spi理解

第十四周：
1 Binary Tree Inorder Traversal，Binary Tree Preorder Traversal， Binary Tree Postorder Traversal    递归，栈实现
2 Kth Smallest Element in a BST 中序遍历实现
3 Minimum Distance Between BST Nodes 中序遍历实现
4 开始学习dubbo源码
学习总结：dubbo 对spi扩展
（1）jdkspi仅仅通过接口类名获取所有实现，而ExtensionLoader则通过接口类名和key值获取一个实现；
（2）Adaptive实现，就是生成一个代理类，这样就可以根据实际调用时的一些参数动态决定要调用的类了。
（3）自动包装实现，这种实现的类一般是自动激活的，常用于包装类，比如Protocol的两个实现类：ProtocolFilterWrapper、ProtocolListenerWrapper。
