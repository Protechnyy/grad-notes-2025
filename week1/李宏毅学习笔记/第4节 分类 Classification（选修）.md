# 应用
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421696311-e4b4e375-0405-498e-9c23-8632066b38de.png)

# 案例
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421701515-a9a7afc2-0641-43f4-8019-2cb10f836194.png)

用一个向量（vector）来表示一只宝可梦的各个数值

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421705654-27305eba-711b-4bd3-8c57-adbfc14417c6.png)

# 如何分类
## 当作回归问题
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421710530-0972ce3d-77a8-40ba-8376-65dfbe8326cd.png)

存在问题：回归中评判标准的好坏与分类中的好坏不同

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421714947-c664be37-2d0b-4855-9e1a-212de1d17c96.png)

理想的选择：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421726168-90f97de4-7c0f-4e44-a0e7-6ade46684613.png)

## 假设几率模型——高斯（Gaussian）分布
### 类比
1. 两个盒子中抽取球的问题：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421733064-6d1724f6-8caa-4a3d-b858-f60e9fc73064.png)

2. 类比分类问题，生成模型（Generative Model）

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421742402-3e6c4a89-08c5-47c2-ae71-d26d0ab5e79a.png)

### 计算过程
算先验概率（Prior）

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421746667-767af047-0840-4423-ba28-e5d60f7442a6.png)

算条件概率：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421750637-473e94b7-4585-4fe8-bd34-07fc137a2ba2.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421756215-c2028347-14a8-4cbe-a187-7e959f23e3a3.png)

假定这些点是从高斯分布采样的：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421760599-aad1a901-e21c-48fd-a8d2-0d067e9fb7c4.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421764778-9af371d2-04b1-4daa-81e6-c26759774dff.png)

`covariance`：协方差

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421769074-a1be1c25-f33e-4303-8852-cc49f1969d57.png)

估测出期望和协方差：用**最大似然估计（Maximum Likelihood）**。任何一个高斯分布都可以采样出这79个点，但采样出这79个点的概率不同。

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421773216-0fdcda81-e997-4300-a930-8f8eb279d012.png)

找一个**最优高斯分布**![image](https://cdn.nlark.com/yuque/__latex/143ebb2eb3830c28ba6875fa02cedd95.svg)，取样出这79个点的概率最大

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421777023-24f94c08-0514-436a-8894-ceb9ae95fc9b.png)

计算结果：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421781252-95db5324-b2cd-455f-826b-602ac2f7e706.png)

现在就可以分类：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421785822-de9a0792-eb16-40d0-bf2b-fda297bdad74.png)

结果并不理想：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731727055947-09af5a3d-6ef7-4694-a03e-05bcd9652844.png)

强制两个类使用同一个协方差矩阵![image](https://cdn.nlark.com/yuque/__latex/a99c3dabbb2eeee45801b2b7d343cc65.svg)，减少参数设置：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731727111112-042a94f4-a6b7-4c82-b971-be0314e5805b.png)

分界线由曲线变为直线：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731728860871-037482d5-19ba-474b-b513-017888d05154.png)

## 总结
### 机器学习模型的三部
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731728992654-302c6472-2f0c-4259-a340-1692e857e0a4.png)

### 算后验概率（Posterior Proability）的推导
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731729303803-9af8c29c-ec1c-433a-bc87-bc8b5e6961ca.png)

这也解释了为什么取![image](https://cdn.nlark.com/yuque/__latex/bd22b2ef56c060537fc4ddd2246c86c1.svg)时，分类边界线会是直线：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731730530938-e772ef95-4d05-4b08-9da9-06add5c2e8d4.png)

