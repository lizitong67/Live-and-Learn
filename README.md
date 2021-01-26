# Live-and-Learn

# 1 Research
- [面向图数据的异常检测综述概述](https://mp.weixin.qq.com/s/WBxmr_hCOVUbSk15ZPWsjw)
- [《透视APT》读书笔记](https://xz.aliyun.com/t/8335)
- [数据挖掘中常见的「异常检测」算法有哪些？](https://www.zhihu.com/question/280696035)
- [Open Threat Research Forge](https://github.com/OTRF)

## 1.1 ATT&CK
- [网络攻击前沿：ATT&CK 模型一览](https://zhuanlan.zhihu.com/p/92581688)

- [ATT&CK一般性学习笔记](https://bbs.pediy.com/thread-254825.htm)

- [基于ATT&CK的APT威胁跟踪和狩猎](https://www.secrss.com/articles/13161)

（1）在 Observable或 Indicator 层面到 ATT&CK 的 Technique 层面存在一些层次上的缺失，中间应该包含一个富有更多上下文信息的复合结构，并且其能够容易映射到检测点以及实现规则的过滤，这里称为Behavior。

（2）在 ATT&CK 矩阵的 Technique 列表中，应该存在层次划分，也就是哪些技术是我们应该优先考虑和覆盖的，哪些技术是比较关键的和异常度高的，244项技术总会存在一些优先级在里面，并且随着防御策略的不断调整，其优先级可能出现变化。



## 1.2 Provenance
- [Getting started with Provenance and Neo4j](https://medium.com/neo4j/getting-started-with-provenance-and-neo4j-b50f666d8656)
  - Activities — An action that modify / create / delete Entities
  - Entities —Pictures, Files, Meat, Horse
  - Agent — Triggers actions and “owns” entities, used to track responsibilities
  


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

- [Threat Hunting with ETW events and HELK — Part 1: Installing SilkETW](https://medium.com/threat-hunters-forge/threat-hunting-with-etw-events-and-helk-part-1-installing-silketw-6eb74815e4a0)
- [SilkETW-FireEye](https://www.fireeye.com/blog/threat-research/2019/03/silketw-because-free-telemetry-is-free.html)

## 1.3 Moving Target Defense (MTD)
- [移动目标防御（MTD）关键技术研究](http://m.chinaaet.com/article/3000018916)

# 2 Security
## 2.1 威胁情报
- [威胁情报系列 (一)：什么是威胁情报](https://www.secrss.com/articles/16577)
- [威胁情报系列（二）：威胁情报从哪里来](https://mp.weixin.qq.com/s/YlBy-QI98UBJD21L0u9NFg)


## 2.2 安全技术
- [DNS Tunnel](https://www.paloaltonetworks.com/cyberpedia/what-is-dns-tunneling)
- [DGA域名](https://www.secrss.com/articles/14369)
- [内网渗透基础知识](http://mang0.me/archis/7db24e65/)
- [DNS Tunnel隧道隐蔽通信实验 && 尝试复现特征向量化思维方式检测](https://www.cnblogs.com/LittleHann/p/8656621.html) 
- [Powershell+dnscat2实现DNS隐蔽隧道反弹Shell，和检测方法](https://mp.weixin.qq.com/s/5mDhzuGC2WEc8bdIjRg94w)
- [windows域环境下认证和攻击初识](https://mp.weixin.qq.com/s/4eroblcVS0dwo26fbzA3-Q)


## 2.3 MISC
- [国内网络主动防御技术现状探讨](https://www.secrss.com/articles/15495)
- [揭秘阿里云WAF背后神秘的AI智能防御体系](https://developer.aliyun.com/article/723263)
- [《对抗中的主动防御》](https://zhuanlan.zhihu.com/p/129713923)
- [SIEM](https://cloud.tencent.com/developer/article/1013572)
  - 监视用户行为+网络行为
  - 真正的机会是预见性的修复
  - 鉴于流经SIEM系统的部分数据比较敏感，目前大型企业用户习惯在本地运行SIEM软件。
- [NIST标准《零信任架构》](https://www.secrss.com/articles/15127)
- [Inside Microsoft Threat Protection: Attack modeling for finding and stopping lateral movement](https://www.microsoft.com/security/blog/2020/06/10/the-science-behind-microsoft-threat-protection-attack-modeling-for-finding-and-stopping-evasive-ransomware/)
- [正向代理和反向代理](https://juejin.cn/post/6844903782556368910)

# 3 Mathematics
- [线性代数的本质](https://www.bilibili.com/video/BV1ib411t7YR?t=8&p=4)

## 3.1 Game Theory
- [博弈论速成指南：那些融入深度学习的经典想法和新思路](https://zhuanlan.zhihu.com/p/110773996)


# 4 Machine Learning

- [模糊聚类](https://blog.csdn.net/changyuanchn/article/details/80427893)
- [吴恩达教授机器学习课程: 第14章--异常检测](https://tianchi.aliyun.com/notebook-ai/detail?spm=5176.12281897.0.0.48f239a9jbA1E9&postId=59235)
- [无监督学习](https://easyai.tech/ai-definition/unsupervised-learning/)
- [K-means和K-medoids](https://blog.csdn.net/databatman/article/details/50445561)
- [机器学习综述](https://mp.weixin.qq.com/s/3JV17K6URQ5rO9BsIMJI-w)
- [Contextual Bandits: LinUCB](https://zhuanlan.zhihu.com/p/32382432)
- [机器学习性能评价指标汇总](https://cloud.tencent.com/developer/article/1694996)
## 4.1 Deep Learning
- [60题PyTorch简易入门指南](https://www.kesci.com/home/project/5e0038642823a10036ae9ebf)
- [浅谈mask矩阵 ](http://www.linzehui.me/2018/10/12/%E7%A2%8E%E7%89%87%E7%9F%A5%E8%AF%86/%E6%B5%85%E8%B0%88mask%E7%9F%A9%E9%98%B5/)
- [PyTorch视频教程](https://www.bilibili.com/)

### 4.1.1 LSTM 
- [人人都能看懂的LSTM](https://zhuanlan.zhihu.com/p/32085405)

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

- [GraphSAGE](https://blog.csdn.net/yyl424525/article/details/100532849) 

- [从图(Graph)到图卷积(Graph Convolution)：漫谈图神经网络模型](https://www.cnblogs.com/SivilTaram/p/graph_neural_network_1.html)

- [中科院计算所沈华伟：图神经网络表达能力的回顾和前沿](https://mp.weixin.qq.com/s?__biz=MzA5ODEzMjIyMA==&mid=2247508211&idx=1&sn=d9059b2b80e2d2ac0a3094ca5c897284&chksm=9094a960a7e32076ce4e0f0cd6b99b1aa9d9b4cf049a1695a642b497e0320ef9b7bb0f981e8d&mpshare=1&scene=1&srcid=&sharer_sharetime=1593152170728&sharer_shareid=ca1742c0d2e24f8344d5b319b948d465&key=8c1e0ba910e0936a985ece58961c3915f3a9a6efd4abdbe9d8bde53f5086fc0d5da8d2b2734de73c04b7c9d18644fbd4d98c8fba0f56a178db17f1c0922ddd306d83f11f1f5e6740ab0c16d6601de391&ascene=1&uin=MTI5NjM0ODk2NA%3D%3D&devicetype=Windows+10+x64&version=6209007b&lang=zh_CN&exportkey=AUbb6c4yneRRptukebRrDTA%3D&pass_ticket=%2Fb7GKbJfPjag0NzUZwdk1MqFhl162QnSmgbUc62vxHypVyJ6PTkjWgv8Wukf%2Fi9r)

图神经网络在节点表示问题上，可以通过加深层数来增强其表达效果。
而在图表示问题上，由于GNN非单射的聚合方式，把原本不一样的东西聚合后变得一样了，这让GNN丧失了表达能力。 更直白一些，WL Test是一个单射函数，GNN不是单射函数，于是WL Test为GNN的表达能力提供了一个理论上的上界。（注：这里GNN说的是通过邻居聚合，如果别的聚合方式，性能可能超过WL test的）。同时ICLR 2019这篇论文又提出了GIN这一有着单射聚合函数的图神经网络，并对其表达能力进行了验证。

- [图表示学习及其无监督损失函数](https://www.infoq.cn/article/sWzLpqkg70TQhlwQcDhI)
- [Self-Attention 加速方法一览：ISSA、CCNet、CGNL、Linformer](https://zhuanlan.zhihu.com/p/270898373)
- [向往的GAT（图注意力模型）](https://zhuanlan.zhihu.com/p/81350196) 
- [图表示学习中的Encoder-Decoder框架](https://mp.weixin.qq.com/s/0lNeSjpm4lbu_8mopWJ2oA)
- [DGL博客 | 深入理解图注意力机制](https://zhuanlan.zhihu.com/p/57168713)
- [DGL框架tutorial小结](https://zhuanlan.zhihu.com/p/129746618)
  - g.ndata.pop('x') 可以移除节点特征，可以在计算过程中节省内存


## 4.4 PyTorch and DGL
- [Torch的广播机制](https://zhuanlan.zhihu.com/p/86997775)

## 4.5 Anomaly Detection
- [数据挖掘中常见的「异常检测」算法有哪些？](https://www.zhihu.com/question/280696035)

# 5 Linux
- [Make 命令教程](http://www.ruanyifeng.com/blog/2015/02/make.html)
- [LXC/LXD命令](https://www.machunjie.com/linux/560.html)

