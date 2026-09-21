---
title: "Paper Accepted by Computers and Electronics in Agriculture | 杨琳同学论文获《Computers and Electronics in Agriculture》接收"
date: 2026-09-18
authors:
  - Codex
---

We are delighted to announce that our paper, **“Harvesting Sequence Optimization for Clustered Strawberries Using a Fruit-Level Harvesting Difficulty Score,”** has been accepted for publication in **Computers and Electronics in Agriculture**.

The paper is led by **Lin Yang (杨琳)**, a Master's student and the first author. The co-authors are **Shimin Hu, Meili Sun, and Ya Xiong**. This research was conducted by the Intelligent Equipment Research Center at the Beijing Academy of Agriculture and Forestry Sciences, in collaboration with the College of Information Science and Engineering at Shandong Agricultural University.

<!--more-->

## English

Harvesting strawberries that grow in dense clusters is challenging because individual fruits can differ substantially in accessibility, occlusion, and collision risk. Existing harvesting-sequence planning methods mainly aim to minimize manipulator travel distance, but often overlook the difficulty of harvesting each fruit.

This study proposes a difficulty-aware harvesting-sequence optimization framework. It combines:

- a fruit-level **Harvesting Difficulty Score (HDS)** predicted by a two-stage convolutional neural network;
- dynamic HDS updates after each virtual fruit removal; and
- weighted multi-criteria sequence planning using genetic-algorithm-based (**MOP-GA**) and simulated-annealing-based (**MOP-SA**) solvers.

The HDS regression model achieved a mean absolute error of **6.55%** and an **R² of 72.39%**. In offline experiments, MOP-GA reduced the average HDS per fruit to **0.282**, compared with **0.291** for the travelling salesman problem (TSP) strategy and **0.297** for the bottom-up strategy.

Indoor robotic harvesting experiments across nine strawberry-cluster scenes further demonstrated lower HDS values for MOP-GA (**0.197**) and MOP-SA (**0.204**) than for TSP (**0.235**) and bottom-up (**0.237**). MOP-GA also achieved a lower observed harvesting failure rate than TSP (**19.11% versus 26.67%**), although the overall difference in failure probability among the methods was not statistically significant.

These results show that dynamically incorporating fruit-level harvesting difficulty can improve the feasibility of harvesting sequences in clustered environments. The work provides a promising foundation for safer and more reliable robotic strawberry harvesting, while real-time deployment will require further reductions in computational cost.

Congratulations to **Lin Yang** and all the co-authors on this achievement! 🍓🤖

---

## 中文

我们很高兴地宣布，实验室论文 **《Harvesting Sequence Optimization for Clustered Strawberries Using a Fruit-Level Harvesting Difficulty Score》** 已被国际期刊 **《Computers and Electronics in Agriculture》** 接收发表。

论文第一作者为硕士研究生 **杨琳（Lin Yang）**，共同作者包括 **Shimin Hu、Meili Sun 和 Ya Xiong**。该研究由北京市农林科学院智能装备技术研究中心与山东农业大学信息科学与工程学院合作完成。

草莓在密集成簇生长时，不同果实在可接近性、遮挡程度和碰撞风险等方面存在明显差异，给机器人采摘带来很大挑战。现有采摘顺序规划方法通常侧重于缩短机械臂运动路径，而较少考虑单颗果实本身的采摘难度。

针对这一问题，本研究提出了一种面向采摘难度的草莓采摘顺序优化框架，主要包括：

- 利用两阶段卷积神经网络预测果实级 **采摘难度评分（Harvesting Difficulty Score，HDS）**；
- 每次虚拟移除果实后动态更新其余果实的 HDS；
- 采用基于遗传算法的 **MOP-GA** 和基于模拟退火的 **MOP-SA**，进行加权多目标采摘顺序规划。

HDS 回归模型的平均绝对误差为 **6.55%**，决定系数 **R² 达到 72.39%**。在离线实验中，MOP-GA 将单果平均 HDS 降至 **0.282**，优于旅行商问题（TSP）策略的 **0.291** 和自下而上策略的 **0.297**。

在 9 组草莓果簇场景的室内机器人实验中，MOP-GA 和 MOP-SA 的 HDS 分别为 **0.197** 和 **0.204**，均低于 TSP 的 **0.235** 和自下而上策略的 **0.237**。MOP-GA 的实际采摘失败率也低于 TSP（**19.11% 对 26.67%**），但不同方法之间总体失败概率的差异未达到统计显著水平。

研究结果表明，在采摘顺序规划中动态引入果实级采摘难度，可以提高机器人在密集果簇环境中的采摘可行性，为更加安全、可靠的草莓机器人采摘提供了新的思路。与此同时，算法计算成本仍是未来实现实时部署需要进一步解决的问题。

祝贺 **杨琳同学** 及全体作者！🍓🤖
