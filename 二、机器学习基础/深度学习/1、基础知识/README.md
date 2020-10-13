## 基础知识
### 激活函数
- 激活函数就是一个非线性函数，可以将非线性模式转化为线性模式
- 特性：非线性，几乎处处可微，有非饱和性，单调性，输出范围有限
- 作用主要就是增加非线性，提高模型的表征能力
- 常见的激活函数

1、Sigmoid
<div align=center><img width="500" height="400" src="https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/blob/main/image/Sigmoid.png"/></div>


&emsp;&emsp;表达式：$sigmoid(x)\frac{1}{1+e^{-x}}$

&emsp;&emsp;特点：可解释，比如将0-1之间的取值解释成一个神经元的激活率

&emsp;&emsp;缺点：①梯度消失，当输入为大的正数或者负数时，梯度为0，使得神经元基本不能更新；②不是零中心激活函数，输出全为正数，会导致zigzag现象；③有指数计算，计算量偏大

### 损失函数
### 反向传播
### BN层
### 过拟合问题
