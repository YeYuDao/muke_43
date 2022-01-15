# muke_43
Flink+ClickHouse 玩转企业级实时大数据开发
Flink+ClickHouse 玩转企业级实时大数据开发
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 Flink认知篇 

#### 本章中，将带领大家来一起认识大数据处业界中主流的分布式计算框架有哪些，进而引出为什么要学习的Flink框架、Flink是什么、发展史、特点；了解业务常见的实时处理框架有哪些，并知道在大厂中都在使用Flink做什么。帮助大家对Flink有初步得认识~~ ...
1-1 课前须知，这里有你需要了解得一切 (09:02)

1-2 课程目录 (01:39)

1-3 业界大数据分布式计算框架 (04:22)

1-4 初识Flink (10:47)

1-5 什么是Flink (12:12)

1-6 【科普小贴士】Flink发展史&特点&行业应用

1-7 学习一个新框架的方法论 (19:58)


### 第2章 Flink本地开发快速上手篇 

#### 本章中，将带领大家，通过Maven+IDEA构建基于Flink的开发环境，快速构建我们的第一个基于Flink的实时和离线分析案例。
2-1 课程目录 (01:38)

2-2 Maven部署 (09:20)

2-3 IDEA社区版和旗舰版区别 (03:17)

2-4 基于官方提供的命令来构建Flink项目 (10:25)

2-5 基于IDEA构建多module的Flink项目 (11:31)

2-6 Flink编程模型 (04:19)

2-7 基于Flink开发第一个实时处理案例之需求分析 (04:41)

2-8 基于Flink开发第一个实时处理案例之功能实现一 (11:44)

2-9 基于Flink开发第一个实时处理案例之功能实现二 (01:38)

2-10 基于Flink开发第一个实时处理案例之功能实现三 (05:14)

2-11 基于Flink开发第一个批处理案例之需求分析 (01:11)

2-12 基于Flink开发第一个批处理案例之功能实现 (03:52)

2-13 基于Flink开发第一个批处理案例之功能实现重构 (02:39)

2-14 基于Flink编程套路总结 (03:14)

2-15 本章重难点总结 (02:20)

2-16 【讨论题】关于数据结果的思考

2-17 【任务题】Lambda 表达式版案例实现


### 第3章 Flink部署篇

#### 本章中，将带领大家一起来完成Flink环境的部署，理解Flink的架构，如何提交作业到Flink集群运行，并认识Flink UI上核心参数的含义和使用策略。
3-1 课程目录 (01:51)

3-2 【环境配置】云主机开通及配置

3-3 Flink架构 (11:59)

3-4 Flink部署 (16:38)

3-5 Flink UI参数讲解 (04:53)

3-6 通过命令行方式提交&展示&取消Flink作业 (09:53)

3-7 通过UI方式提交&展示&取消Flink作业 (03:56)

3-8 关于并行度的补充 (03:02)

3-9 【讨论题】知识梳理

3-10 【任务题】Flink集群部署应用


### 第4章 Flink实时处理核心API基础篇

#### 本章中，将向大家介绍，基于Flink的DataStream API内置的三大核心要素的编程：Source、Tranformation、Action
4-1 课程目录 (01:24)

4-2 DataStream API概述 (07:38)

4-3 StreamExecutionEnvironment详解 (07:45)

4-4 Source概述 (08:56)

4-5 Source API编程之Socket及并行度 (05:11)

4-6 Source API编程之并行集合及并行度 (06:13)

4-7 【核心组件部署】ZooKeeper&Kafka部署

4-8 Source API编程之对接Kafka数据 (07:18)

4-9 Transformation概述 (06:41)

4-10 Transformation算子之map (11:12)

4-11 Transformation算子之filter (05:19)

4-12 Transformation算子之flatMap (05:18)

4-13 Transformation算子之keyBy (06:47)

4-14 Transformation算子之reduce (08:42)

4-15 Sink概述 (02:31)

4-16 Sink之print&printToErr及并行度 (09:00)

4-17 【任务题】词频统计

4-18 【任务题】Kafka消息的发送和接收

4-19 【任务题】readTextFile的并行度

4-20 【面试讨论题】Flink中的并行度

4-21 【面试讨论题】Task Slot的理解


### 第5章 Flink实时处理核心API进阶篇 

