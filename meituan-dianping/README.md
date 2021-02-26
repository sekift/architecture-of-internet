# :bank:美团点评技术线

## :cat:1.前端

| 序号 | 名称      | 全称      | 简介                             | 技术栈 | 时间  | 网址                        | 发展 |
| ---- | --------- | --------- | -------------------------------- | ------ | ----- | --------------------------- | ---- |
| 1    | YUI3      | YUI       | The Yahoo User Interface Library | /      | 2013  | https://github.com/yui/yui3 | ---  |
| 2    | Node      | Node.js   | JavaScript 运行时工具            | /      | 2015- | https://nodejs.org          | ++   |
| 3    | app-proto | app-proto | 前端工程化开发                   | Node   | 2017  | /                           | -    |
| 4    |           |           |                                  |        |       |                             |      |

## :hamster:2.后端

| 序号 | 名称     | 全称              | 简介             | 技术栈                            | 时间 | 网址                                           | 发展 |
| ---- | -------- | ----------------- | ---------------- | --------------------------------- | ---- | ---------------------------------------------- | ---- |
| 1    | Flume    | Apache Flume      | 日志收集系统     | ZooKeeper、gossip、Hadoop、Thrift | 2013 | http://flume.apache.org/                       | ++   |
| 2    | Solr     | Apache Solr       | 企业级搜索服务器 | Java、Lucene                      | 2014 | https://lucene.apache.org/solr/                | ++   |
| 3    | Gradle   | Gradle Build Tool | 自动化构建工具   | Java                              | 2014 | https://gradle.org/                            | +++  |
| 4    | RestQL   | Meituan RestQL    | API开发工具      | HTTP                              | 2016 | https://github.com/Meituan-Dianping/koa-restql | --   |
| 5    | RabbitMQ | RabbitMQ          | 消息队列         | Erlang                            | 2016 | www.rabbitmq.com/                              | ++   |
| 6    | celery   | celery            | 消息传递作业队列 | Python                            | 2016 | https://docs.celeryproject.org                 | -    |
| 7    | MTrace   | Meituan MTrace    | 会话跟踪系统     | Java、Kafka、HBase、Hive          | 2016 | /                                              | -    |
| 8    | MTDDL    | Meituan MTDDL     | 数据访问层中间件 | Java                              | 2016 | /                                              | --   |
| 9    | Leaf     | Meituan Leaf      | 分布式ID生成系统 | Java                              | 2016 | https://github.com/Meituan-Dianping/Leaf       | -    |
| 10   | MGW      | Meituan Gateway   | 四层负载均衡网关 | /                                 | 2017 | /                                              | -    |

## :frog:3.数据库

| 序号 | 名称       | 全称                              | 简介             | 技术栈 | 时间  | 网址                                           | 发展 |
| ---- | ---------- | --------------------------------- | ---------------- | ------ | ----- | ---------------------------------------------- | ---- |
| 1    | OpenTSDB   | The Scalable Time Series Database | 时间序列数据库   | HBase  | 2014  | http://opentsdb.net/                           | +    |
| 2    | MySQL      | MySQL                             | 开源数据库       | /      | 2010  | https://www.mysql.com/                         | +++  |
| 3    | InfluxDB   | InfluxData                        | 时序数据库       | /      | 2016  | www.influxdata.com/                            | +    |
| 4    | Redis      | Redis                             | 键值对内存数据库 | ANSI C | 2013  | https://redis.io/                              | ++   |
| 5    | DBProxy    | Meituan DBProxy                   | 数据库中间件     | /      | 2015+ | https://github.com/Meituan-Dianping/DBProxy    | -    |
| 6    | SQLAdvisor | Meituan SQLAdvisor                | SQL优化工具      | C      | 2017  | https://github.com/Meituan-Dianping/SQLAdvisor | +    |

## :bear:4.大数据

