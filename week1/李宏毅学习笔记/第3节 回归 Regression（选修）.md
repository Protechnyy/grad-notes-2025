# 引入
## 常见问题
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051095-c6583874-1c9d-42b3-aca4-408284b9c208.png)

## 应用
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051085-8aa689e4-0d36-47ad-9c6e-cbc654b87f9e.png)

# 步骤
## 选择模型
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051039-98e9823a-7818-4705-a78e-a57ceeba416d.png)

## 设定标准
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051067-dfed8a92-38e6-4ec0-8b5b-f1405fb63ebb.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051098-1dc53627-b568-40e5-8c86-befc5b76257c.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051875-73dc3372-a361-423c-97fd-711b62992656.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421052855-b81aeedf-b36f-43b3-9b7c-c7396653a7fe.png)

## 达成目标
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421051913-1c3241a0-3a0a-41a1-82f7-577242dc306e.png)

只要Loss Function是**可微分**的，利用梯度下降都可以找到最佳的函数：

1. 假定只有一个参数时：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421353671-f3836661-859d-48ac-81d5-099dfa77be94.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421367741-f5b99b46-f95a-4e1d-a19c-e33ecec08fdf.png)

其中![image](https://cdn.nlark.com/yuque/__latex/ac451adcd75e4326edc8b4a1baa35b4a.svg)<font style="color:rgb(55, 53, 47);"> </font>被称为**学习率**（Learning Rate）

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421417256-68cc77e7-e2dc-41f4-86ba-1457e8028c9a.png)

2. 两个参数时：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421434060-6395557d-74bc-4609-a441-48fca7311283.png)

3. 理解：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421448308-9704deee-5cbb-40ae-9874-28fe7cfaea52.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421456969-1a6d0564-6b88-42c0-967b-408ecb6ac692.png)

在线性回归中，损失函数（loss function）凸函数（convex function），**没有局部最优解**（local optimal）

4. 示例：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421479902-c69035d2-c0a0-42b8-a504-6bfe57bafa01.png)

# 结果
+ 训练集：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421495460-33c6260b-d814-4b6c-ba8e-b8b6d4b637ad.png)

+ 测试集：

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421513689-9b5e35c6-0dc5-4fa8-b691-2277e6559d56.png)

# 过拟合（Overfitting）
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421557651-fbae1e6b-bc1d-45ef-8023-eedef9f9ae02.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421564525-3d86f784-6ede-46f3-8b45-b80c665eaa1b.png)

# 优化
## 5.1 重新设计模型
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421583589-17214c3a-e4e2-4132-8863-eb531f3ec387.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421588066-97a5e21d-f8d2-4504-874e-47beba007528.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421592640-7a5f4d8b-3c3b-42d7-9e35-11486036f4ce.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421600104-e10e42dc-8f1c-4967-9f0b-c1885488f1b1.png)

## 5.2 重新设定标准——正则化（Regularization）
说明：正则化时不需要考虑![image](https://cdn.nlark.com/yuque/__latex/d29c2e5f4926e5b0e9a95305650f6e54.svg)（bias）

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421617938-d6507780-0855-405b-a5c8-0ef80342de0b.png)

![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421623614-50e4cce5-f189-4ff3-aa39-4b6a31f5a5f8.png)

# 总结
![](https://cdn.nlark.com/yuque/0/2024/png/33804227/1731421632534-c6f18ec0-d091-496c-ba4e-a7152a8db6b6.png)

