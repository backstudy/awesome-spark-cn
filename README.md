# 前言
感兴趣大数据相关技术特别是Spark，想以此作为知识储备。  
之前玩爬虫时学习Python基础，所以自然选用了Python作为开发语言学习（学习资源不限于Python语言）
这里的东西会持续积累下去，欢迎Star，也欢迎发PR给我。

[我的Github](https://github.com/sherryriver)

# Spark介绍

Spark:内存并行计算框架

Spark 核心组件概述

- Spark Streaming：支持高吞吐量、支持容错的实时流数据处理
- Spark SQL， Data frames: 结构化数据查询
- MLLib：Spark 生态系统里用来解决大数据机器学习问题的模块
- GraphX是构建于Spark上的图计算模型

Spark 适用场景
目前大数据处理场景有以下几个类型：

1. 复杂的批量处理（Batch Data Processing），偏重点在于处理海量数据的能力，至于处理速度可忍受，通常的时间可能是在数十分钟到数小时；
2. 基于历史数据的交互式查询（Interactive Query），通常的时间在数十秒到数十分钟之间
3. 基于实时数据流的数据处理（Streaming Data Processing），通常在数百毫秒到数秒之间

目前对以上三种场景需求都有比较成熟的处理框架，第一种情况可以用Hadoop的MapReduce来进行批量海量数据处理，第二种情况可以Impala进行交互式查询，对于第三中情况可以用Storm分布式处理框架处理实时流式数据。以上三者都是比较独立，各自一套维护成本比较高，而Spark的出现能够一站式平台满意以上需求。

# 技术资料

## python语法学习

- [Python语法学习](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000) 基础知识学习，廖雪峰大神的Python教程 良心推荐

## scala语法学习

## Spark学习

### Spark core
- [Spark官网](http://spark.apache.org/) 官网必不可少
- [Spark官方文档 - 中文翻译](http://www.cnblogs.com/BYRans/p/5292763.html) 如果英语啃起来吃力的话，不妨可以对照翻译学习
### Spark Streaming

### Spark SQL

### Spark 机器学习

