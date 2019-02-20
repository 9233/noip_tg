# AlldreamNOIP

this is for codes and problem solvings to save

## Dir

ppt还没想好怎么放在git上，感觉一堆ppt文件比较大，大伙可以拿这里的md当草稿，写完贴一些内容放ppt，ppt太满了写md解题报告

文件夹是对应的章节，内有各种题目的题解，如需引用图片建议在文件夹内创一个 `pic` 文件夹然后引用，github目前不兹瓷 `latex`，建议大家先写个 `latex` 正式版的然后截个图在旁边

`codes`里面是ac代码的总览（按oj分类）、

## Outline

1. **热身练习**: 简单模拟, dfs, bfs, 简单dp, 位运算简单技巧(sum_xor)
2. **模拟类问题**: P1003 铺地毯,P1067 多项式输出, P1540 机器翻译, P1056 排座椅, P1328 生活大爆炸版石头剪刀布, P1563 玩具谜题, P1023 税收与补贴问题, P1031 均分纸牌, P1042 乒乓球, P1086 花生采摘, P1098 字符串的展开
3. **高精度计算**: (P1601, P2142, P1303, P1255, P1604)
4. **堆**（二叉树复习，堆，堆排序，优先队列）
5. **贪心算法进阶**: 直观&最好需要数学证明最优性-调整法(P1090, P1181, P1208, P1223, P1094, P1803, P1031, P1080, P1080, P1158)(主要练习sort, struct, cmp, 优先队列)
6. **搜索建模**: DFS和BFS, 隐式图转化(搜索建模), 
7. **搜索优化**: 剪枝优化(1.可行性优化  2.最优性优化  3.记忆化)(P1092 虫食算 P1731, 生日蛋糕 P3230比赛)
8. **字符串初阶**: (KMP(find))
9. **图论基础**: 图的概念与遍历, 拓扑排序, 欧拉回路
10. **图论常用算法1**: 并查集(tree), 生成树(kruskal, prim),二分图
11. **图论常用算法2**: 图的最短路径，最短路变形(dj堆优化, spfa(Bellman Ford), floyd)
12. **动态规划1**: 记忆化搜索, DP经典模型（线性、背包、区间、树状）
13. **区间数据结构**: 树状数组, 线段树
- ------------96课时分割线------------
14. **搜索进阶**: 迭代加深策略, 搜索顺序的选择
15. **动态规划2**: 优化(单调队列优化背包问题51nod-1158 全是1的最大子矩阵)(一切形式如f[i]=min/max(g[j]) 且需要满足条件a[i]>=a[j]或者a[i]<=a[j]形式的动态规划，都可以采用单调队列优化)(jcx)
16. **二分答案进阶**: 借教室, 架设电话线, 关押罪犯, 聪明的质检员
17. **图论问题建模**: 一般问题对图论问题的转换
18. **字符串进阶**: (tire)
19. **初等数论**: 欧拉筛，中国剩余定理，同余，逆元，扩欧
20. **组合数学**: 常用组合数处理（杨辉，费马小定理，卢卡斯定理），容斥原理，二项式
21. **线性代数**: 矩阵基础, 矩阵快速幂, 高斯消元,现代机器学习方法
22. **图论高级算法**: LCA, Tarjan
23. **考试技巧**: 构造数据, 分段得分, 骗分


## Schedule

章节|课件进度| 课件二轮|题目进度 | 题目总结
--- | --- |---| --- | ---
01 热身 | 路天一 || 朱景亮 |
02 模拟 | 路天一 || 周博 |
03 高精度 | 路天一 || |
04 堆 | 路天一 || | 吉嘉铭牛逼
05 贪心进阶 | 蒋承旭(3/3) || |
06 搜索建模 | 陈伟文 || 朱明清 |
07 搜索优化 | 陈伟文 || |
08 字符串初阶 | 路天一 ||  | wcn
09 图论基础| 王浩泽(1/1)| 蒋涵欣 | zmq |
10 图论算法1 | 路天一 || 朱明清 |
11 图论算法2 | 陈伟文 || lx |
12 动态规划1 | 吉嘉铭(5/5) || 朱明清, 凌晓 |
13 区间数据结构| 路天一 || 朱明清 |
14 搜索进阶 | 陈伟文 || |
15 动态规划2 | 蒋承旭 || |
16 二分答案进阶 | 吉嘉铭, 陈伟文 || 姚金辉 |
17 图论问题建模 | 陈伟文 || | 姚金辉
18 字符串进阶 | 路天一 || 姚金辉 | 朱明清
19 初等数论 | 蒋承旭(2/2) || | csf
20 组合数学 | 王浩泽 || 姚金辉 |
21 线性代数 | 姚金辉 || 姚金辉 |
22 图论高级算法 | 郭恒康 || lx |
23 考试技巧 | 陈伟文 || 陈伟文 |

## markdown tips:

- 最后我统一转成 `.docx` 上传 `teambition`
- 注意文件名尽量不要包含空格与特殊字符（包括md文件与图片文件）
- 引用图片在章节目录下创建`images`子文件夹，然后上传
- 关于数学公式，`latex` 是个好东西，可是 `gayhub` 不兹瓷，不过pandoc兹瓷，所以大家可以写着（最好顺带附一张公式的截图），这样`github`和最后的`doc`文件都能很优雅，~~懒的话就贴张图吧~~

