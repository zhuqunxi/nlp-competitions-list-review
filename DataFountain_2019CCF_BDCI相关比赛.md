### 一.O2O商铺食品安全相关评论发现

[比赛地址](https://www.datafountain.cn/competitions/370)，二分类，提供了一个数据集。

### 二.文本实体识别及关系抽取

[比赛地址](https://www.datafountain.cn/competitions/371)

基于SemEval 2010 Task8 Dataset，该数据集原本是用于神经关系抽取(NRE)的基础数据集。NRE任务的设定是给定context和context中的实体，判断实体之间的关系。该赛道第一步需要做一个实体识别的模型，其实这也是真实场景下关系抽取的应用场景，主要用于信息抽取。[自己在该数据集上的一个实现工作](https://github.com/zhpmatrix/BERTem)

类似比赛最近一段时间较多，可以看下**2019语言与智能技术竞赛**相关的比赛和“之江杯”的电商评论情感分析赛道。具体方案不多聊了，在该repo下应该也可以找到。

### 三.汽车论坛消费者用车体验内容的判别与标注

这个比赛不是CCF的，暂且放在这里。[比赛地址](https://www.datafountain.cn/competitions/365/datasets)

**比赛简介**：比赛用数据集来自**国内三大知名汽车论坛**，2017年至2018年期间，6款指定汽车车型子论坛的网友发帖内容；数据通过网络爬虫而得。数据经过内容语义分析处理后，标记出是否为真实汽车消费者发布内容，如果是则后续进一步标引其内容类别归属，如：空间、动力、座椅、舒适性、油耗、价格等（本次比赛暂不涉及此步骤）。通过标引后的内容，汽车业务部门会根据消费者反馈意见及其比例分布，用于改进后续车型设计开发和质量优化提升等工作。

一个分类任务，提供了一个数据集。关于汽车类的相关比赛，在该比赛平台上较多。同科研论文领域类似，汽车相关的文本分析也是一个非常棒的技术场景，具体上可以展开很多技术。比如，同样可以基于该数据做信息抽取等子任务。