#### 本章中，将向大家介绍，基于Flink的DataStream API的三大核心要素的的高级特性，以及如何进行自定义功能的开发。
5-1 课程目录 (03:18)

5-2 MapFunction&RichMapFunction认识 (06:19)

5-3 通过RichMapFunction认识对应的生命周期方法 (07:25)

5-4 SourceFunction代码层级 (03:23)

5-5 自定义单并行度Source (09:15)

5-6 自定义多并行度Source (01:44)

5-7 自定义Source读取MySQL数据 (13:15)

5-8 Transformation算子之union (04:14)

5-9 Transformation算子之connect (07:37)

5-10 Transformation算子之CoMapFunction (06:10)

5-11 Transformation算子之CoFlatMapFunction (02:17)

5-12 自定义分区器 (10:22)

5-13 自定义MySQLSink功能实现 (10:33)

5-14 自定义MySQLSink需求分析 (04:20)

5-15 RedisSink功能实现 (09:02)

5-16 【核心组件部署】Redis部署

5-17 【任务题】自定义RedisSink

5-18 【任务题】自定义数据源

5-19 【面试讨论题】Flink中的分区策略

5-20 【面试讨论题】Flink DataStream中使用得算子


### 第6章 【项目实战第一篇】基于Flink+ClickHouse构建大数据实时分析项目实战

#### 本章节将实现项目实战的第一篇，从实时项目的架构、选型出发，介绍项目背景以及需求，并使用Flink已学知识点进行数据清洗、各种不同维度的功能开发、结果入库、自定义函数开发等
6-1 课程目录 (03:17)

6-2 同类产品分析 (06:07)

6-3 项目架构 (06:15)

6-4 项目子工程创建 (01:41)

6-5 字段说明 (05:25)

6-6 用户行为日志类定义 (03:01)

6-7 功能一需求分析 (03:18)

6-8 功能一实现之数据清洗 (04:59)

6-9 功能一实现之统计分析 (04:56)

6-10 功能一实现之统计结果入Redis (05:30)

6-11 功能一实现之拓展 (04:08)

6-12 需求二之功能分析 (06:51)

6-13 需求二之IP解析测试 (06:30)

6-14 功能二实现之自定义UDF函数解析IP地址 (04:55)

6-15 功能二实现之统计分析及入库 (03:35)

6-16 需求二之异步IO补充 (14:09)

6-17 前面两个需求可能会遇到的问题提炼 (04:55)

6-18 重难点总结 (02:22)

6-19 【任务题】统计新老用户的数据分布（1）

6-20 【任务题】统计新老用户的数据分布（2）

6-21 【任务题】统计结果存储

6-22 【面试讨论题】在数据清洗过程中做过的处理

6-23 【面试讨论题】使用Flink做实时处理项目架构选型


### 第7章 Flink时间语义及Window API篇

#### 本章中，我们将从流处理过程中的三大时间语义出发，通过场景及案例分析帮助大家理解时间三兄弟是什么意思、三兄弟对于业务逻辑处理的影响、Window的分类、以及基于增量的全量的Window Function编程。
7-1 课程目录 (04:09)

7-2 时间三兄弟 (10:16)

7-3 时间三兄弟举例解释 (05:31)

7-4 初识Window (03:55)

7-5 Window分类 (08:19)

7-6 Window Assigner (04:16)

7-7 滚动窗口 (03:40)

7-8 滑动窗口 (03:20)

7-9 会话窗口 (03:04)

7-10 窗口生命周期 (04:45)

7-11 基于ProcessingTime的Non-Keyed滚动窗口实战 (11:03)

7-12 基于ProcessingTime的Keyed滚动窗口实战 (04:21)

7-13 WindowFunction概述 (04:02)

7-14 WindowFunction之ReduceFunction实战 (05:12)

7-15 WindowFunction补充 (03:04)

7-16 WindowFunction之ProcessWindowFunction实战 (10:19)

7-17 重难点总结 (04:14)

7-18 【任务题】会话窗口编程

7-19 【任务题】滑动窗口编程

7-20 【面试讨论题】数据倾斜解决方案

7-21 【面试讨论题】对WindowFunction的认识

7-22 【面试讨论题】对于时间语义的理解

7-23 【面试讨论题】Flink中的窗口分析


### 第8章 Flink Watermark

