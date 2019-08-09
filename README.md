# Algorithms--

## 坐标型动态规划
- lintcode
- [553. 炸弹敌人](https://www.lintcode.com/problem/bomb-enemy/description) 
- [110. 最小路径和](https://www.lintcode.com/problem/minimum-path-sum/description)
- leetcode
- [55. 跳跃游戏](https://leetcode.com/problems/jump-game/)

## 区间型动态规划
- 给定一个序列/字符串，进行一些操作，最后一步会将序列/字符串去头/去尾，剩下的会是一个区间[i,j]， 状态自然定义为f[i][j]，表示面对子序列[i,...j]时的最优性质。
- 按照长度j-i从小到大的顺序去算
- leetcode
- [516. Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/submissions/)
- Coins in a line III
- [312. Burst Balloons](https://leetcode.com/problems/burst-balloons/)

## 序列型动态规划
- 前i个... 最小/方式数/可行性
- 序列+状态
- lintcode
- [515. 房屋染色](https://www.lintcode.com/problem/paint-house/description) 
- [516. 房屋染色 II](https://www.lintcode.com/problem/paint-house-ii/description) 
- [392. 打劫房屋](https://www.lintcode.com/problem/house-robber/description) 
- [392. 打劫房屋 II](https://www.lintcode.com/problem/house-robber-ii/description) 
- [392. leetcode打劫房屋 II](https://leetcode.com/problems/house-robber-ii/)
- [149. 买卖股票的最佳时机](https://www.lintcode.com/problem/best-time-to-buy-and-sell-stock/description)
- [150. 买卖股票的最佳时机 II](https://www.lintcode.com/problem/best-time-to-buy-and-sell-stock-ii/description)
- [151. 买卖股票的最佳时机 III](https://www.lintcode.com/problem/best-time-to-buy-and-sell-stock-iii/description)


### 最长序列型动态规划（坐标型）
***要求找出符合条件的最长子序列*** 

***方法：记录以每个元素i结尾的最长子序列的长度；计算时，在i之前枚举子序列上一个元素是哪个。***  

- leetcode
- [354. Russian Doll Envelopes](https://leetcode.com/problems/russian-doll-envelopes/) 
- [300. Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/submissions/)
- lintcode
- [397. 最长上升连续子序列](https://www.lintcode.com/problem/longest-continuous-increasing-subsequence/my-submissions)



## 划分型动态规划
- 给定长度为N的序列或字符串，要求划分成若干段
- 做法：类似序列型DP，但是通常要加上段数信息；一般用f[i][j]记录前i个元素(0 ~ i-1)分成j段的性质，如最小代价。
- lintcode
- [512. 解码方法](https://www.lintcode.com/problem/decode-ways/description) 
- leetcode
- [279. Perfect Squares](https://leetcode.com/problems/perfect-squares/)
- [132. Palindrome Partitioning II](https://leetcode.com/problems/palindrome-partitioning-ii/submissions/)
- [437. 书籍复印](https://www.lintcode.com/problem/copy-books/description)


## 双序列型动态规划
***有两个序列，每个是一维的，用二维DP来做*** 
- lintcode
- [664. 数1](https://www.lintcode.com/problem/counting-bits/description) 
- [1143. Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
- [97. Interleaving String](https://leetcode.com/problems/interleaving-string/)
- [72. Edit Distance](https://leetcode.com/problems/edit-distance/submissions/)


## 序列+位操作型动态规划
- lintcode
- [664. 数1](https://www.lintcode.com/problem/counting-bits/description) 



## 博弈型动态规划
- lintcode
- [394. 硬币排成线](https://www.lintcode.com/problem/coins-in-a-line/description) 


## 背包型动态规划
***要把总承重放入状态！***  

- lintcode
### 可行型 ***
- 题面：要求不超过Target时能拼出的最大重量
- 记录f[i][w]=前i个物品能不能拼出重量w
- [92. 背包问题](https://www.lintcode.com/problem/backpack/description) 
### 计数型 ***
- 题面：要求有多少种方式拼出重量Target
- 记录f[i][w]=前i个物品有多少种方式拼出重量w
- Backpack
- [564. 组合总和 IV](https://www.lintcode.com/problem/combination-sum-iv/description) 
### 最值型 ***
- 题面：要求能拼出的最大价值
- 记录f[i][w]=前i个/种物品拼出重量w能得到的最大价值
- [125. 背包问题 II](https://www.lintcode.com/problem/backpack-ii/description) 
- Backpack III
