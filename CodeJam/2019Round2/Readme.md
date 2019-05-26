# 2019 Round 1 Sub-Round C

-   Score : 48
-   Rank : 349
-   这场真的自闭了。。。

---

## A

- 能造成区别的是两种元素重量的比值
- 可能有先后区别的一对当且仅当$(C_1 - C_2) \times (J_1 - J_2) < 0$
- 他们先后的区分事实上是和对应分数的大小关系
- 找到这$k$个分界点，会把整个数轴分成$k + 1$个区间，答案就是$k + 1$

## B

- 一个不知道说什么的题目

- 看起来其实还挺有意思的

- 策略按照[题解](https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/00000000001461c8#)写的来就好

## C

- 继承了$A$题的思路
- 找到这$k + 1$个区间后，在每个区间里找满足最小要求的分数
- 判断这个分数是否可行
- 找分数事实上是法雷序列

## D

- 细节很多的一个题
- 本质上只需要想清楚什么情况下会`UNBOUNDED`
- 具体题解参见[这里](<https://codingcompetitions.withgoogle.com/codejam/round/0000000000051679/0000000000146185>)