#### 本章中将对Flink的Window编程中最核心的Watermark进行介绍。会带领大家认识，基于EventTime、Window、Watermark的综合使用，以及如何处理延迟或者乱序数据 。
8-1 课程目录 (02:57)

8-2 Watermark概述 (12:53)

8-3 基于EventTime和Watermark结合滚动窗口综合案例之没有延迟 (14:27)

8-4 基于EventTime和Watermark结合滚动窗口综合案例之有延迟 (15:16)

8-5 基于EventTime和Watermark结合滚动窗口综合案例之延迟数据丢失 (05:01)

8-6 基于EventTime和Watermark结合滚动窗口综合案例之捕获到延迟数据 (08:05)

8-7 重难点总结 (04:31)

8-8 【任务题】会话窗口编程

8-9 【任务题】滑动窗口编程

8-10 【面试讨论题】乱序数据解决方案

8-11 【面试讨论题】Flink中水印得理解


### 第9章 Flink状态管理篇

#### 本章带领大家学习在Flink流处理中为什么要引入State？State分类有哪些？如何自定义实现State功能？Flink中的Checkpoint机制有什么作用？重启策略以及StateBackend在生产上如何使用等等硬核内容。
9-1 课程目录 (02:53)

9-2 状态能为什么带来什么 (09:06)

9-3 State分类 (16:10)

9-4 使用ValueState完成求平均数功能 (14:45)

9-5 使用MapState完成求平均数功能 (05:59)

9-6 Flink Checkpoint机制 (15:04)

9-7 Flink应用程序中开启checkpoint (05:32)

9-8 Restart Strategy (08:20)

9-9 Checkpoint整合重启策略功能测试screenflow (07:35)

9-10 Checkpoint整合重启策略及状态功能测试screenflow (05:29)

9-11 Flink StateBackend (06:01)

9-12 Flink StateBackend之MemoryStateBackend (05:59)

9-13 Flink StateBackend之FsStateBackend (02:46)

9-14 Flink StateBackend之RocksDBStateBackend (05:35)

9-15 FsStateBackend 本地文件系统功能测试 (02:49)

9-16 ExternalizedCheckpointCleanup在生产上的使用 (05:12)

9-17 FsStateBackend HDFS功能测试 (02:32)

9-18 Checkpoint全流程测试之Flink UI操作 (07:28)

9-19 Checkpoint全流程测试之命令行操作 (03:47)

9-20 Checkpoint小结 (04:34)

9-21 Savepoints (09:26)

9-22 重难点总结 (02:23)

9-23 【任务题】使用ListState实现求平均数

9-24 【任务题】RocksDBStateBackend应用

9-25 【面试讨论题】Flink的容错机制

9-26 【面试讨论题】Checkpoint和SavePoint的区别

9-27 【面试讨论题】Flink中的状态存储


### 第10章 【项目实战第二篇】基于Flink+ClickHouse构建大数据实时分析项目实战

#### 本章节将实现项目实战的第二篇，将带领大家来学习在Flink中如何实现分组TopN的功能开发，以及使用Flink结合布隆过滤器，对项目实战第一篇的功能进行重构达到更好的性能。
10-1 课程目录 (02:19)

10-2 功能一之需求分析 (09:22)

10-3 功能一之实现01 (04:08)

10-4 功能一之实现02 (14:50)

10-5 功能一之实现03 (11:06)

10-6 功能二之需求分析 (03:26)

10-7 功能二之实现01 (07:26)

10-8 功能二之实现02 (03:22)

10-9 重难点总结 (07:05)

10-10 【任务题】布隆过滤器的原理

10-11 【任务题】ValueState应用

10-12 【面试讨论题】布隆过滤器应用分析

10-13 【面试讨论题】分组TopN的实现思路及数据倾斜的解决方案


### 第11章 【项目实战第三篇】基于Flink+ClickHouse构建大数据实时分析项目实战

#### 本章节将实现项目实战的第三篇，也是整个项目中最重要得一篇。不管是采用哪种实时处理框架，对于如何做到一次性精准消费都是一个非常重要且棘手的问题，这不仅是面试过程中也是在实际开发过程中必须要掌握的。本章节要彻底解决这些问题，并对代码进行重构封装，达到以后能完全复用的目的。...
11-1 课程目录 (02:46)

11-2 Flink对接Kafka数据入门 (11:20)

