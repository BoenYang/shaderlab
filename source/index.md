---
title: ShaderLab Refrence

search: true
---

# 简介

这里是简介

# Cg 标准函数

## 数学函数

### abs(x)
返回x的绝对值

### acos(x)
反余切函数，输入参数范围为[-1,1]， 返回[0,π]区间的弧度值

### asin(x)
反正弦函数,输入参数取值区间为[−1,1]，返回弧度值范围为, [−π2,π2]

### atan(x)
反正切函数，返回角度值范围为[−π2,π2]

### any(x)
输入参数只要有其中一个不为0，则返回true。

### all(x)
如果输入参数均不为0，则返回ture； 否则返回flase。&&运算

### ceil(x)
对输入参数向上取整。例如： ceil(float(1.3)) ，其返回值为2.0

### clamp(x,a,b)
如果x值小于a，则返回a；如果x值大于b，返回b；否则，返回x。

### cos(x)
返回弧度x的余弦值。返回值范围为[−1,1]

### cosh(x)
双曲余弦（hyperbolic cosine）函数，计算x的双曲余弦值。

### cross(a,b)
返回两个三元向量的叉积(cross product)。注意，输入参数必须是三元向量！

### degress(x)
弧度转角度,输入参数为弧度值(radians)，函数将其转换为角度值(degrees)

### determinant(M)
计算矩阵的行列式因子。

### dot(a,b)
返回a和b的点积(dot product)。参数a和b可以是标量，也可以是向量（输入参数方面，点积和叉积函数有很大不同）。

###exp(x)
计算ex的值，e=2.71828182845904523536

### exp2(x)
计算2x的值

### floor(x)
对输入参数向下取整。例如floor(float(1.3))返回的值为1.0；但是floor(float(-1.3))返回的值为-2.0。该函数与ceil(x)函数相对应。

### fmod(x,y)
返回x/y的余数。如果y为0，结果不可预料。

### frac(x)
返回标量或矢量的小数位

### lerp(a,b,f)
计算(1−f)∗a+b∗f或者a+f∗(b−a)的值。即在下限a和上限b之间进行插值，f表示权值。注意，如果a和b是向量，则权值f必须是标量或者等长的向量。

### log(x)
计算ln(x)的值，x必须大于0

### log2(x)
计算log(x)2的值，x必须大于0

### log10(x)
计算log(x)10的值，x必须大于0

### max(a,b)
比较两个标量或等长向量元素，返回最大值。

### min(a,b)
比较两个标量或等长向量元素，返回最小值。

### mul(M,N)
矩阵M和矩阵N的积，返回值为矩阵

### mul(M,v)
矩阵M和列向量v的积，返回值为矩阵

### mul(v,M)
行向量v和矩阵M的积，返回值为向量

### noise(x)
根据它的参数类型，这个函数可以是一元、二元或三元噪音函数。返回的值在0和1之间，并且通常与给定的输入值一样

## 几何函数

## 纹理映射

### tex2D

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Unity 内置变量

## 屏幕相关
### 1
### 2
### 3
## 光照相关
### 1
### 2
### 3
## 贴图相关
### 1
### 2
### 3

# Unity 内置函数
