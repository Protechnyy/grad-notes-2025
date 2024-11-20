# 函数集合
后验概率的计算：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731729303803-9af8c29c-ec1c-433a-bc87-bc8b5e6961ca.png?x-oss-process=image%2Fformat%2Cwebp%2Fresize%2Cw_1312%2Climit_0)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731730530938-e772ef95-4d05-4b08-9da9-06add5c2e8d4.png?x-oss-process=image%2Fformat%2Cwebp%2Fresize%2Cw_1312%2Climit_0)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731739987598-40e5085e-9046-4aff-89e2-d105bad26398.png)

用图像来表示：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731739974949-60a32cc4-5fa3-4709-9528-b2c4b9d6fc38.png)

# 评估模型好坏——采用 Cross Entropy（交叉熵）
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731739872638-a74274a4-6bac-4962-a107-5616dde62355.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731740341912-8e68a7f5-2293-4e59-a66b-c03a7a030b4e.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731741794649-d3bb74e9-0d64-416c-bd64-94ea7ddf6ede.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731741866615-41aad30c-c567-421d-941e-f1124c5944bc.png)

# 找最好的函数
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731742159452-18c260fa-55f5-4bdf-8296-ee8f6a5ea8aa.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746195262-fb97787a-8fea-494a-8015-391d4dcc9ec3.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746284017-da6d9c15-df40-41c3-b09f-ce00bdc7aa2f.png)

结论：实际输出与理想结果差距越大，更新量越大。这样接近最佳越快。

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746391150-9a541a79-95e1-41d0-8083-563558e2eacb.png)

# Cross Entropy（交叉熵） 与 Square Error（均方误差） 对比
如果用 Square Error（均方误差）来作为评估好坏的标准：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746602978-eb23f669-78ea-4516-acb5-584c1d6ce1d2.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746764079-81d1eb0f-c7d7-4253-86bc-8385e324c75b.png)

这时作梯度下降时，无法确定离目标近还是远，训练速度也慢，不容易得出结果。

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731746682587-473b1386-aa17-4be7-a168-e9690a7fd21c.png)

# Dicriminative Model（判别式模型） 和 Generative Model（生成模型）
## 区别
Logistic Regression 属于 Discriminate。二者的 function set （Model）是一样，因为做了不同的假设，找出来的结果![image](https://cdn.nlark.com/yuque/__latex/2a2fb23b1d51fac2f310c0cfa3fad3db.svg) 是不同的。

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731747041029-1009d7c5-f06c-4f9e-9a71-94b73cd8928d.png)

正确率对比：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731747121390-29c12e86-85c0-45eb-99e1-fc71de2e67fd.png) 

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731749163391-e8c5a292-91c1-4c98-91a1-724ba6f3e25c.png)

## 举例
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731748196226-884bde79-2462-4975-9e9d-39e4d40b1606.png)

如果用朴素贝叶斯计算后验概率：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731748474362-dec25d03-eb6e-4722-a9af-93e24db4c9c0.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731748616599-cc3348a1-b0bc-468d-9482-1737c435a1cd.png)

理解：Generative Model 做了一些假设（脑补）

# 多个类别进行分类
假设有 3 个类，经过 Softmax（![image](https://cdn.nlark.com/yuque/__latex/349e1211cadcd9fca9c3cea2a41a2870.svg)）

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731830030163-408e4b9f-a57f-4cc8-a5ad-3e8d362ffd0a.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731830659016-0bb60648-c325-4270-9589-5ad212d5e220.png)

# 局限
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731830751026-8d24d7e1-ae34-47c6-a02e-d6f5bdf6ca49.png)

存在问题：无法找到一条分界线，将两个类各分一边：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731830834707-dc9973bd-40c8-47dc-966f-53b45f23f32b.png)

解决办法：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731831084165-5c611142-34de-4174-a417-6b4e39ee04f4.png)

希望机器能够找到这个 transformation：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731831291881-c5e37732-03b4-4331-b349-5a4bb265187c.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731831536816-054fcca0-c000-49f4-a2ae-5f18e4d7491c.png)

经过 transform：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731831582849-a17294e8-1bd3-477a-9294-1c2e6ac2e706.png)

> 纠正：右下角横纵轴画反了
>

# 神经网络与深度学习
<font style="color:rgb(25, 27, 31);">假如把上例中的一个逻辑回归叫做</font>**<font style="color:rgb(25, 27, 31);">神经元（Neuron）</font>**<font style="color:rgb(25, 27, 31);">，那我们就形成了一个神经网络。</font>

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731831661183-6ef1e95f-6017-47a8-87ec-8af069c58996.png)

