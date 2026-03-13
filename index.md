# 我的主页

欢迎来到我的 GitHub Pages 站点

---

## :calendar: 2026年3月4日

:newspaper: 第一次创建网页，我的第一张互联网大字报！

### :notebook: 生物信息学学习笔记

算法和模型的区别

| 概念 | 算法 | 模型 |  
|:---:|:-----:|:-----:|  
| 定义 | 解决问题的方法 | 从数据中学习到的参数化表示 |  
| 形式 | 流程图、伪代码 | 训练后的参数、神经网络权重 |  
| 例子 | 梯度下降算法 | 神经网络 |  
| 通用性 | 不依赖数据 | 依赖数据 |  
| 可变性 | 固定不变 | 随训练数据变化而变化 |

---

## :calendar:2026年3月5日

### :notebook:生物信息学学习笔记

- 课程介绍：
  - Linux系统中Fedora 实验室用的多一些
  - 图灵机基本结构：输入(Transformer在input上革新)→计算→输出
  - Shell的介绍：Bash shell 
  - 作业：完成基本命令
    - 命令记忆 上下键
    - 自动补全 tab键
    - alias
    - 通配符的用法 * ？
    - bash script
  - 大作业推荐完成作业1、6：
    - 作业1：利用构建出的expression matrix，建立分类模型，找出稳健的可以区分癌症和正常样本的Feature，并进行相关分析。
    - 作业6：利用最新的 AI 工具，例如OpenClaw、OpenCode 等，构建一个 AI Agent for Biomedicine based on field-specific domain knowledge。

- 前沿进展：
  - alpha-genomics Omics 用于基因组 output

- 课程内容：

| 对象 | 算法 | 流程 | 应用 |
| :---: | :------: | :---------------: | :---------: |
| 基础 | | non-terminal :arrow_right: production rule:arrow_right: terminal | |
| 一维 | 隐马尔可夫(HMM)| derivation path :arrow_right: parsing :arrow_right: sequence | Gene finder，Pfam |
| 二维 | 随机上下文无关(SCFG)| derivation path :arrow_right: parsing :arrow_right: secondary structure | Rfam |
| 三维 | Transformer |  | AlphaFold |
| 高维 | | | AI Vitual Cell |

---

## :calendar:2026年3月13日

### :notebook:生物信息学笔记

1. choose seq  
2. generate score  
   构建score function。:question:PAM250矩阵为什么不对称  
3. allow gap  
   计算gap权重的函数：W<sub>n</sub> =a + (n-1) b。对权重的赋值是一种超参，即用背景知识设计的参数  
4. score reflect  
5. alignment global or local  
   Needleman-Wunsch algorithm	全局最优  
   Smith-Waterman algorithm		局部最优  
6. estimate probability  
   计算速度太慢，需要启发式算法(heuristic): local match, precompute look-up table (hash table), posistion of every possible tuple  
7. occured by chance   
   BLAST中衡量概率的参数：  
   expect value = : 和随机相比概率值，越小越好，correction of the p-value multiple testing  
   p-value = : probabilitty that an event occurs by change  

名词解释：  
identity相同，similar相似  
sequence alignment：  
　　homolog(同源：所有血红蛋白家族)  
　　ortholog(直接同源：鼠，鸡的α球蛋白)  
　　paralog(旁系同源：鼠的α，β球蛋白)  
RefSeq: NCBI reference sequence，一个基因注释数据库 

---

**底部导航栏：**

- :construction_worker:施工中……
