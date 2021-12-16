---
title: 计算机结构和解释--Structure and Interpretation of Computer Programs
date: 2021-12-15 21:47:04
tags:
description: 课程笔记
---

B站

[](https://www.bilibili.com/video/BV1Xx41117tr)

# Lisp 概览

计算机科学-大型项目-控制复杂度

控制复杂度的方法

- 黑盒抽象—-Black-box abstraction
    - 基本对象
        - 基本过程、基本数据
    - 组合的意义
        - 过程组合，复杂数据的构造
    - 抽象的意义
        - 定义过程，简单数据的抽象
    - 获取一般模式
        - 高阶过程，数据作为过程
- api（conventional interfaces）
    - 通用操作—-generic operations
    - 大规模架构及模块化—-large-scale structure and modularity
        - 面向对象编程—-object-oriented programming
        - operations on aggregates
- 定义新的编程语言— metalinguistic abstraction（元语言抽象）

    lisp已经搭建好了，将用lisp解释lisp（与lisp中的一个神奇符号有关）


---

语言的通用框架：

- 基本元素有哪些
- means of combination
- means of abstruction

lisp 介绍

绝对值 abs—找出$\sqrt{x}$

猜测G的数值

改进G的值：对G和 $\frac{X}{G}$取平均值

知道改进值达到满足条件

# 计算过程

- 主要关注点：特定模式下的过程和表达式 会产生什么样的执行模式，什么样的处理行为
- 可以通过一些模型帮助理解关注点，如
    - 代换模型 - 一般情况下适用，不能准确描述计算机实际运行方式
    - 特殊模型
