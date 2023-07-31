# :bank:美团点评技术线

## :cat:1.前端

| 序号 | 项目      | 名称                  | 简介                                                         | 技术栈     | 应用                       | 时间  | 网址                                                  | 发展 |
| ---- | --------- | --------------------- | ------------------------------------------------------------ | ---------- | -------------------------- | ----- | ----------------------------------------------------- | ---- |
| 1    | YUI3      | Yahoo用户交互UI       | A library for building richly interactive web applications.  | /          | 酒旅                       | 2013  | [Git](https://github.com/yui/yui3)                    | ---  |
| 2    | Node      | JavaScript 运行时工具 | JavaScript 运行时工具                                        | /          | 酒店、酒旅(人机识别)、零售 | 2015- | [官网](https://nodejs.org)                            | ++   |
| 3    | app-proto | 前端工程化开发        | 前端工程化开发                                               | Node       | 酒旅                       | 2017  | /                                                     | -    |
| 4    | RestQL    | API开发工具           | API开发工具                                                  | HTTP       | 酒旅                       | 2016  | [Git](https://github.com/Meituan-Dianping/koa-restql) | --   |
| 5    | Yeoman    | Web 应用脚手架        | Yeoman 通用型脚手架工具，容易拓展，比较灵活，可创建属于自己的脚手架。Plop项目开发过程中，创建特定类型的文件。 | Node       | 酒旅                       | 2017  | [官网](https://yeoman.io/)                            | +    |
| 6    | Lego      | 可视化页面搭建        | 可视化页面搭建                                               | Java、Node | 外卖                       | 2017  | /                                                     | -    |
| 7    | doT       | 前端渲染引擎          | The fastest + concise javascript template engine for nodejs and browsers. Partials, custom delimiters and more. | JS、Node   | 外卖                       | 2017  | [Git](https://github.com/olado/doT)                   | -    |
| 8    | HUNT      | Web监控平台           | Web监控平台                                                  | SDK        | 点餐                       | 2017  | /                                                     | -    |
| 9    | Cyra      | 单页视图工具          | 单页视图工具                                                 | JS         | 点评                       | 2017  | /                                                     | -    |
| 10   | ThunderJS | CMD模块加载器         | CMD模块加载器                                                | JS         | 前端                       | 2017  | /                                                     | -    |
| 11   | BS        | 静态资源托管方案      | 静态资源托管方案                                             | Myers、CDN | 前端                       | 2017  | /                                                     | -    |
| 12   | mpvue     | 小程序开发工具        | 基于 Vue.js 的小程序开发框架，从底层支持 Vue.js 语法和构建工具体系。 | vue、h5    | 酒旅                       | 2017  | [Git](https://github.com/Meituan-Dianping/mpvue)      | -    |
| 13   | Bifrost   | 微前端框架            | 微前端框架                                                   | vue        | 闪购                       | 2019  | /                                                     | -    |
| 14   | Page      | 跨端一体化富文本管理  | Page-佩奇，跨端一体化富文本管理                              | js、Node   | 医药                       | 2021  | /                                                     | -    |

## :hamster:2.后端

| 序号 | 项目         | 名称                     | 简介                                                         | 技术栈                     | 应用       | 时间 | 网址                                                         | 发展 |
| ---- | ------------ | ------------------------ | ------------------------------------------------------------ | -------------------------- | ---------- | ---- | ------------------------------------------------------------ | ---- |
| 1    | Flume        | 日志收集系统             | *Flume*是Cloudera提供的一个高可用的，高可靠的，分布式的海量日志采集、聚合和传输的系统，Flume支持在日志系统中定制各类数据发送方，用于收集数据。 | ZK、gossip、Hadoop、Thrift | 基础服务   | 2013 | [官网](http://flume.apache.org/)                             | ++   |
| 2    | Solr         | 企业级搜索服务器         | *Solr*是一个独立的企业级搜索应用服务器，它对外提供类似于Web-service的API接口。 | Java、Lucene               | CRM、美旅  | 2014 | [官网](https://lucene.apache.org/solr/)                      | ++   |
| 3    | Gradle       | 自动化构建工具           | *Gradle*是一个基于Apache Ant和Apache Maven概念的项目自动化构建开源工具。 | Java                       | 基础服务   | 2014 | [官网](https://gradle.org/)                                  | +++  |
| 4    | RabbitMQ     | 消息队列                 | *RabbitMQ*是实现了高级消息队列协议（AMQP）的开源消息代理软件（亦称面向消息的中间件）。 | Erlang                     | 基础服务   | 2016 | [官网](www.rabbitmq.com/)                                    | ++   |
| 5    | celery       | 消息传递作业队列         | *Celery*是一个简单,灵活,可靠的分布式系统,用于处理大量消息,同时为操作提供维护此类系统所需的工具。 | Python                     | 基础服务   | 2016 | [官网](https://docs.celeryproject.org)                       | -    |
| 6    | MTrace       | 会话跟踪系统             | Meituan Trace，会话跟踪系统                                  | Java、Kafka、HBase、Hive   | 基础服务   | 2016 | /                                                            | -    |
| 7    | MTDDL        | 数据访问层中间件         | Meituan MTDDL，数据访问层中间件                              | Java                       | 外卖       | 2016 | /                                                            | --   |
| 8    | Leaf         | 分布式ID生成系统         | 生成全局唯一ID的系统                                         | Java、MySQL                | 基础服务   | 2016 | [Git](https://github.com/Meituan-Dianping/Leaf)              | -    |
| 9    | MGW          | 四层负载均衡网关         | Meituan Gateway，四层负载均衡网关                            | DPDK、RSS                  | 美团云     | 2017 | /                                                            | -    |
| 10   | Cat          | 实时应用监控平台         | CAT 是基于 Java 开发的实时应用监控平台，为美团点评提供了全面的实时监控告警服务。 | Java                       | 基础服务   | 2017 | [Git](https://github.com/dianping/cat)                       | --   |
| 11   | Maze         | 规则引擎                 | 规则引擎                                                     | /                          | 外卖CRM    | 2017 | /                                                            | -    |
| 12   | Kerberos     | 认证服务                 | 认证服务                                                     | /                          | 基础服务   | 2017 | /                                                            | +    |
| 13   | Rhino        | 熔断组件                 | Meituan Rhino，熔断组件                                      | /                          | 基础服务   | 2017 | /                                                            | -    |
| 14   | ProGuard     | Java代码优化器           | *ProGuard*是一个压缩、优化和混淆Java字节码文件的免费的工具，它可以删除无用的类、字段、方法和属性。 | Java、Kotlin               | /          | 2018 | [官网](https://www.guardsquare.com)                          | +    |
| 15   | Netty        | 网络通信层框架           | *Netty*是由JBOSS提供的一个java开源框架，提供异步的、事件驱动的网络应用程序框架和工具，用以快速开发高性能、高可靠性的网络服务器和客户端程序。 | Java                       | 基础服务   | 2018 | [官网](https://netty.io/)                                    | ++   |
| 16   | Oceanus      | HTTP服务治理框架         | HTTP服务治理框架                                             | Nginx、Lua                 | 基础服务   | 2018 | /                                                            | +    |
| 17   | UAS          | 用户行为系统             | User Action System，用户行为系统                             | /                          | 基础服务   | 2018 | /                                                            | +    |
| 18   | Camus        | kafka2hive数据工具       | LinkedIn's previous generation Kafka to HDFS pipeline.       | Kafka、Hive                | 基础服务   | 2018 | [Git](https://github.com/LinkedInAttic/camus)                | --   |
| 19   | Canal        | 增量订阅和消费组件       | 阿里巴巴 MySQL binlog 增量订阅&消费组件                      | MySQL                      | 物流       | 2018 | [Git](https://github.com/alibaba/canal)                      | +    |
| 20   | Databus      | 数据库变更实时传输系统   | Meituan Databus，Source-agnostic distributed change data capture system | /                          | 物流       | 2018 | [Git](https://github.com/linkedin/databus)                   | -    |
| 21   | DataMan      | 数据质量监管平台         | Meituan DataMan，数据质量监管平台                            | /                          | 美旅       | 2018 | /                                                            | -    |
| 22   | Quake        | 全链路压测平台           | Meituan Quake，全链路压测平台                                | Mtrace、MySQL              | /          | 2018 | /                                                            | -    |
| 23   | Gravity      | 流程管理组件             | Meituan Gravity，流程管理组件                                | activiti                   | 绩效系统   | 2018 | /                                                            | -    |
| 24   | Aviator      | 规则表达式引擎           | `AviatorScript` 是一门高性能、轻量级寄宿于 JVM （包括 Android 平台）之上的脚本语言。 | Java                       | 美旅       | 2018 | [Git](https://github.com/killme2008/aviator)                 | +    |
| 25   | BTrace       | 动态追踪服务工具         | BTrace - a safe, dynamic tracing tool for the Java platform  | Java                       | 打车       | 2019 | [Git](https://github.com/btraceio/btrace)                    | +    |
| 26   | OCTO         | 微服务通信框架及治理平台 | 美团致力于将Mtransport定位成一组高性能、高可用的企业级RPC通信框架，现将已在公司广泛使用，成熟稳定的Mtransport进行开源，开源后总名称为OCTO-RPC。 | Java、Zookeeper            | 基础服务   | 2019 | [Git](https://github.com/Meituan-Dianping/octo-rpc)、[Git](https://github.com/Meituan-Dianping/octo-ns)、[Git](https://github.com/Meituan-Dianping/octo-portal) | +    |
| 27   | Wedge        | 参数配置平台             | 参数配置平台                                                 | /                          | 搜索广告   | 2019 | /                                                            | -    |
| 28   | Gulf         | 日期管理系统             | Meituan Gulf，日期管理系统                                   | /                          | 基础服务   | 2020 | /                                                            | -    |
| 29   | QA-Assistant | 质量检查                 | QA-Assistant，质量检查                                       | /                          | /          | 2020 | /                                                            | -    |
| 30   | MNS          | 命名服务                 | Meituan Name Service，命名服务                               | OCTO、Zk、Mesh             | 基础服务   | 2020 | /                                                            | +    |
| 31   | Crane        | 分布式定时任务系统       | Crane，分布式定时任务系统                                    | /                          | /          | 2020 | /                                                            | +    |
| 32   | Service Mesh | 服务网格微服务框架       | Service *Mesh* 概念 Service *Mesh*又译作“服务网格”，作为服务间通信的基础设施层。 | /                          | 中间件     | 2020 | /                                                            | ++   |
| 33   | Shepherd     | API网关服务              | Shepherd API，API网关服务                                    | Java                       | 公共组件   | 2021 | /                                                            | ++   |
| 34   | Pike         | 终端消息投递服务         | Pike 2.0，终端消息投递服务                                   | Shark                      | 前端、直播 | 2021 | /                                                            | -    |
| 35   | GraphQL      | 图查询语言               | 图查询语言                                                   | Java                       | /          | 2021 |                                                              | +    |
| 36   | Sonic        | 热部署的IDEA插件         | 热部署的IDEA插件                                             | Java                       | 到家       | 2020 | /                                                            | -    |

## :frog:3.数据库

| 序号 | 项目        | 名称                    | 简介                                                         | 技术栈       | 应用     | 时间  | 网址                                                  | 发展 |
| ---- | ----------- | ----------------------- | ------------------------------------------------------------ | ------------ | -------- | ----- | ----------------------------------------------------- | ---- |
| 1    | OpenTSDB    | 时间序列数据库          | OpenTSDB 是一个时间序列数据库。它支持秒级数据采集所有 metrics，支持永久存储，可以做容量规划，并很容易地接入到现有的报警系统里。 | HBase        | 监控平台 | 2014  | [官网](http://opentsdb.net/)                          | +    |
| 2    | MySQL       | 开源数据库              | *MySQL*是一个关系型数据库管理系统                            | /            | 基础服务 | 2010  | [官网](https://www.mysql.com/)                        | +++  |
| 3    | InfluxDB    | 时序数据库              | influxdata是一个强大的实时[监控系统](https://so.csdn.net/so/search?q=监控系统&spm=1001.2101.3001.7020)，分为4个部分，Telegraf、InfluxDB、Chronograf、Kapacitor。 | /            | 压测工具 | 2016  | [官网](www.influxdata.com/)                           | +    |
| 4    | Redis       | 键值对内存数据库        | 键值对内存数据库                                             | ANSI C       | 基础服务 | 2013  | [官网](https://redis.io/)                             | ++   |
| 5    | DBProxy     | 数据库中间件            | Meituan DBProxy，DBProxy是由美团点评公司技术工程部DBA团队（北京）开发维护的一个基于MySQL协议的数据中间层。它在奇虎360公司开源的Atlas基础上，修改了部分bug，并且添加了很多特性。 | C、Altas     | 基础服务 | 2015+ | [Git](https://github.com/Meituan-Dianping/DBProxy)    | -    |
| 6    | SQLAdvisor  | SQL优化工具             | Meituan SQLAdvisor，是由美团点评公司技术工程部DBA团队（北京）开发维护的一个分析SQL给出索引优化建议的工具。它基于MySQL原生态词法解析，结合分析SQL中的where条件、聚合条件、多表Join关系 给出索引优化建议。 | C、MySQL     | 运维     | 2017  | [Git](https://github.com/Meituan-Dianping/SQLAdvisor) | 停滞 |
| 7    | Tair        | 键值对数据存储系统      | A distributed key-value storage system developed by Alibaba Group | C            | 基础服务 | 2016  | [Git](https://github.com/alibaba/tair)                | +    |
| 8    | MyFlash     | MySQL 闪回工具          | Meituan MyFlash，是由美团点评公司技术工程部开发维护的一个回滚DML操作的工具。该工具通过解析v4版本的binlog，完成回滚操作。相对已有的回滚工具，其增加了更多的过滤选项，让回滚更加容易。 |              | 运维     | 2017  | [Git](https://github.com/Meituan-Dianping/MyFlash)    | +    |
| 9    | squirrel    | 键值对内存数据库        | Meituan squirrel，键值对内存数据库                           | Redis        | 基础服务 | 2017  | /                                                     | -    |
| 10   | Zebra       | 数据库访问层中间件      | 美团点评集团统一使用的MySQL数据库访问层的中间件。主要提供对业务开发透明、读写分库、分库分表能力，并提供了端到端SQL监控的集成方案。 | /            | 物流     | 2016  | [Git](https://github.com/Meituan-Dianping/Zebra)      | -    |
| 11   | Alluxio     | 内存式存储系统          | Alluxio, data orchestration for analytics and machine learning in the cloud | Java         | 数据平台 | 2018  | [Git](https://github.com/Alluxio/alluxio)             | +    |
| 12   | Druid       | 高性能实时分析数据库    | Apache Druid: a high performance real-time analytics database. | Java         | /        | 2018  | [Git](https://github.com/apache/druid/)               | +    |
| 13   | TiDB        | 在线事务/分析处理数据库 | PingCAP TiDBRapidsDB，TiDB is an open-source, cloud-native, distributed, MySQL-Compatible database for elastic scale and real-time analytics. | Go           | 基础服务 | 2018  | [Git](https://github.com/pingcap/tidb)                | ++   |
| 14   | Doris       | OLAP 引擎               | An easy-to-use, high-performance and unified analytical database | Mesa、Impala | 外卖     | 2020  | [官网](http://doris.apache.org)                       | +    |
| 15   | NebulaGraph | 图数据库                | Nebula Graph是一款开源的图数据库，擅长处理千亿个顶点和万亿条边的超大规模数据集。 | C++          | 基础服务 | 2021  | [Git](https://github.com/vesoft-inc/nebula-graph)     | ++   |
| 16   | Ptubes      | 数据库恢复工具          | Ptubes是一款基于PITR（Point In Time  Recovery）方式实现的，解决异构数据库备份及多活的数据容灾平台，可帮助使用者提升数据库的安全性和产品能力。 | Java         | /        | 2022  | [Git](https://github.com/meituan/ptubes)              | ++   |
|      |             |                         |                                                              |              |          |       |                                                       |      |

## :bear:4.大数据

| 序号 | 项目          | 名称               | 简介                                                         | 技术栈          | 应用               | 时间  | 网址                                | 发展 |
| ---- | ------------- | ------------------ | ------------------------------------------------------------ | --------------- | ------------------ | ----- | ----------------------------------- | ---- |
| 1    | Presto        | 分布式SQL查询引擎  | 基于内存的并行计算，Facebook推出的分布式SQL交互式查询引擎 多个节点管道式执行  支持任意数据源 数据规模GB~PB 是一种Massively parallel processing（mpp）(大规模并行处理)模型。 | Hive、HDFS      | 基础服务           | 2014  | [官网](https://prestodb.io/)        | +    |
| 2    | Hadoop        | 分布式系统基础架构 | *Hadoop*是一个由Apache基金会所开发的分布式系统基础架构。用户可以在不了解分布式底层细节的情况下，开发分布式程序。 | HDFS、MapReduce | 基础服务           | 2014- | [官网](http://hadoop.apache.org/)   | ++   |
| 3    | Hive          | 数据仓库系统       | *hive*是基于Hadoop的一个数据仓库工具，用来进行数据提取、转化、加载，这是一种可以存储、查询和分析存储在Hadoop中的大规模数据的机制。 | HDFS、HBase     | 基础服务           | 2014- | [官网](http://hive.apache.org/)     | -    |
| 4    | Kafka         | 分布式日志系统     | *Kafka*是由Apache软件基金会开发的一个开源流处理平台，由Scala和Java编写。 | zookeeper       | 酒旅               | 2015  | [官网](http://kafka.apache.org/)    | +    |
| 5    | Spark         | 大数据并行计算框架 | 大数据并行计算框架                                           | YARN、HDFS      | 基础服务、数据平台 | 2016  | [官网](http://spark.apache.org/)    | ++   |
| 6    | Zeppelin      | 数据分析可视化     | Apache Zeppelin 是一个让交互式数据分析变得可行的基于网页的开源框架。Zeppelin提供了数据分析、数据可视化等功能 | Spark           | 基础服务           | 2016  | [官网](http://zeppelin.apache.org/) | +    |
| 7    | Storm         | 实时计算框架       | Apache Storm，是一个分布式实时流式计算平台                   | /               | 基础服务           | 2016  | [官网](http://storm.apache.org/)    | +    |
| 8    | Elasticsearch | 搜索和数据分析引擎 | *Elasticsearch* 是位于 Elastic Stack 核心的分布式搜索和分析引擎。Logstash 和 Beats 有助于收集、聚合和丰富您的数据并将其存储在 *Elasticsearch* 中。 | Java、Lucene    | 酒旅               | 2016  | [官网](https://www.elastic.co/)     | ++   |
| 9    | Flink         | 实时计算框架       | Flink 是一个针对流数据和批数据的分布式处理引擎。它主要是由 Java 代码实现。 | Scala           | 基础服务           | 2017  | [官网](https://flink.apache.org/)   | ++   |
| 10   | kylin         | 分析型数据仓库     | Apache Kylin™是一个开源的、分布式的分析型数据仓库，提供 Hadoop 之上的 SQL 查询接口及多维分析（OLAP）能力以支持超大规模数据，最初由eBay Inc.开发并贡献至开源社区。 | Java            | 基础服务           | 2016  | [官网](http://kylin.apache.org/cn/) | +    |

## :cow:5.算法与AI

| 序号 | 项目               | 名称                         | 简介                                                         | 技术栈           | 应用                 | 时间 | 网址                                                 | 发展 |
| ---- | ------------------ | ---------------------------- | ------------------------------------------------------------ | ---------------- | -------------------- | ---- | ---------------------------------------------------- | ---- |
| 1    | POI                | 机器学习的POI品类推荐算法    | 机器学习的POI品类推荐算法                                    | Naive Bayes      | 商家数据中心         | 2014 | /                                                    | -    |
| 2    | AlexNet            | 卷积神经网络                 | 卷积神经网络                                                 | CNN              | 图像识别             | 2017 | /                                                    | +    |
| 3    | GBDT               | 梯度提升决策树               | 梯度提升决策树                                               | /                | ETA配送              | 2017 | /                                                    | +    |
| 4    | Core ML            | 集成机器学习模型             | Core ML，集成机器学习模型                                    | Python           | AR                   | 2018 | /                                                    | +    |
| 5    | ps-lite            | 模型的训练框架               | 模型的训练框架，A lightweight parameter server interface     | C++              | 猜你喜欢             | 2018 | [Git](https://github.com/dmlc/ps-lite)               | +    |
| 6    | Kaldi              | 语音识别系统                 | 语音识别系统，kaldi-asr/kaldi is the official location of the Kaldi project. | C++              | /                    | 2018 | [Git](https://github.com/kaldi-asr/kaldi)            | ++   |
| 7    | Wide & Deep        | 分类和回归模型               | 分类和回归模型                                               | TensorFlow       | 广告                 | 2018 | /                                                    | ++   |
| 8    | TensorFlow Serving | 机器学习模型                 | 机器学习模型                                                 | TensorFlow       | 广告                 | 2018 | /                                                    | ++   |
| 9    | Faster R-CNN       | 深度学习目标检测框架         | 深度学习目标检测框架                                         | CNN              | OCR应用              | 2018 | /                                                    | +    |
| 10   | XGBoost            | 机器学习平台                 | 机器学习平台                                                 | /                | 配送                 | 2019 | /                                                    | +    |
| 11   | BERT               | 深度双向语言表征模型         | Bidirectional Encoder Representations from Transformers      | Transformer      | 搜索                 | 2019 | /                                                    | ++   |
| 12   | Jupyter            | 数据分析平台                 | Kaggle Kernels Jupyter，数据分析平台                         | /                | 民宿                 | 2019 | /                                                    | +    |
| 13   | Augur              | 在线预估框架                 | 在线预估框架                                                 | Transformer      | 搜索                 | 2020 | /                                                    | +    |
| 14   | Transformer        | 编码解码层                   | 编码解码层                                                   | Attention        | 搜索                 | 2020 | /                                                    | ++   |
| 15   | Turing             | 机器学习平台                 | 机器学习平台                                                 | Java             | 配送                 | 2020 | /                                                    | -    |
| 16   | CA-TCN             | 跨会话感知的时间卷积神经网络 | 跨会话感知的时间卷积神经网络                                 | RNN              | 增长技术             | 2020 | /                                                    | -    |
| 17   | DARTS-             | 神经网络架构搜索             | Code for "DARTS-: Robustly Stepping out of Performance Collapse Without Indicators" | NAS              | 视觉平台             | 2021 | [Git](https://github.com/Meituan-AutoML/DARTS-)      | +    |
| 18   | VisTR              | 视频分割识别算法             | End-to-End Video Instance Segmentation with Transformers     | CNN              | /                    | 2021 | [Git](https://github.com/Epiphqny/VisTR)             | +    |
| 19   | ConSERT            | 对比学习的句子表示迁移框架   | ConSERT: A Contrastive Framework for Self-Supervised Sentence Representation Transfer | BERT             | 知识图谱、KBQA、搜索 | 2021 | [Git](https://github.com/yym6472/ConSERT)            | -    |
| 20   | DPIN               | CTR模型                      | CTR模型                                                      | DL               | 广告平台             | 2021 | /                                                    | -    |
| 21   | YOLOv6             | YOLOv6                       | YOLOv6是美团视觉智能部研发的一款目标检测框架，致力于工业应用，本框架同时专注于检测的精度和推理效率。 | Jupyter Notebook | /                    | 2022 | [Git](https://github.com/meituan/YOLOv6)             | ++   |
| 22   | vision-ui          | 视觉UI分析                   | Vision UI 源于美团视觉测试工具，提供图像UI分析，识别服务     | Python           | /                    | 2022 | [Git](https://github.com/Meituan-Dianping/vision-ui) | +    |
| 23   | Tulong             | 图神经网络框架               | 图神经网络框架Tulong以及配套的图学习平台，自带MTGraph图计算库。 | Python           | 搜索与NLP            | 2022 | /                                                    | +    |
| 24   | Twins              | 视觉注意力模型               | Twins  是美团和阿德莱德大学合作提出的视觉注意力模型。        | Python           | /                    | 2022 | [Git](https://github.com/Meituan-AutoML/Twins)       | +    |

## :monkey:6.运维

| 序号 | 项目         | 名称                           | 简介                                                         | 技术栈            | 应用     | 时间 | 网址                            | 发展 |
| ---- | ------------ | ------------------------------ | ------------------------------------------------------------ | ----------------- | -------- | ---- | ------------------------------- | ---- |
| 1    | Docker       | 开源的应用容器引擎             | *Docker* 是一个开源的应用容器引擎，让开发者可以打包他们的应用以及依赖包到一个可移植的镜像中，然后发布到任何流行的 Linux或Windows操作系统的机器上，也可以实现虚拟化。 | Linux、GO、Glance | 基础服务 | 2015 | [官网](https://www.docker.com/) | +++  |
| 2    | Ursa         | 分布式块存储系统               | Meituan Ursa，分布式块存储系统                               | /                 | 美团云   | 2016 | /                               | -    |
| 3    | Mt-Falcon    | 监控系统                       | 监控系统                                                     | Open-Falcon       | SRE      | 2017 | /                               | ++   |
| 4    | AWP          | 静态化发布系统                 | 静态化发布系统                                               | /                 | 酒旅     | 2017 | /                               | -    |
| 5    | OPS          | 运维发布系统                   | 运维发布系统                                                 | /                 | 酒旅     | 2017 | /                               | -    |
| 6    | Jenkins      | 持续集成工具                   | *Jenkins*是一个开源软件项目，是基于Java开发的一种持续集成工具，用于监控持续重复的工作。 | Java              | 基础服务 | 2017 | [官网](https://www.jenkins.io/) | +++  |
| 7    | HULK         | 容器管理及弹性伸缩平台         | Meituan HULK，是美团的容器集群管理平台。                     | /                 | 基础服务 | 2017 | /                               | -    |
| 8    | Kubernetes   | 资源管理和调度                 | *Kubernetes* 是一个可移植、可扩展的开源平台,用于管理容器化的工作负载和服务,方便进行声明式配置和自动化。 | /                 | 基础服务 | 2018 | [官网](https://kubernetes.io/)  | +++  |
| 9    | Horae        | 时序数据异常检测系统           | 时序数据异常检测系统                                         | /                 | 交易     | 2020 | /                               | +    |
| 10   | Nest         | Serverless平台                 | Serverless平台                                               | Nginx、K8S        | 前端     | 2021 | /                               | -    |
| 11   | Orchestrator | MySQL 复制拓扑管理和可视化工具 | MySQL 复制拓扑管理和可视化工具                               | Go                | 基础     | 2023 | /                               | -    |

## :camel:7.安全

| 序号 | 项目    | 名称               | 简介                                                         | 技术栈 | 应用     | 时间 | 网址                                                | 发展 |
| ---- | ------- | ------------------ | ------------------------------------------------------------ | ------ | -------- | ---- | --------------------------------------------------- | ---- |
| 1    | Nmap    | 端口扫描器         | *Nmap*，也就是Network Mapper，最早是Linux下的网络扫描和嗅探工具包。 | python | 基础服务 | 2017 | [官网](https://nmap.org/)                           | +    |
| 2    | Masscan | 端口扫描器         | TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes. | /      | 基础服务 | 2017 | [Git](https://github.com/robertdavidgraham/masscan) | ++   |
| 3    | drozer  | 移动端渗透测试工具 | *drozer*是一款针对Android系统的安全测试框架。                | /      | Android  | 2017 | [链接](https://labs.f-secure.com/tools/drozer/)     | -    |
| 4    | Zeus    | 规则引擎           | 规则引擎                                                     | /      | 安全服务 | 2020 | /                                                   | -    |

## :panda_face:8.测试

| 序号 | 项目      | 名称                    | 简介                                                         | 技术栈   | 应用     | 时间 | 网址                                                | 发展 |
| ---- | --------- | ----------------------- | ------------------------------------------------------------ | -------- | -------- | ---- | --------------------------------------------------- | ---- |
| 1    | Emma      | 代码覆盖工具            | EMMA 是一个用于检测和报告 JAVA 代码覆盖率的开源工具。它不但能很好的用于小型项目，很方便得得出覆盖率报告，而且适用于大型企业级别的项目。 | Java     | 基础服务 | 2014 | [官网](http://emma.sourceforge.net/)                | +    |
| 2    | KIF       | iOS自动化测试和持续集成 | Keep It Functional - An iOS Functional Testing Framework     | iOS      | 猫眼     | 2016 | [Git](https://github.com/kif-framework/KIF)         | +    |
| 3    | Spider    | App自动化测试           | Dianping Spider，App自动化测试                               | /        | 基础服务 | 2016 | /                                                   | --   |
| 4    | Appium    | App自动化测试           | appium 是当前移动平台上主流的自动化测试工具之一。            | Cucumber | 酒旅     | 2016 | [官网](http://appium.io)                            | +    |
| 5    | JaCoCo    | 代码覆盖率工具          | JaCoCo，代码覆盖率工具                                       | Java     | 到店     | 2017 | [Git](https://github.com/jacoco/jacoco)             | -    |
| 6    | sysbench  | 数据库测试工具          | *sysbench*是一款开源的多线程性能测试工具，可以执行CPU/内存/线程/IO/数据库等方面的性能测试。 | MySQL    | 基础服务 | 2017 | [Git](https://github.com/topics/sysbench)           | +    |
| 7    | JMeter    | 压测工具                | Apache JMeter是Apache组织开发的基于Java的压力测试工具。用于对软件做压力测试，它最初被设计用于Web应用测试，但后来扩展到其他测试领域。 | Java     | 基础服务 | 2017 | [官网](https://jmeter.apache.org/)                  | ++   |
| 8    | Spock     | 单元测试工具            | *Spock* 是适合 Java 和 Groovy 应用程序的一个测试框架。       | Java     | 优选     | 2020 | [官网](https://spockframework.org)                  | ++   |
| 9    | Lyrebird  | 移动应测试平台          | **Lyrebird** 是一个基于拦截以及模拟 HTTP/HTTPS 网络请求的面向移动应用的插件式测试平台。 | Python   | 基础     | 2021 | [Git](https://github.com/Meituan-Dianping/lyrebird) | ++   |
| 10   | AlphaTest | 自动化测试平台          | AlphaTest是美团外卖自研的测试平台，采用了基于录制回放的方式进行设计，增加了环境模拟、跨App支持、混合技术栈的支持等能力，在使用简单的同时，也保障了用例的可维护性、测试的准确性等。 | /        | 外卖     | 2022 | /                                                   | -    |

## :baby_chick:9.移动端

| 序号 | 项目          | 名称                   | 简介                                                         | 技术栈          | 应用       | 时间  | 网址                                              | 发展 |
| ---- | ------------- | ---------------------- | ------------------------------------------------------------ | --------------- | ---------- | ----- | ------------------------------------------------- | ---- |
| 1    | Lint          | 静态代码检查工具       | Lint/TSLint/ESLint，静态代码检查工具                         | Java            | 酒旅       | 2016  | [官网](http://tools.android.com/tips)             | -    |
| 2    | Hertz         | 移动端性能监控         | Meituan Hertz，移动端性能监控                                | /               | 酒旅、外卖 | 2016  | /                                                 | -    |
| 3    | Walle         | 快速渠道包生产工具     | Meituan Walle，Android Signature V2 Scheme签名下的新一代渠道包打包神器 | Java、Groovy    | 酒旅       | 2017  | [Git](https://github.com/Meituan-Dianping/walle)  | +    |
| 4    | Shield        | 模块化 UI 界面         | `Shield`是一个模块化UI界面解决方案，它不仅仅是一个Native（Android&iOS）的UI开发框架，它不但具备高可复用性，协同开发等特性，还包括后端动态配置，动态模块等一系列解决方案。 | JS              | 到店       | 2017  | [Git](https://github.com/Meituan-Dianping/Shield) | +    |
| 5    | Flutter       | 跨平台UI框架           | Flutter makes it easy and fast to build beautiful apps for mobile and beyond | JS              | 外卖       | 2018+ | [Git](https://github.com/flutter/flutter)         | +++  |
| 6    | Picasso       | 跨平台动态化框架       | Meituan Picasso，是大众点评移动研发团队自研的高性能跨平台动态化[框架](https://so.csdn.net/so/search?q=框架&spm=1001.2101.3001.7020)，经过两年多的孕育和发展，目前在美团多个事业群已经实现了大规模的应用。 | DSL、TypeScript | 外卖、酒旅 | 2018  | /                                                 | -    |
| 7    | EasyReact     | 客户端开发框架         | Meituan EasyReact，是一款基于响应式编程范式的客户端开发框架，开发者可以使用此框架轻松地解决客户端的异步问题。 | Objective-C     |            | 2018  | [Git](https://github.com/meituan/EasyReact)       | -    |
| 8    | Logan         | 移动端基础日志组件     | Meituan Logan，是美团点评集团推出的大前端日志系统。名称是 Log 和 An 的组合，代表个体日志服务。 | C、JS           | 基础服务   | 2018  | [Git](https://github.com/Meituan-Dianping/Logan)  | ++   |
| 9    | MCI           | 流程研发系统           | Mobile continuous integration，流程研发系统                  | /               | 基础服务   | 2018  | /                                                 | -    |
| 10   | Robust        | 热修复框架             | Robust是新一代热更新系统，无差别兼容Android2.3-10版本；无需重启补丁实时生效，快速修复线上问题，补丁修补成功率高达99.9%。 | /               | 外卖       | 2018  | [Git](https://github.com/Meituan-Dianping/Robust) | -    |
| 11   | Holmes        | 动态日志系统           | Meituan Holmes，动态日志系统                                 | Android         | /          | 2018  | /                                                 | -    |
| 12   | LiveDataBus   | 消息总线框架           | EventBus for Android，消息总线，基于LiveData，具有生命周期感知能力，支持Sticky，支持AndroidX，支持跨进程，支持跨APP。 | Android         | 收银       | 2018  | [Git](https://github.com/JeremyLiao/LiveDataBus)  | +    |
| 13   | modular-event | 组件化消息总线框架     | modular-event，组件化消息总线框架                            | Android         | 收银       | 2018  | /                                                 | -    |
| 14   | WMRouter      | Android路由框架        | WMRouter是一款Android路由框架，基于组件化的设计思路，有功能灵活、使用简单的特点。 | Android         | 外卖       | 2018  | [Git](https://github.com/meituan/WMRouter)        | +    |
| 15   | Graver        | UI 渲染框架            | Graver 是一款高效的 UI 渲染框架，它以更低的资源消耗来构建十分流畅的 UI 界面。Graver 独创性的采用了基于绘制的视觉元素分解方式来构建界面，得益于此，该框架能让 UI 渲染过程变得更加简单、灵活。 | iOS             | 外卖       | 2018  | [Git](https://github.com/Meituan-Dianping/Graver) | -    |
| 16   | Hades         | 静态分析框架           | Meituan Hades，静态分析框架                                  | C、CouchDB      | 基础服务   | 2018  | /                                                 | -    |
| 17   | beeshell      | 基础组件库             | Meituan beeshell，一个 React Native 应用的基础组件库，基于 0.53.3 版本，提供一整套开箱即用的高质量组件。 | /               | 蜜蜂       | 2018  | [Git](https://github.com/meituan/beeshell)        | -    |
| 18   | OpenSTF       | 云真机平台             | 云真机平台                                                   | /               | 基础服务   | 2018  | /                                                 | +    |
| 19   | MTFlexbox     | 跨平台动态化方案       | Meituan Flexbox，跨平台动态化方案                            | XML、CSS3       | 外卖       | 2019  | /                                                 | -    |
| 20   | Litho         | 声明式UI框架           | 声明式UI框架                                                 | RecyclerView    | 终端       | 2019  | /                                                 | -    |
| 21   | MRN           | 移动应用开发框架       | Meituan React Native，移动应用开发框架                       | React Native    | 终端       | 2019  | /                                                 | +    |
| 22   | Probe         | Android线上OOM定位组件 | Android线上OOM定位组件                                       | /               | 配送       | 2019  | /                                                 | -    |
| 23   | Sketch        | 积木UI统一解决方案     | Meituan Sketch，积木UI统一解决方案                           | /               | 前端       | 2020  | /                                                 | +    |
| 24   | R2X           | 终端容器无关化框架     | React2X，终端容器无关化框架                                  | React           | 前端       | 2021  | /                                                 | -    |
| 25   | RoboAspectJ   | 移动端切面开发         | A gradle plugin that enables AOP in android.                 | Groovy          | /          | 2016  | [Git](https://github.com/meituan/RoboAspectJ)     | --   |
| 26   | Phoenix       | 端侧 CDN 容灾方案      | 在端侧进行容灾，就需要感知 CDN 的可用性，然后实现端侧自动切换的能力。 | /               | 外卖       | 2021  | /                                                 | -    |
| 27   | Robust        | Android实时热修复框架  | 基于方法插桩的实时热修复框架，主要优势是实时生效、零 Hook 兼容所有 Android 版本 | Java            | app        | 2023  | /                                                 | +    |

