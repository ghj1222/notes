# 一元函数积分学

ghj1222

[TOC]

主要按照同济大学《高等数学》第七版上册第4-7章编排

## 第四章 不定积分z

写在前面：不定积分要加C

### 4.1 不定积分的概念与性质

(1) **原函数**：在区间 $I$ 上，可导函数 $F(x)$ 的导函数为 $f(x)$，则称 $F(x)$ 为 $f(x)$ 在区间 $I$ 上的一个原函数。**原函数存在定理**：连续函数一定有原函数。

(2) **不定积分**：在区间 $I$ 上，函数 $f(x)$ 带有任意常数项的原函数称为 $f(x)$ 在区间 $I$ 上的不定积分 $\int f(x)\mathrm dx$。**积分号**、**被积函数**、**被积表达式**、**积分变量**、**积分曲线**。

(3) **基本积分表**：

| 编号 | 积分 |
| ---- | ---- |
| 1    | $\int k\mathrm dx=kx+C$ |
| 2   | $\int x^\mu\mathrm dx=\frac{x^{\mu+1}}{\mu+1}+C$ |
| 3   | $\int\frac{\mathrm dx}x=\ln|x|+C$ |
| 4   | $\int\frac{\mathrm dx}{1+x^2}=\arctan x+C$ |
| 5   | $\int\frac{\mathrm dx}{\sqrt{1-x^2}}=\arcsin x+C$ |
| 6   | $\int\cos x\mathrm dx=\sin x+C$ |
| 7   | $\int\sin x\mathrm dx=-\cos x+C$ |
| 8   | $\int\sec^2 x\mathrm dx=\tan x+C$ |
| 9   | $\int\csc^2 x\mathrm dx=-\cot x+C$ |
| 10   | $\int\sec x\tan x\mathrm dx=\sec x+C$ |
| 11   | $\int\csc x\cot x\mathrm dx=-\csc x+C$ |
| 12   | $\int e^x\mathrm dx=e^x+C$ |
| 13 | $\int a^x\mathrm dx=\frac{a^x}{\ln a}+C$ |

(4) **不定积分的性质**：可以加减、数乘；通常求解积分时，通过拆开（对就暴力拆）来求解。

### 4.2 换元积分法

**换元积分法**：把复合函数的微分法反过来用于求不定积分，利用中间变量的代换，得到复合函数的积分法。

#### 第一换元积分法

复合函数， 外层 $f(u)$ 具有原函数 $F(u)$ ，$u=\varphi(x)$ 。

对于微分，有 $\mathrm dF[\varphi(x)]=f[\varphi(x)]\varphi'(x)\mathrm dx$。

积分回来有 $\int f[\varphi(x)]\varphi'(x)\mathrm dx =F[\varphi(x)]+C=\int f[\varphi(x)]\mathrm d[\varphi(x)]$。

Problem - 求 $\int \tan^nx\sec^mx\mathrm dx$。

注意到 $(\tan x)'=\sec^2 x$  且有 $(\sec x)'=\sec x\tan x$ 且

(1) $m > 0$ m为偶数 用  $\sec^2 x=\tan^2x+1$ 凑微分；

(2) m=0，用$\tan^2 x=\sec^2 x-1$ 降次；

(2) n m 均为奇数，用$\tan^2 x=\sec^2 x-1$ 凑微分；

(3) n偶m奇数

#### 第二换元积分法

把上面的式子反着用： $\int f(x)\mathrm dx=\int f[\psi(t)]\psi'(t)\mathrm dt$ ，其中 $t=\psi^{-1}(x)$；使用条件： $x=\psi(t)$ 在 $t$ 的区间上单调、可导并且 $\psi(t)\neq 0$。

积分表扩充：

| 编号 | 积分 |
| ---- | ---- |
| 14   |      |
| 15   |      |
| 16   |      |
| 17   |      |
| 18   |      |
| 19   |      |
| 20   |      |
| 21   |      |
| 22   |      |
| 23   |      |
| 24   |      |

### 4.3 分部积分法

(1) **分步积分公式**：由导数的乘法法则： $(uv)'=u'v+v'u$ 进行积分，得到： $\int uv'\mathrm dx=uv-\int u'v\mathrm dx$ ；或者写成 $\int u\mathrm dv=uv-\int v\mathrm du$ 。 

### 4.4 有理函数的积分

### 4.5 积分表的使用

### Troubleshooting

## 第五章 定积分

### 5.1 定积分的概念与性质

### 5.2 微积分基本公式

### 5.3 定积分的换元法和分部积分法

### 5.4 反常积分

### 5.5 反常积分的审敛法  $\Gamma$ 函数

### Troubleshooting

## 第六章 定积分的应用

### 6.1 定积分的元素法

### 6.2 定积分在几何学上的应用

### 6.3 定积分在物理学上的应用

### Troubleshooting

## 第七章 微分方程

### 7.1 微分方程的基本概念

### 7.2 可分离变量的微分方程

### 7.3 齐次方程

### 7.4 一阶线性微分方程

### 7.5 可降阶的高阶微分方程

### 7.6 高阶线性微分方程

### 7.7 常系数齐次线性微分方程

### 7.8 常系数非齐次线性微分方程

### 7.9 欧拉方程

### 7.10 常系数线性微分方程组解法举例

### Troubleshooting

## Troubleshooting