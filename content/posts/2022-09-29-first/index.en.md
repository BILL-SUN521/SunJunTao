---
title: 第一篇博客
author: JunTao Sun
date: '2022-09-29'
slug: 第一篇博客
categories:
  - 资源收集
tags:
  - R
  - blogdown
  - resources
description: ~
featured_image: ~
markup: 'Mmark'
---

## 简介

最近在网上看到了用Rstudio创建个人博客的[文章](https://cosx.org/2022/03/build-blog-step-by-step/ "文章")，在对计算机，前端，git都不熟悉的我的捣腾之下，花了一个晚上和早上还是搞出来了。虽然没有什么用处，但看上去还是很不错滴！！！


## 图片测试：

<img src="images/1.png" alt="图片示例" width="80%"/>

![](1.png)

## 公式测试：

<script src="//yihui.org/js/math-code.min.js" defer></script>
<script defer src="//mathjax.rstudio.com/latest/MathJax.js?config=TeX-MML-AM_CHTML"></script>

$$x=a_0+\frac{1^2}{a_1+\frac{2^2}{a_2+\frac{3^2}{a_3+\frac{4^2}{a_4+...}}}}$$

$$\begin{equation}
a_1+a_2+\ldots+a_n \\\\
a_1+a_2+\cdots+a_n
\end{equation}$$

$$
\begin{array}{c|lcr}
n & \text{Left} & \text{Center} & \text{Right} \\\\
\hline
1 & 0.24 & 1 & 125 \\\\
2 & -1 & 189 & -8 \\\\
3 & -20 & 2000 & 1+10i \\\\
\end{array}
$$

$$
\begin{matrix}
1 & x & x^2 \\\\
1 & y & y^2 \\\\
1 & z & z^2 \\\\
\end{matrix}
$$

$$ X = \begin{bmatrix}
数字1 & 数字2 \\\\
数字3 & 数字4
\end{bmatrix}$$

$$
X(m,n)=
\begin{cases}
x(n),\\\\
x(n-1),\\\\
x(n+1)
\end{cases}
$$

$$
\begin{equation}\begin{split}
H(Y|X)&=\sum_{x\in X}p(x)H(Y|X)\\\\
&=-\sum_{x\in X}p(x)\sum_{y\in Y}p(y|x)\log p(y|x)\\\\
&=-\sum_{x\in X} \sum_{y\in Y}p(y,x)\log p(y|x)
\end{split}\end{equation}
$$

## 代码测试：

```R
a=c(1,2,3,4,5)
a>3
print("真不戳")
```

## 其他语法测试测试：

- 列表第一项
- 列表第二项

1. *斜体测试*
2. **粗体测试**

> All models are wrong, but some are useful 

