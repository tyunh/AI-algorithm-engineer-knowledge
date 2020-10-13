## 模型压缩方法
### 网络剪枝
- 剪枝流程：
<div align=center><img width="700" height="120" src="https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/blob/main/image/networks_pruning.png"/></div>

### 知识蒸馏
- 蒸馏的是大网络的学习能力，我们认为大网络的学习到的信息更多，那么我们对于同一个图片，不直接用小网络学习信息，而是学习大网络学习的东西，也可以说学习到一种泛化能力

- 去学习大网络的输出，比如输入1的图像，小网络要尽量输出大网络的输出，而不是只是学习输出真实标签1

<div align=center><img width="500" height="300" src="https://github.com/ethan-sui/AI-algorithm-engineer-knowledge/blob/main/image/teacher-student_network.png"/></div>

### 高效网络结构
### 参数量化
### 低秩转化
### 神经架构搜索
