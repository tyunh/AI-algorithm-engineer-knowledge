## 模型压缩方法
### 1、网络剪枝
- 剪枝流程：
<div align=center><img width="700" height="120" src="https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/blob/main/image/networks_pruning.png"/></div>

### 2、知识蒸馏
- 蒸馏的是大网络的学习能力，我们认为大网络的学习到的信息更多，那么我们对于同一个图片，不直接用小网络学习信息，而是学习大网络学习的东西，也可以说学习到一种泛化能力

- 去学习大网络的输出，比如输入1的图像，小网络要尽量输出大网络的输出，而不是只是学习输出真实标签1

<div align=center><img width="500" height="300" src="https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/blob/main/image/teacher-student_network.png"/></div>

### 3、高效网络结构
- 深度可分离卷积(MobileNet)
先通道进行卷积(depthwise)再进行点卷积(pointwise)
参数量，计算量皆为正常卷积的$\frac{1}{N}+\frac{1}{D_{k}^2}$
### 4、参数量化
### 5、低秩转化
### 6、神经架构搜索
