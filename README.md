<h1>数据结构和算法的学习笔记 </h1>
仅供参考, 持续更新  


<h2>目录</h2>
<!-- TOC -->

- [1. 数据结构概述](#1-数据结构概述)
- [2. 线性结构](#2-线性结构)
  - [2.1. 稀疏数组](#21-稀疏数组)
  - [2.2. 队列](#22-队列)
    - [2.2.1. 线形队列](#221-线形队列)
    - [2.2.2. 环形队列](#222-环形队列)
  - [2.3. 链表](#23-链表)
    - [2.3.1. 单向链表](#231-单向链表)
    - [2.3.2. 双向链表](#232-双向链表)
    - [2.3.3. 单向环形链表](#233-单向环形链表)
  - [2.4. 栈](#24-栈)
    - [2.4.1. 栈的基本原理](#241-栈的基本原理)
    - [2.4.2. 栈实现计算器](#242-栈实现计算器)
- [3. 递归](#3-递归)
  - [3.1. 递归的原理](#31-递归的原理)
  - [3.2. 递归解决数学问题](#32-递归解决数学问题)
- [4. 排序算法](#4-排序算法)
  - [4.1. 排序算法的时间复杂度](#41-排序算法的时间复杂度)
  - [4.2. 排序算法的分类](#42-排序算法的分类)
  - [4.3. 冒泡排序](#43-冒泡排序)
  - [4.4. 选择排序](#44-选择排序)
  - [4.5. 插入排序](#45-插入排序)
  - [4.6. 希尔排序](#46-希尔排序)
  - [4.7. 快速排序](#47-快速排序)
  - [4.8. 归并排序](#48-归并排序)
  - [4.9. 桶排序](#49-桶排序)
  - [4.10. 基数排序](#410-基数排序)
- [5. 查找算法](#5-查找算法)
  - [5.1. 线性查找](#51-线性查找)
  - [5.2. 二分查找](#52-二分查找)
  - [5.3. 插值查找](#53-插值查找)
  - [5.4. 斐波那契查找](#54-斐波那契查找)
- [6. 哈希表(散列)](#6-哈希表散列)
- [7. 树形结构](#7-树形结构)
  - [7.1. 二叉树](#71-二叉树)
    - [7.1.1. 二叉树的基本原理](#711-二叉树的基本原理)
    - [7.1.2. 顺序存储二叉树](#712-顺序存储二叉树)
    - [7.1.3. 堆排序](#713-堆排序)
    - [7.1.4. 哈夫曼树及其应用](#714-哈夫曼树及其应用)
    - [7.1.5. 二叉排序树](#715-二叉排序树)
    - [7.1.6. 平衡二叉树](#716-平衡二叉树)
  - [7.2. 多叉树](#72-多叉树)
- [8. 图论算法](#8-图论算法)
  - [8.1. 图的遍历](#81-图的遍历)
  - [8.2. 图相关算法的应用](#82-图相关算法的应用)
- [9. 常用的算法](#9-常用的算法)

<!-- /TOC -->
****

## 1. 数据结构概述
- <a href="01.algorithm_notes\001.线性结构和非线性结构.md">001.线性结构和非线性结构</a>

****

## 2. 线性结构

### 2.1. 稀疏数组
- <a href="01.algorithm_notes\002.稀疏数组的原理和代码实现.md">002.稀疏数组的原理和代码实现</a>

### 2.2. 队列

#### 2.2.1. 线形队列
- <a href="01.algorithm_notes\003.线形队列的原理和代码实现.md">003.线形队列的原理和代码实现</a>

#### 2.2.2. 环形队列
- <a href="01.algorithm_notes\004.环形队列的原理和代码实现.md">004.环形队列的原理和代码实现</a>

### 2.3. 链表

#### 2.3.1. 单向链表
- <a href="01.algorithm_notes\005.单链表的原理和代码实现.md">005.单链表的原理和代码实现</a>
- <a href="01.algorithm_notes\006.单链表面试题.md">006.单链表面试题</a>

#### 2.3.2. 双向链表
- <a href="01.algorithm_notes\007.双向链表的原理和代码实现.md">007.双向链表的原理和代码实现</a>

#### 2.3.3. 单向环形链表
- <a href="01.algorithm_notes\008.单向环形链表和约瑟夫问题.md">008.单向环形链表和约瑟夫问题</a>

### 2.4. 栈

#### 2.4.1. 栈的基本原理
- <a href="01.algorithm_notes\009.栈的原理和代码实现.md">009.栈的原理和代码实现</a>

#### 2.4.2. 栈实现计算器
- <a href="01.algorithm_notes\010.栈实现综合计算器.md">010.栈实现综合计算器</a>
- <a href="01.algorithm_notes\011.前缀中缀后缀表达式规则.md">011.前缀中缀后缀表达式规则</a>
- <a href="01.algorithm_notes\012.逆波兰计算器实现.md">012.逆波兰计算器实现</a>
- <a href="01.algorithm_notes\013.中缀转后缀表达式思路分析和代码实现.md">013.中缀转后缀表达式思路分析和代码实现</a>

****

## 3. 递归

### 3.1. 递归的原理
- <a href="01.algorithm_notes\014.递归的应用和说明.md">014.递归的应用和说明</a>

### 3.2. 递归解决数学问题
- <a href="01.algorithm_notes\015.迷宫回溯问题分析和实现.md">015.迷宫回溯问题分析和实现</a>  
- <a href="01.algorithm_notes\016.八皇后问题分析和代码实现.md">016.八皇后问题分析和代码实现</a>

****

## 4. 排序算法

### 4.1. 排序算法的时间复杂度
- <a href="01.algorithm_notes\018.时间频度介绍和特点.md">018.时间频度介绍和特点</a>
- <a href="01.algorithm_notes\019.时间复杂度计算和举例说明.md">019.时间复杂度计算和举例说明</a>
- <a href="01.algorithm_notes\020.平均时间复杂度和最坏时间复杂度.md">020.平均时间复杂度和最坏时间复杂度</a>
- <a href="01.algorithm_notes\029.排序算法时间复杂度比较.md">029.排序算法时间复杂度比较</a>

### 4.2. 排序算法的分类
- <a href="01.algorithm_notes\017.排序算法介绍和分类.md">017.排序算法介绍和分类</a>

### 4.3. 冒泡排序
- <a href="01.algorithm_notes\021.冒泡排序思路分析和代码实现.md">021.冒泡排序思路分析和代码实现</a>

### 4.4. 选择排序
- <a href="01.algorithm_notes\022.选择排序算法思路分析和代码实现.md">022.选择排序算法思路分析和代码实现</a>  

### 4.5. 插入排序
- <a href="01.algorithm_notes\023.插入排序思路分析和代码实现.md">023.插入排序思路分析和代码实现</a>

### 4.6. 希尔排序
- <a href="01.algorithm_notes\024.希尔排序思路分析和代码实现.md">024.希尔排序思路分析和代码实现</a>

### 4.7. 快速排序
- <a href="01.algorithm_notes\025.快速排序思路分析和代码实现.md">025.快速排序思路分析和代码实现</a>

### 4.8. 归并排序
- <a href="01.algorithm_notes\026.归并排序思路分析和代码实现.md">026.归并排序思路分析和代码实现</a>  

### 4.9. 桶排序
- <a href="01.algorithm_notes\027.桶排序思路及实现.md">027.桶排序思路及实现</a>

### 4.10. 基数排序
- <a href="01.algorithm_notes\028.基数排序思路分析和代码实现.md">028.基数排序思路分析和代码实现</a>

****

## 5. 查找算法

### 5.1. 线性查找
- <a href="01.algorithm_notes\030.线性查找分析和实现.md">030.线性查找分析和实现</a>

### 5.2. 二分查找
- <a href="01.algorithm_notes\031.二分查找思路和实现和优化.md">031.二分查找思路和实现和优化</a>
- <a href="01.algorithm_notes\051.二分查找非递归算法的原理和实现.md">051.二分查找非递归算法的原理和实现</a>

### 5.3. 插值查找
- <a href="01.algorithm_notes\032.插值查找的原理和实现.md">032.插值查找的原理和实现</a>

### 5.4. 斐波那契查找
- <a href="01.algorithm_notes\033.斐波那契查找的原理和实现.md">033.斐波那契查找的原理和实现</a>

****

## 6. 哈希表(散列)
- <a href="01.algorithm_notes\034.哈希表的分析和实现.md">034.哈希表的分析和实现</a>

****

## 7. 树形结构

### 7.1. 二叉树

#### 7.1.1. 二叉树的基本原理
- <a href="01.algorithm_notes\035.二叉树的存储和定义.md">035.二叉树的存储和定义</a>
- <a href="01.algorithm_notes\036.二叉树的创建和结点遍历.md">036.二叉树的创建和结点遍历</a>
- <a href="01.algorithm_notes\037.二叉树的结点查找和结点删除.md">037.二叉树的结点查找和结点删除</a>

#### 7.1.2. 顺序存储二叉树
- <a href="01.algorithm_notes\038.顺序存储二叉树的原理和实现.md">038.顺序存储二叉树的原理和实现</a>
- <a href="01.algorithm_notes\039.线索化二叉树的原理和实现.md">039.线索化二叉树的原理和实现</a>

#### 7.1.3. 堆排序
- <a href="01.algorithm_notes\040.堆排序的概念和实现.md">040.堆排序的概念和实现</a>

#### 7.1.4. 哈夫曼树及其应用
- <a href="01.algorithm_notes\041.哈夫曼树的概念和实现.md">041.哈夫曼树的概念和实现</a>
- <a href="01.algorithm_notes\042.哈夫曼编码的原理和实现.md">042.哈夫曼编码的原理和实现</a>
- <a href="01.algorithm_notes\043.哈夫曼编码应用于压缩文件.md">043.哈夫曼编码应用于压缩文件</a>

#### 7.1.5. 二叉排序树
- <a href="01.algorithm_notes\044.二叉排序树的原理和实现.md">044.二叉排序树的原理和实现</a>  

#### 7.1.6. 平衡二叉树
- <a href="01.algorithm_notes\045.平衡二叉树的原理和实现.md">045.平衡二叉树的原理和实现</a>

### 7.2. 多叉树
- <a href="01.algorithm_notes\046.多叉树的原理概述.md">046.多叉树的原理概述</a>

****

## 8. 图论算法

### 8.1. 图的遍历
- <a href="01.algorithm_notes\047.图的概念和实现.md">047.图的概念和实现</a>
- <a href="01.algorithm_notes\048.图的深度优先算法原理和实现.md">048.图的深度优先算法原理和实现</a>
- <a href="01.algorithm_notes\049.图的广度优先算法原理和实现.md">049.图的广度优先算法原理和实现</a>
- <a href="01.algorithm_notes\050.图的深度优先和广度优先算法的总结.md">050.图的深度优先和广度优先算法的总结</a>

### 8.2. 图相关算法的应用
- <a href="01.algorithm_notes\056.贪心算法的原理以及解决集合覆盖问题.md">056.贪心算法的原理以及解决集合覆盖问题</a>
- <a href="01.algorithm_notes\057.普里姆(Prim)算法的原理以及解决最小生成树问题.md">057.普里姆(Prim)算法的原理以及解决最小生成树问题</a>
- <a href="01.algorithm_notes\058.克鲁斯卡尔(Kruskal)算法的原理以及解决最小生成树问题.md">058.克鲁斯卡尔(Kruskal)算法的原理以及解决最小生成树问题</a>
- <a href="01.algorithm_notes\059.迪杰斯特拉(Dijkstra)算法的原理以及解决最短路径问题.md">059.迪杰斯特拉(Dijkstra)算法的原理以及解决最短路径问题</a>
- <a href="01.algorithm_notes\060.弗洛伊德(Floyd)算法的原理以及解决最短路径问题.md">060.弗洛伊德(Floyd)算法的原理以及解决最短路径问题</a>
- <a href="01.algorithm_notes\061.马踏棋盘算法的原理和实现方案.md">061.马踏棋盘算法的原理和实现方案</a>
  
****

## 9. 常用的算法
- <a href="01.algorithm_notes\052.分治算法的设计模式以及解决汉诺塔问题.md">052.分治算法的设计模式以及解决汉诺塔问题</a>
- <a href="01.algorithm_notes\053.动态规划算法的原理以及解决背包问题.md">053.动态规划算法的原理以及解决背包问题</a>
- <a href="01.algorithm_notes\054.暴力匹配算法的原理以及解决字符串匹配问题.md">054.暴力匹配算法的原理以及解决字符串匹配问题</a>  
- <a href="01.algorithm_notes\055.KMP算法的原理以及解决字符串匹配问题.md">055.KMP算法的原理以及解决字符串匹配问题</a>
- <a href="01.algorithm_notes\062.多数投票算法的原理和实现.md">062.多数投票算法的原理和实现</a>