| 序号 | 名称          | 全称            | 简介               | 技术栈          | 时间  | 网址                        | 发展 |
| ---- | ------------- | --------------- | ------------------ | --------------- | ----- | --------------------------- | ---- |
| 1    | Presto        | Facebook Presto | 分布式SQL查询引擎  | Hive、HDFS      | 2014  | https://prestodb.io/        | +    |
| 2    | Hadoop        | Apache Hadoop   | 分布式系统基础架构 | HDFS、MapReduce | 2014- | http://hadoop.apache.org/   | ++   |
| 3    | Hive          | Apache Hive     | 数据仓库系统       | HDFS、HBase     | 2014- | http://hive.apache.org/     | -    |
| 4    | Kafka         | Apache Kafka    | 分布式日志系统     | zookeeper       | 2015  | http://kafka.apache.org/    | +    |
| 5    | Spark         | Apache Spark    | 大数据并行计算框架 | YARN、HDFS      | 2016  | http://spark.apache.org/    | ++   |
| 6    | Zeppelin      | Apache Zeppelin | 数据分析可视化     | Spark           | 2016  | http://zeppelin.apache.org/ | +    |
| 7    | Storm         | Apache Storm    | 实时计算框架       | /               | 2016  | http://storm.apache.org/    | +    |
| 8    | Elasticsearch | Elasticsearch   | 搜索和数据分析引擎 | Java、Lucene    | 2016  | https://www.elastic.co/     | ++   |
| 9    |               |                 |                    |                 |       |                             |      |

## :cow:5.算法与AI

| 序号 | 名称 | 全称 | 简介 | 技术栈 | 时间 | 网址 | 发展 |
| ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |
| 1    |      |      |      |        |      |      |      |
| 2    |      |      |      |        |      |      |      |
| 3    |      |      |      |        |      |      |      |
| 4    |      |      |      |        |      |      |      |

## :monkey:6.运维

| 序号 | 名称      | 全称         | 简介               | 技术栈      | 时间 | 网址                                                   | 发展 |
| ---- | --------- | ------------ | ------------------ | ----------- | ---- | ------------------------------------------------------ | ---- |
| 1    | Docker    | Docker       | 开源的应用容器引擎 | Linux、GO   | 2015 | https://www.docker.com/<br />https://github.com/docker | +++  |
| 2    | Ursa      | Meituan Ursa | 分布式块存储系统   | /           | 2016 | /                                                      | -    |
| 3    | Mt-Falcon | Mt-Falcon    | 监控系统           | Open-Falcon | 2017 | /                                                      | ++   |
| 4    |           |              |                    |             |      |                                                        |      |

## :camel:7.安全

| 序号 | 名称 | 全称 | 简介 | 技术栈 | 时间 | 网址 | 发展 |
| ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |
| 1    |      |      |      |        |      |      |      |
| 2    |      |      |      |        |      |      |      |
| 3    |      |      |      |        |      |      |      |
| 4    |      |      |      |        |      |      |      |

## :panda_face:8.测试

| 序号 | 名称   | 全称            | 简介                    | 技术栈 | 时间 | 网址                                 | 发展 |
| ---- | ------ | --------------- | ----------------------- | ------ | ---- | ------------------------------------ | ---- |
| 1    | Emma   | Emma            | 代码覆盖工具            | Java   | 2014 | http://emma.sourceforge.net/         | +    |
| 2    | KIF    | KIF             | iOS自动化测试和持续集成 | iOS    | 2016 | https://github.com/kif-framework/KIF | +    |
| 3    | Spider | Dianping Spider | App自动化测试           | /      | 2016 | /                                    | --   |
| 4    | Appium | Appium          | App自动化测试           | /      | 2016 | http://appium.io                     | +    |
| 5    |        |                 |                         |        |      |                                      |      |

## :baby_chick:9.移动端

| 序号 | 名称  | 全称          | 简介               | 技术栈       | 时间 | 网址                                      | 发展 |
| ---- | ----- | ------------- | ------------------ | ------------ | ---- | ----------------------------------------- | ---- |
| 1    | Lint  | Android Lint  | 静态代码检查工具   | Java         | 2016 | http://tools.android.com/tips             | -    |
| 2    | Hertz | Meituan Hertz | 移动端性能监控     | /            | 2016 | /                                         | -    |
| 3    | Walle | Meituan Walle | 快速渠道包生产工具 | Java、Groovy | 2017 | https://github.com/Meituan-Dianping/walle | +    |
| 4    |       |               |                    |              |      |                                           |      |