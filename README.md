# Live-and-Learn

# 1 Research

## 1.1 ATT&CK
- [网络攻击前沿：ATT&CK 模型一览](https://zhuanlan.zhihu.com/p/92581688)

- [ATT&CK一般性学习笔记](https://bbs.pediy.com/thread-254825.htm)

- [基于ATT&CK的APT威胁跟踪和狩猎](https://www.secrss.com/articles/13161)

（1）在 Observable或 Indicator 层面到 ATT&CK 的 Technique 层面存在一些层次上的缺失，中间应该包含一个富有更多上下文信息的复合结构，并且其能够容易映射到检测点以及实现规则的过滤，这里称为Behavior。

（2）在 ATT&CK 矩阵的 Technique 列表中，应该存在层次划分，也就是哪些技术是我们应该优先考虑和覆盖的，哪些技术是比较关键的和异常度高的，244项技术总会存在一些优先级在里面，并且随着防御策略的不断调整，其优先级可能出现变化。



## 1.2 Provenance
- [Getting started with Provenance and Neo4j] (https://medium.com/neo4j/getting-started-with-provenance-and-neo4j-b50f666d8656)
![PROV-O concept](https://miro.medium.com/max/1050/1*cgrKoUQX8LkVBeus-PCu1Q.png)
  - Activities — An action that modify / create / delete Entities
  - Entities —Pictures, Files, Meat, Horse
  - Agent — Triggers actions and “owns” entities, used to track responsibilities
  
![](https://miro.medium.com/max/788/1*1KZXJRXeQu7iW8EeXDTdBw.png)


- [CamFlow](http://camflow.org/)
CamFlow is a Linux Security Module (LSM) designed to capture data provenance for the purpose of system audit.

- [Open Provenance](https://openprovenance.org/)

- [A Python library for W3C Provenance Data Model (PROV)](https://prov.readthedocs.io/en/latest/)
  - Features:
An implementation of the W3C PROV Data Model in Python；
In-memory classes for PROV assertions, which can then be output as PROV-N；
Serialization and deserialization support: PROV-O (RDF), PROV-XML and PROV-JSON；
Exporting PROV documents into various graphical formats (e.g. PDF, PNG, SVG)；
Convert a PROV document to a Networkx MultiDiGraph and back.

# 2 Security
## 2.1 威胁情报
- [威胁情报系列 (一)：什么是威胁情报](https://www.secrss.com/articles/16577)
- [威胁情报系列（二）：威胁情报从哪里来](https://mp.weixin.qq.com/s/YlBy-QI98UBJD21L0u9NFg)


## 2.2 安全技术
- [DNS Tunnel](https://www.paloaltonetworks.com/cyberpedia/what-is-dns-tunneling)



# 3 Mathematics
## 3.1 Game Theory
- [博弈论速成指南：那些融入深度学习的经典想法和新思路](https://zhuanlan.zhihu.com/p/110773996)



# 4 Machine Learning

- [模糊聚类](https://blog.csdn.net/changyuanchn/article/details/80427893)

## 4.1 Deep Learning

### 4.1.1 LSTM 
- [人人都能看懂的LSTM](https://zhuanlan.zhihu.com/p/32085405)
![LSTM工作原理](https://pic2.zhimg.com/80/v2-556c74f0e025a47fea05dc0f76ea775d_720w.jpg)

- [人人都能看懂的GRU](https://zhuanlan.zhihu.com/p/32481747)

## 4.2 知识图谱
[机器之心：这是一份通俗易懂的知识图谱技术与应用指南](https://www.jiqizhixin.com/articles/2018-06-20-4)
- 在一项任务中，只要有关系分析的需求，知识图谱就有可能派的上用场。
- 知识图谱本质上是语义网络（Semantic Network）的知识库；从实际应用角度，可以简单地把知识图谱理解成多关系图（Multi-relational Graph）
- 知识图谱构建过程：1. 定义具体的业务问题  2. 数据的收集 & 预处理  3. 知识图谱的设计  4. 把数据存入知识图谱  5. 上层应用的开发，以及系统的评估
- 效率：把常用的信息存放在知识图谱中，把那些访问频率不高，对关系分析无关紧要的信息放在传统的关系型数据库当中。效率原则的核心在于把知识图谱设计成小而轻的存储载体。
- 挖掘知识图谱的算法：
  - 基于规则：不一致性检验；基于规则提取特征；基于模式的判断；
  - 基于概率：社区挖掘；标签传播；聚类
  - 基于动态网络的分析：dynamic network mining
  
## 4.3 Graph Neural Network
- [NTU Graph Deep Learning Lab](https://github.com/graphdeeplearning)
- [一文读懂图卷积GCN](https://zhuanlan.zhihu.com/p/89503068)
- [何时能懂你的心——图卷积神经网络（GCN）](https://zhuanlan.zhihu.com/p/71200936)
- [GraphSAGE](https://zhuanlan.zhihu.com/p/74242097)
- [从图(Graph)到图卷积(Graph Convolution)：漫谈图神经网络模型](https://www.cnblogs.com/SivilTaram/p/graph_neural_network_1.html)

# 5 Linux
- [Make 命令教程](http://www.ruanyifeng.com/blog/2015/02/make.html)


# 6 图论
- [图的支配集、覆盖集与独立集](http://kklin.farbox.com/post/ji-suan-ji-li-lun/tu-lun/7-zhi-pei-ji-fu-gai-ji-du-li-ji-yu-pi-pei/1-tu-de-dian-zhi-pei-ji-dian-fu-gai-ji-yu-dian-du-li-ji)

