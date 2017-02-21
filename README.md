# Spark学习

Spark:内存并行计算框架

Spark 核心组件概述
Spark Streaming：支持高吞吐量、支持容错的实时流数据处理
Spark SQL， Data frames: 结构化数据查询
MLLib：Spark 生态系统里用来解决大数据机器学习问题的模块
GraphX是构建于Spark上的图计算模型

Spark 适用场景
目前大数据处理场景有以下几个类型：
1. 复杂的批量处理（Batch Data Processing），偏重点在于处理海量数据的能力，至于处理速度可忍受，通常的时间可能是在数十分钟到数小时；
2. 基于历史数据的交互式查询（Interactive Query），通常的时间在数十秒到数十分钟之间
3. 基于实时数据流的数据处理（Streaming Data Processing），通常在数百毫秒到数秒之间

目前对以上三种场景需求都有比较成熟的处理框架，第一种情况可以用Hadoop的MapReduce来进行批量海量数据处理，第二种情况可以Impala进行交互式查询，对于第三中情况可以用Storm分布式处理框架处理实时流式数据。以上三者都是比较独立，各自一套维护成本比较高，而Spark的出现能够一站式平台满意以上需求。
