# class 1 Introduction and Examples

[toc]

## 1 Mechanism Design: The Science of Rule-Making

用2012年伦敦奥运会上的案例来说明，一个好的机制可以让所有参与者都能尽全力发挥最好的水平，有时也不能完全责备钻漏洞的人

> https://zh.wikipedia.org/wiki/2012%E5%B9%B4%E5%A4%8F%E5%AD%A3%E5%A5%A7%E6%9E%97%E5%8C%B9%E5%85%8B%E9%81%8B%E5%8B%95%E6%9C%83%E7%BE%BD%E6%AF%9B%E7%90%83%E5%A5%B3%E5%AD%90%E9%9B%99%E6%89%93%E6%AF%94%E8%B3%BD#%E6%B6%88%E6%9E%81%E6%AF%94%E8%B5%9B%E4%BA%8B%E4%BB%B6



## 2 The Price of Anarchy: When Is Selfish Behavior
Near-Optimal?

**布雷斯悖论(Braess's Paradox)**描述一种在道路网络上增加通路反而使得网络上的旅行时间增加的现象->每个司机采取最优的策略->纳什均衡并不意味着通过网络的整体流量最佳

布雷斯悖论不只体现在通路结构中，去掉一些相连结构有时也能提升整体效率（线与弹簧结构）

**最坏均衡与最佳解比(Price of Anarchy)**衡量在一个博弈中，由于参与者的自私所导致整个系统的效能降低

目标是使得PoA尽量接近1，在每个人自私的情况下仍然能够接近最佳的系统效果



## 3  Complexity of Equilibria: How Do Strategic Players Learn?

**纳什均衡(Nash equilibrium)**参与的各方都不能在其他人收益不变的情况下增加自己的收益

剪刀石头布游戏没有确定的均衡，对手采取的是随机的策略，双方都不能通过偏离带来收益，一对具有这种性质的概率分布就是混合策略的纳什均衡。在随机化的情况下，每个游戏都至少有一个纳什均衡。

> 纳什定理：每个双矩阵博弈都有一个纳什均衡

剪刀石头布是一个零和博弈，双方的收益对之和均为0。

==如果一个双矩阵博弈是一个零和博弈，那么纳什均衡可以在多项式时间内计算得到。==使用线性规划或者迭代学习算法进行计算，可知纳什均衡概念可以很好地预测零和博弈的行为。

计算一般的(非零和)博弈没有多项式时间算法

计算纳什均衡是一个中等难度的问题-> PPAD-hard



## 4 What Computer Science Brings to the Table

传统的经济学方法强调精确解，计算机科学讨论复杂度和推广近似边界，精确解是不现实的，鼓励更加稳定的性能保证



## 5 Target Audience

计算机硕士、博1