11-3 Flink整合Kafka代码开发 (11:55)

11-4 参数配置化并读取 (07:52)

11-5 Flink对接Kafka完整参数配置开发 (08:28)

11-6 Flink对接Kafka数据封装V1版本 (03:54)

11-7 Flink对接Kafka数据封装V2版本 (01:18)

11-8 Flink对接Kafka数据封装V3版本 (05:38)

11-9 Flink对接Kafka数据分析结果入Redis (06:55)

11-10 Flink ExactlyOnce图解 (08:39)

11-11 Flink两阶段提交 (08:46)

11-12 【任务题】自定义MySQL Sink

11-13 【面试讨论题】Flink整合kafka的两阶段提交的认识

11-14 【面试讨论题】Flink如何实现Exactly-Once


### 第12章 初识ClickHouse

#### 本章节将介绍当前非常火的OLAP框架ClickHouse。会带领大家认识ClickHouse的适用场景、部署、如何使用CH的SQL语言对大数据场景进行统计分析表引擎、ClickHouse 核心 API编程，以及如何整合各种不同数据源数据。
12-1 课程目录 (02:05)

12-2 背景需求 (03:39)

12-3 初识ClickHouse (08:17)

12-4 ClickHouse部署及快速入门 (10:59)

12-5 ClickHouse常用参数讲解 (02:53)

12-6 数据类型之Int和Float (08:45)

12-7 数据类型之Decimal (07:37)

12-8 数据类型之Bool (01:41)

12-9 数据类型之String&FixedString&UUID (07:35)

12-10 数据类型之Date&DateTime&DateTime64 (06:49)

12-11 数据类型之Array (01:53)

12-12 数据类型之Tuple (03:32)

12-13 数据类型之Nested (04:03)

12-14 数据库和表创建语法及数据库引擎 (05:38)

12-15 初识表引擎 (03:13)

12-16 表引擎之TinyLog (06:29)

12-17 表引擎之StripeLog (05:23)

12-18 表引擎之Log (03:01)

12-19 ClickHouse整合MySQL (10:18)

12-20 ClickHouse API编程 (04:55)

12-21 【任务题】ClickHouse的集群搭建

12-22 【任务题】ClickHouse的数据处理

12-23 【面试讨论题】谈谈对 ClickHouse 引擎得理解

12-24 【面试讨论题】ClickHouse得选择必然性


### 第13章 【项目实战终极篇】基于Flink+ClickHouse构建大数据实时分析项目实战

#### 本章节将实现项目实战的第四篇，也就是终极一战！本章中第一个案例将使用Flink对接ClickHouse，将处理过的明细数据写入ClickHouse，后续统计分析直接使用SQL完成，借以大大提升开发效率以及降低开发成本；第二个案例将使用Flink CEP完成恶意攻击风控告警，提高安全性。...
13-1 课程目录 (01:34)

13-2 现存问题描述及分析 (07:10)

13-3 ReplacingMergeTree引擎的用法 (06:46)

13-4 CH表如何设计 (04:54)

13-5 CH ID生成策略 (09:40)

13-6 Flink整合CH插入数据 (10:29)

13-7 使用Flink进行数据清洗 (08:23)

13-8 Flink清洗后的数据落地到CH并进行各种维度的统计分析 (09:05)

13-9 全流程服务器测试 (05:34)

13-10 引入CEP (04:38)

13-11 CEP模式概述 (05:34)

13-12 CEP功能开发 (08:32)

13-13 CEP功能测试 (04:15)

13-14 前端UI展示 (07:35)

13-15 【任务题】数据写入ClickHouse

13-16 【任务题】Flink on YARN运行全流程

13-17 【任务题】使用CEP完成数据提取

13-18 【面试讨论题】实时数据分析平台构建思路


### 第14章 Flink DataSet篇

#### 前面的章节主要是用流的角度进行阐述，本章中将介绍如何使用Flink的DataSet API完成离线场景的开发。通过本章得学习，相信大家能更好得理解Flink是如何能够支持批流一体的解决方案的。
14-1 课程目录 (01:53)

14-2 Flink批处理概述 (06:47)

14-3 对接数据源为csv格式的数据 (09:49)

14-4 对接数据源为压缩后的数据 (02:16)

14-5 对接数据源为子目录的数据 (03:19)

