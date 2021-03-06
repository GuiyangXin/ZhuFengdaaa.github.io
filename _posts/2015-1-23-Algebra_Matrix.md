---
layout: post
title: 线性代数从零单排_矩阵篇
tag: 线性代数
---
{% capture name1 %}
<a href="http://www.codecogs.com/eqnedit.php?latex=\left&space;|&space;A^{-1}&space;\right&space;|&space;=&space;\left|&space;A\right|^{-1}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\left&space;|&space;A^{-1}&space;\right&space;|&space;=&space;\left|&space;A\right|^{-1}" title="\left | A^{-1} \right | = \left| A\right|^{-1}" /></a>
{% endcapture %}
###先来回顾几个概念
* 可逆矩阵，也叫非奇异矩阵，秩与阶数相同。

* 若A是一个n阶可逆矩阵，则它的逆矩阵是唯一的。
* 若A^{*}是A的[伴随矩阵](http://zh.wikipedia.org/wiki/%E4%BC%B4%E9%9A%8F%E7%9F%A9%E9%98%B5)，有<a href="http://www.codecogs.com/eqnedit.php?latex=A^{-1}=&space;\frac{A^{*}}{A}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?A^{-1}=&space;\frac{A^{*}}{A}" title="A^{-1}= \frac{A^{*}}{A}" /></a>

* 若A可逆，则 {{ name1 }}
* 若A满足<a href="http://www.codecogs.com/eqnedit.php?latex=AA^{T}=A^{T}A=E" target="_blank"><img src="http://latex.codecogs.com/gif.latex?AA^{T}=A^{T}A=E" title="AA^{T}=A^{T}A=E" /></a> 则称A为[**正交矩阵**](http://zh.wikipedia.org/wiki/%E6%AD%A3%E4%BA%A4%E7%9F%A9%E9%98%B5)

* **等价**的定义：矩阵A以经过有限次初等变换化为矩阵B，则称A与B等价。

* 两个矩阵等价*等同于*两个矩阵秩相等
* 向量组的秩等于其极大线性无关组所含向量个数。

* 矩阵的秩等于其行向量组的秩，也等于其列向量组的秩。
* 如果其次线性方程组**AX=0**的系数矩阵A的秩 **R(A)=r<n** ,则方程组有基础解系，并且任一基础解系中含有**n-r**个解向量。




