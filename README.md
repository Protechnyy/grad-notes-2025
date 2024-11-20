# GraduateLearning
## 前言

2024级新生入门任务为期十周，包含必须完成学习的基本知识，以及需要自己长时间持续学习的知识。所有学习的内容必须有相关笔记（不限格式，可.docx、.md）以及代码的输出，每周学习得到的笔记和代码使用git远程仓库管理，以周为单位保存，如：

name
 |-- week1
 |  |-- 李宏毅视频笔记
 |  |  |-- xxx.md 或 xxx.docx
 |  |-- git工具使用笔记
 |  |  |-- xxx.md 或 xxx.docx
 |-- week2
 |  |-- 李宏毅视频笔记
 |  |  |-- xxx.md 或 xxx.docx
 ...

 

每周周末填写[周报](第x周-姓名-周报-20230627.xlsx)，并发送到邮箱：xxx，邮件中添加excel周报附件，以及git远程仓库的地址。大家学习中的疑惑也可以记在笔记或者邮件中，各位老师师兄看到都会回复。

 

**必须完成学习的知识包括：**

1. 深度学习入门

​        主要参考资料：

–       [【授权】李宏毅2023春机器学习课程*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP/?vd_source=09614df33504ffaff7c056d2a8c06e74)

​        （注，本视频集完整记录了李教授2023春包括tutorial的所有课程，除了任务安排指定，课程中其他选修部分都不做硬性要求；）