14-6 Transformation之map (05:42)

14-7 Transformation之mapPartition (03:04)

14-8 Transformation之distinct (02:47)

14-9 Transformation之first-n (07:37)

14-10 Sink (07:24)

14-11 Flink中分布式缓存的使用 (08:05)

14-12 Flink中计数器的使用 (07:37)

14-13 重难点总结 (04:34)

14-14 【任务题】实现join的功能

14-15 【任务题】join和cross算子的编程

14-16 【面试讨论题】Flink中使用分布式缓存的看法


### 第15章 Flink Table&SQL API篇

#### 本章将介绍如何使用Table API进行业务处理，以及如何更方便的使用SQL的方式基于Flink进行处理。【注意：SQL的方式在生产上用的非常多，因为SQL对于开发人员来说，门槛极低，只要使用SQL就可以进行大数据的统计分析操作，这是一件极好极好的事情】 ...
15-1 课程目录 (03:32)

15-2 Flink Table API&SQL概述 (06:08)

15-3 Flink Table API&SQL编程模型 (08:03)

15-4 Flink SQL整合DataStream编程 (06:59)

15-5 Flink Table API整合DataStream编程 (03:24)

15-6 Flink Table API整合DataStream编程toRetractStream使用 (06:34)

15-7 动态表和连续查询 (07:43)

15-8 图解连续查询 (05:24)

15-9 Table转Stream的方式 (07:06)

15-10 Flink Table API&SQL Connector概述 (03:38)

15-11 Flink Table API&SQL FileSystem Connector读取数据 (08:45)

15-12 Flink Table API&SQL FileSystem Connector写出数据 (04:33)

15-13 Flink Table API结合Window及EventTime编程 (16:13)

15-14 Flink SQL结合Window及EventTime编程 (05:03)

15-15 Flink UDF函数概述 (06:34)

15-16 Flink UDF函数编程实战 (08:24)

15-17 重难点总结 (06:10)

15-18 【任务题】实现数据的对接和Sink

15-19 【任务题】实现EventTime结合滑动窗口的功能测试

15-20 【任务题】完成IP解析的功能开发

15-21 【面试讨论题】Flink项目中选择哪种访问方式

15-22 【面试讨论题】Flink使用Kafka对接时的注意事项

15-23 【面试讨论题】Flink SQL是如何实现SQL的解析的


### 第16章 Flink版本升级篇

#### 本章中，将带领大家知晓大数本章节将介绍Flink版本升级时的注意事项：如，代码兼容性、服务器环境注意事项等。
16-1 课程目录 (02:00)

16-2 开发环境准备 (04:16)

16-3 老版本keyBy的用法 (07:06)

16-4 新版本keyBy的用法 (02:44)

16-5 老版本WM的用法 (06:29)

16-6 新版本WM的用法 (08:14)

16-7 新老版本Table API&SQL整合WM的用法 (16:10)

16-8 Flink on YARN运行及升级 (17:19)

16-9 【拓展阅读】Flink版本升级核心梳理


### 第17章 【拓展】基于Flink构建实时数仓项目实战

#### 本章中，将拓展讲解基于Canal、Kafka、Flink来构建实时数仓，掌握数仓的常用分层方式，业务数据的实时采集、双流join等
17-1 课程目录 (03:50)

17-2 实时数仓架构及分层 (16:59)

17-3 认识Canal (06:37)

17-4 Canal对接Kafka联调 (15:12)

17-5 使用TCP方式拉取Canal数据 (16:38)

17-6 双流JOIN设计思路 (07:27)

17-7 双流JOIN实现之对接数据 (09:19)

17-8 双流JOIN实现之设置WM (03:53)

17-9 双流JOIN实现之JOIN实现 (09:52)

17-10 双流JOIN实现之未关联上的数据处理方案 (05:41)

17-11 实时数仓数据流转&命名规范 (06:33)

17-12 【任务题】基于Flink实现维表的join

17-13 【任务题】双流join的测试

17-14 【面试讨论题】如何基于UI配置方式完成项目设计

17-15 【面试讨论题】maxwell和canal的区别


### 第18章 总结和展望

#### 本章节将对课程讲解的核心内容进行总结，并提出对未来发展的展望。
18-1 课程总结和回顾 (14:10)


[下载地址](https://51xueit.vip "下载地址")