–       [跟李沐学AI](https://space.bilibili.com/1567748478?spm_id_from=333.337.0.0)

2. Linux 基本命令
3. git 工具

​        （注，涉及有关项目实践和任务输出的内容，都使用gitee进行版本和内容管理）

4. 循环神经网络（Recurrent Neural Network，RNN）、Transformer、部分预训练模型（Pretrained Model）、大语言模型（Large Language Model）入门
5. pytorch

​        主要参考资料：

–       [【布客】PyTorch 中文翻译 (apachecn.org)](https://pytorch1x.apachecn.org/)

–       [TingsongYu/PyTorch-Tutorial-2nd: 《Pytorch实用教程》（第二版）无论是零基础入门，还是CV、NLP、LLM项目应用，或是进阶工程化部署落地，在这里都有。相信在本书的帮助下，读者将能够轻松掌握 PyTorch 的使用，成为一名优秀的深度学习工程师。 (github.com)](https://github.com/TingsongYu/PyTorch-Tutorial-2nd)

**需要长时间学习的知识包括：**

1. Python
2. [跟李沐学AI的个人空间 哔哩哔哩 bilibili](https://space.bilibili.com/1567748478/channel/seriesdetail?sid=398820) 论文精读系列

注意，不要花费过多的时间在各种环境配置，以及扩展插件等功能上，所有环境都只是工具，为实现代码而服务



## 第一周（6.19-6.25）

### 任务

1. 机器学习&ChatGPT相关基础概念以及Pytorch基础操作

–       [(正课)机器学习 2023 规则说明*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=1&vd_source=09614df33504ffaff7c056d2a8c06e74)

–       [(正课)【生成式AI】ChatGPT原理剖析(1_3)-对 ChatGPT 的常见误解*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=2&vd_source=09614df33504ffaff7c056d2a8c06e74)

​         第一节内容：P1-P9

2. git 代码仓库的学习

–       [Git使用教程,最详细，最傻瓜，最浅显，真正手把手教 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/30044692)

–       [收藏了！Git 核心操作图解 (qq.com)](https://mp.weixin.qq.com/s/Fg5rht0k583YvHD0pMJ_BQ)

–       [GitHub仓库快速导入Gitee及同步更新 - Gitee.com](https://gitee.com/help/articles/4284#article-header1)

–       [Gitee 帮助中心 - Gitee.com](https://gitee.com/help)



### 输出

1. 在[Gitee](https://gitee.com/)上，建立自己的笔记仓库，利用git工具进行自己笔记的版本管理，学会分支、合并等基本操作
2. 视频课程学习笔记并将自己的笔记上传到在1.上建立的自己的gitee笔记仓库中，作业部分不用完成（可以根据视频讲解和博主提供的git/gitee仓库中的内容学习）



## 第二周（6.26-7.02）

### 任务

1. 机器学习基本原理

–       [(正课)【生成式AI】快速了解机器学习基本原理 (1_2) (已经略懂机器学习的同学可以跳过这段)*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=13&vd_source=09614df33504ffaff7c056d2a8c06e74)

​        P13-P21

2. Linux环境配置以及基本命令

–       在windows上运行WSL2

•       [适用于 Linux 的 Windows 子系统文档 | Microsoft Docs](https://docs.microsoft.com/zh-cn/windows/wsl/)

•       [Windows10/11 三步安装wsl2 Ubuntu20.04（任意盘） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/466001838)

–       在widows子系统WSL2中建立Ubuntu环境

–       了解Linux基本操作

•       [第一章：引言 · The Linux Command Line 中文版 · 看云 (kancloud.cn)](https://www.kancloud.cn/thinkphp/linux-command-line/39431)



### 输出

1. 视频课程学习笔记并上传到自己的gitee笔记仓库中
2. 完成linux的配置以及基本操作的学习



## 第三周（7.03-7.09）

### 任务

1. 生成式AI

–       [(正课)【生成式AI】Finetuning vs. Prompting：对于大型语言模型的不同期待所衍生的两类使用方式 (1_3)*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=23&vd_source=09614df33504ffaff7c056d2a8c06e74)

​        P23-P25

2. 课程作业

–       [(作业)Colab Tutorial (introduction + demo)*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=10&vd_source=09614df33504ffaff7c056d2a8c06e74)

​        P10-P12，P22，P28

3. 在WSL2下安装anaconda或miniconda（功能更轻量级，占用空间更小）并配置PyTorch环境（PyTorch有GPU版和CPU版，个人笔记本上使用CPU版就行，后续进入实验室后会分配有GPU的服务器）

–       安装方法自行搜索，例如[linux安装anaconda及配置pytorch环境](https://blog.csdn.net/qq_46311811/article/details/123524762)

4. 在WSL2中安装jupyter notebook，在windows中打开可视化界面，并熟悉jupyter使用方法

–       安装方法自行搜索，例如[搭建 Python 轻量级编写环境（WSL2+Jupyter 自动开启本地浏览器） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/158824489)

–       使用方法：

•       [Jupyter Notebook介绍、安装及使用教程 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/33105153)

•       [最详尽使用指南：超快上手Jupyter Notebook - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/32320214)

5. PyTorch包学习

–       [什么是PyTorch？ (apachecn.org)](https://pytorch.apachecn.org/#/docs/1.4/blitz/tensor_tutorial)

6. PaddlePaddle学习

–       [PaddlePaddle与PyTorch的转换](https://blog.csdn.net/shaojie_45/article/details/115445796?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2~default~CTRLIST~Rate-1-115445796-blog-119469002.235^v38^pc_relevant_anti_t3&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~CTRLIST~Rate-1-115445796-blog-119469002.235^v38^pc_relevant_anti_t3&utm_relevant_index=2)

–       [飞桨PaddlePaddle-源于产业实践的开源深度学习平台](https://www.paddlepaddle.org.cn/tutorials/projectdetail/5603475) 前五章



### 输出

1. 视频课程学习笔记
2. 完成环境配置以及对PyTorch的初步了解
3. 初步了解PaddlePaddle，以及与PyTorch的转换关系
4. 完成P10-P12，P22，P28的课程作业



## 第四周（7.10-7.16）

### 任务

1. 大模型

–       [(正课)大模型 + 大资料 = 神奇结果？ (1_3)：大模型的顿悟时刻*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=29&vd_source=09614df33504ffaff7c056d2a8c06e74)

​        P29-P33

2. 图像生成模型

–       [(正课)速览图像生成常见模型*哔哩哔哩*bilibili](https://www.bilibili.com/video/BV1TD4y137mP?p=34&vd_source=09614df33504ffaff7c056d2a8c06e74)

​        P35-P36，P39-P41

3. PyTorch入门中剩下部分的学习

​        [【布客】PyTorch 中文翻译 (apachecn.org)](https://pytorch1x.apachecn.org/)

4. PaddlePaddle包配置尝试

​        [使用指南-使用文档-PaddlePaddle深度学习平台](https://www.paddlepaddle.org.cn/documentation/docs/zh/guides/index_cn.html)



### 输出

1. 视频课程学习笔记以及作业
2. 完成PyTorch教程上的代码教程
3. 完成环境配置以及对PaddlePaddle的初步实践



## 第五周（7.17-7.23）

### 任务

1. NLP相关基础知识

–       自然语言处理导引及词向量[Lecture 1 - Introduction and Word Vector](https://www.bilibili.com/video/BV12z4y1i7vh?p=1)

•       Word2vec参考资料：

（1）    [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf)

（2）    [Distributed Representations of Words and Phrases and their Compositionality](https://arxiv.org/pdf/1310.4546.pdf)

（3）    [word2vec Parameter Learnin](https://arxiv.org/pdf/1411.2738.pdf)[g](https://arxiv.org/pdf/1411.2738.pdf)[ Explained](https://arxiv.org/pdf/1411.2738.pdf)

–       依赖分析[Lecture 4 - Dependenc](https://www.bilibili.com/video/BV12z4y1i7vh?p=4)[y](https://www.bilibili.com/video/BV12z4y1i7vh?p=4)[ Parsin](https://www.bilibili.com/video/BV12z4y1i7vh?p=4)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=4)

–       语言模型[Lecture 5 - Lan](https://www.bilibili.com/video/BV12z4y1i7vh?p=5)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=5)[ua](https://www.bilibili.com/video/BV12z4y1i7vh?p=5)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=5)[e Models and RNNs](https://www.bilibili.com/video/BV12z4y1i7vh?p=5)

–      Transformer模型、预训练模型[Lecture 10 - Transformers and Pretrained Model](https://www.bilibili.com/video/BV12z4y1i7vh?p=10)

–      大模型相关：[大模型基础](https://github.com/datawhalechina/so-large-lm)、[清华大模型课程](https://www.youtube.com/playlist?list=PLbiIHfsIRP5eWU5ySTYkQYwJIIGgXxOel)、[大模型知识点](https://github.com/datawhalechina/so-large-lm)

–      多模态学习：[经典论文阅读](https://dragon9001.github.io/MMG-page/)

2. 实战演练-阶段一

–       [nlp](https://github.com/fastai/fastbook/blob/master/10_nlp.ipynb)

–       [midlevel_data](https://github.com/fastai/fastbook/blob/master/11_midlevel_data.ipynb)

–       [nlp_dive](https://github.com/fastai/fastbook/blob/master/10_nlp.ipynb)



### 输出



1. 视频课程学习笔记以及作业
2. 阶段一涵盖NLP中模型构建的基本步骤，记录实验结果

## 第六周（7.24-7.30）

### 任务



1. NLP相关任务

–       翻译任务[Lecture 7 - Translation](https://www.bilibili.com/video/BV12z4y1i7vh?p=7)[,](https://www.bilibili.com/video/BV12z4y1i7vh?p=7)[ Seq2Seq](https://www.bilibili.com/video/BV12z4y1i7vh?p=7)[,](https://www.bilibili.com/video/BV12z4y1i7vh?p=7)[ Attention](https://www.bilibili.com/video/BV12z4y1i7vh?p=7)

这部分内容中包含的序列模型，注意力机制在第四周的神经网络训练任务部分已经讲述过，所以该部分可以略看。

–       问答任务[Lecture 11 - Question Answerin](https://www.bilibili.com/video/BV12z4y1i7vh?p=11)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=11)

–       自然语言生成任务[Lecture 12 - Natural Lan](https://www.bilibili.com/video/BV12z4y1i7vh?p=12)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=12)[ua](https://www.bilibili.com/video/BV12z4y1i7vh?p=12)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=12)[e Generation](https://www.bilibili.com/video/BV12z4y1i7vh?p=12)

–       共指消解任务[Lecture 13 - Coreference Resolution](https://www.bilibili.com/video/BV12z4y1i7vh?p=13)

2. 实战演练-阶段二

–       [词嵌入](https://github.com/zulihit/TransE)[ TransE](https://github.com/zulihit/TransE)[实现](https://github.com/zulihit/TransE)

–       [词嵌入](https://github.com/stanfordnlp/GloVe)[ Glove](https://github.com/stanfordnlp/GloVe)[实现](https://github.com/stanfordnlp/GloVe)

–       [序列模型与](https://zhuanlan.zhihu.com/p/601633905)[Attention](https://zhuanlan.zhihu.com/p/601633905)

–       [情感分析模型](https://zhuanlan.zhihu.com/p/599542107)

–       [关系抽取模型](https://github.com/thunlp/OpenNRE)

–       [大模型](https://intro-llm.github.io/)

### 输出



1. 视频课程学习笔记以及作业
2. 阶段二主要涵盖词嵌入学习及基础模型应用两部分内容完成模型调优，记录实验结果

## 第七周（7.31-8.06）



### 任务

1. 知识+大语言模型相关

–       [T5 and Lar](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[e Lan](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[ua](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)[e Model](https://www.bilibili.com/video/BV12z4y1i7vh?p=14)

–       [【生成式](https://www.bilibili.com/video/BV16N411K7aT?p=1)[AI](https://www.bilibili.com/video/BV16N411K7aT?p=1)[】](https://www.bilibili.com/video/BV16N411K7aT?p=1)[ChatGPT ](https://www.bilibili.com/video/BV16N411K7aT?p=1)[原理剖析](https://www.bilibili.com/video/BV16N411K7aT?p=1)[ ](https://www.bilibili.com/video/BV16N411K7aT?p=1) P1-P3、P7-P14

2. 大模型微调相关-基于LangChain的大语言模型应用开发，微调以及RAG

–       [指令微调 Instruction Tuning](https://www.bilibili.com/video/BV1Dm4y157Dc?p=4&vd_source=7347045f1c2aad0baa96f46fbc9894d6)

–       [常见微调方法：全量微调/P-Tuning/Prompt Tuning/LoRA](https://www.bilibili.com/video/BV1gQ4y137Xd/?spm_id_from=333.337.search-card.all.click&vd_source=7347045f1c2aad0baa96f46fbc9894d6)

–       [吴恩达大模型系列教程：2024吴恩达LLM大模型教程，手把手带你实现大模型预训练和模型微调，中英字幕（附学习课件）](https://www.bilibili.com/video/BV1Gm421p7DL/?p=18&share_source=copy_web&vd_source=a397d006fd2c1a6de2714dfa8b4cea95)

•       【配套代码：GitHub - ConnectAI-E/LangChain-Tutior: ⛓ LangChain 入门指南，配套吴恩达老师 [deeplearning.ai](https://www.deeplearning.ai/) 课程 😎复现语言：Python、NodeJs、Golang】

3. 实战演练-阶段三若对预训练模型微调部分感兴趣，可以参考huggingface主页。

–       [文本分类](https://huggingface.co/docs/transformers/tasks/sequence_classification)

–       [问答](https://huggingface.co/docs/transformers/tasks/question_answering)[1](https://huggingface.co/docs/transformers/tasks/question_answering)

–       [问答](https://huggingface.co/docs/transformers/tasks/multiple_choice)[2](https://huggingface.co/docs/transformers/tasks/multiple_choice)

4. 以下内容选择性完成

–       [BERT](https://zhuanlan.zhihu.com/p/143209797)[微调](https://zhuanlan.zhihu.com/p/143209797)[ ](https://zhuanlan.zhihu.com/p/143209797)

（本地或教程中提及Colab中执行）

–       [RoBERTa](https://colab.research.google.com/github/DhavalTaunk08/NLP_scripts/blob/master/sentiment_analysis_using_roberta.ipynb)[微调](https://colab.research.google.com/github/DhavalTaunk08/NLP_scripts/blob/master/sentiment_analysis_using_roberta.ipynb)

### 输出

1. 视频课程学习笔记
2. 阶段三涵盖预训练模型微调的基本过程，主要用意为熟悉huggingface平台，记录实验结果
3. 熟悉大模型的离线知识检索增强生成以及在线知识微调流程，记录实验结果

## 第八周（8.07-8.13）

### 任务

1. 其他

–       知识增强[Lecture 15 - Add Knowled](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[e to Lan](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[ua](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[g](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)[e Model](https://www.bilibili.com/video/BV12z4y1i7vh?p=15)

–       伦理道德[Lecture 16 - Social & Ethical Consideration](https://www.bilibili.com/video/BV12z4y1i7vh?p=16)

–       模型分析与可解释性[Lecture 17 - Model Anal](https://www.bilibili.com/video/BV12z4y1i7vh?p=17)[y](https://www.bilibili.com/video/BV12z4y1i7vh?p=17)[sis and Explanations](https://www.bilibili.com/video/BV12z4y1i7vh?p=17)

–       NLP未来[Lecture 18 - Future of NLP](https://www.bilibili.com/video/BV12z4y1i7vh?p=18)

2. 实战演练-阶段四

–       [语义检索系统](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/applications/neural_search)

–       [智能问答系统 ](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/applications/document_intelligence/doc_vqa)

–       [情感分析](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/applications/sentiment_analysis)



### 输出



1. 视频课程学习笔记以及作业
2. 阶段四涵盖预训练模型微调的基本过程，主要目的为熟悉paddleNLP平台，记录实验结果

## 第九周（8.14-8.20）

### 任务

1. 模型压缩入门

–       [模型压缩概述](https://www.bilibili.com/video/BV1ht4y1P73i/?spm_id_from=333.337.search-card.all.click&vd_source=eb1da0153b98ca6ae90d6b0ccaa9550c)

–       [模型蒸馏](https://www.bilibili.com/video/BV1eb411971p/?spm_id_from=333.788&vd_source=eb1da0153b98ca6ae90d6b0ccaa9550c)入门

–       [模型剪枝](https://www.bilibili.com/video/BV1pg4y1J73p/?spm_id_from=333.788&vd_source=eb1da0153b98ca6ae90d6b0ccaa9550c)入门

–       [模型参数量化入门](https://www.bilibili.com/video/BV1bL411U747/?spm_id_from=333.788&vd_source=eb1da0153b98ca6ae90d6b0ccaa9550c)

2. 论文阅读

–       模型压缩综述论文：Model compression as constrained optimization, with application to neural nets. Part I: general framework

–       [其他](https://wiki.modeloverfit.com/index.php/模型组Read_List)（推荐计划从事该方向研究的同学阅读）

### 输出

1. 视频课程学习笔记
2. 论文阅读笔记

## 第十周（8.21-8.27）

### 任务

1. 代码实操

–       [模型剪枝](https://github.com/huggingface/nn_pruning)

–       [知识蒸馏](https://github.com/haitongli/knowledge-distillation-pytorch)

–       [低秩分解](https://github.com/ruihangdu/Decompose-CNN)

–       [模型参数量化](https://github.com/Xilinx/brevitas)

### 输出

1. 熟悉代码的编写和内在逻辑，记录实验结果
