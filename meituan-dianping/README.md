# :bank:美团点评技术线

## :cat:1.前端

| 序号 | 名称      | 全称           | 简介                             | 技术栈     | 应用                       | 时间  | 网址                                                  | 发展 |
| ---- | --------- | -------------- | -------------------------------- | ---------- | -------------------------- | ----- | ----------------------------------------------------- | ---- |
| 1    | YUI3      | YUI            | The Yahoo User Interface Library | /          | 酒旅                       | 2013  | [Git](https://github.com/yui/yui3)                    | ---  |
| 2    | Node      | Node.js        | JavaScript 运行时工具            | /          | 酒店、酒旅(人机识别)、零售 | 2015- | [官网](https://nodejs.org)                            | ++   |
| 3    | app-proto | app-proto      | 前端工程化开发                   | Node       | 酒旅                       | 2017  | /                                                     | -    |
| 4    | RestQL    | Meituan RestQL | API开发工具                      | HTTP       | 酒旅                       | 2016  | [Git](https://github.com/Meituan-Dianping/koa-restql) | --   |
| 5    | Yeoman    | Yeoman         | Web 应用脚手架                   | Node       | 酒旅                       | 2017  | [官网](https://yeoman.io/)                            | +    |
| 6    | Lego      | 乐高           | 可视化页面搭建                   | Java、Node | 外卖                       | 2017  | /                                                     | -    |
| 7    | doT       | doT.js         | 前端渲染引擎                     | JS、Node   | 外卖                       | 2017  | [Git](https://github.com/olado/doT)                   | -    |
| 8    | HUNT      | HUNT           | Web监控平台                      | SDK        | 点餐                       | 2017  | /                                                     | -    |
| 9    | Cyra      | Cyra           | 单页视图工具                     | JS         | 点评                       | 2017  | /                                                     | -    |
| 10   | ThunderJS | ThunderJS      | CMD模块加载器                    | JS         | 前端                       | 2017  | /                                                     | -    |
| 11   | BS        | Build Service  | 静态资源托管方案                 | Myers、CDN | 前端                       | 2017  | /                                                     | -    |
| 12   | mpvue     | mpvue          | 小程序开发工具                   | vue、h5    | 酒旅                       | 2017  | [Git](https://github.com/Meituan-Dianping/mpvue)      | -    |

## :hamster:2.后端

| 序号 | 名称     | 全称              | 简介             | 技术栈                            | 应用      | 时间 | 网址                                            | 发展 |
| ---- | -------- | ----------------- | ---------------- | --------------------------------- | --------- | ---- | ----------------------------------------------- | ---- |
| 1    | Flume    | Apache Flume      | 日志收集系统     | ZooKeeper、gossip、Hadoop、Thrift | 基础服务  | 2013 | [官网](http://flume.apache.org/)                | ++   |
| 2    | Solr     | Apache Solr       | 企业级搜索服务器 | Java、Lucene                      | CRM、酒旅 | 2014 | [官网](https://lucene.apache.org/solr/)         | ++   |
| 3    | Gradle   | Gradle Build Tool | 自动化构建工具   | Java                              | 基础服务  | 2014 | [官网](https://gradle.org/)                     | +++  |
| 4    | RabbitMQ | RabbitMQ          | 消息队列         | Erlang                            | 基础服务  | 2016 | [官网](www.rabbitmq.com/)                       | ++   |
| 5    | celery   | celery            | 消息传递作业队列 | Python                            | 基础服务  | 2016 | [官网](https://docs.celeryproject.org)          | -    |
| 6    | MTrace   | Meituan Trace     | 会话跟踪系统     | Java、Kafka、HBase、Hive          | 基础服务  | 2016 | /                                               | -    |
| 7    | MTDDL    | Meituan MTDDL     | 数据访问层中间件 | Java                              | 外卖      | 2016 | /                                               | --   |
| 8    | Leaf     | Meituan Leaf      | 分布式ID生成系统 | Java、MySQL                       | 基础服务  | 2016 | [Git](https://github.com/Meituan-Dianping/Leaf) | -    |
| 9    | MGW      | Meituan Gateway   | 四层负载均衡网关 | DPDK、RSS                         | 美团云    | 2017 | /                                               | -    |
| 10   | Cat      | Meituan Cat       | 实时应用监控平台 | Java                              | 基础服务  | 2017 | [Git](https://github.com/dianping/cat)          | --   |
| 11   | Maze     | Maze              | 规则引擎         | /                                 | 外卖CRM   | 2017 | /                                               | -    |
| 12   | Kerberos | Kerberos          | 认证服务         | /                                 | 基础服务  | 2017 | /                                               | +    |
| 13   | Rhino    | Meituan Rhino     | 熔断组件         | /                                 | 基础服务  | 2017 | /                                               | -    |

## :frog:3.数据库

| 序号 | 名称       | 全称                              | 简介               | 技术栈   | 应用     | 时间  | 网址                                                  | 发展 |
| ---- | ---------- | --------------------------------- | ------------------ | -------- | -------- | ----- | ----------------------------------------------------- | ---- |
| 1    | OpenTSDB   | The Scalable Time Series Database | 时间序列数据库     | HBase    | 监控平台 | 2014  | [官网](http://opentsdb.net/)                          | +    |
| 2    | MySQL      | MySQL                             | 开源数据库         | /        | 基础服务 | 2010  | [官网](https://www.mysql.com/)                        | +++  |
| 3    | InfluxDB   | InfluxData                        | 时序数据库         | /        | 压测工具 | 2016  | [官网](www.influxdata.com/)                           | +    |
| 4    | Redis      | Redis                             | 键值对内存数据库   | ANSI C   | 基础服务 | 2013  | [官网](https://redis.io/)                             | ++   |
| 5    | DBProxy    | Meituan DBProxy                   | 数据库中间件       | C、Altas | 基础服务 | 2015+ | [Git](https://github.com/Meituan-Dianping/DBProxy)    | -    |
| 6    | SQLAdvisor | Meituan SQLAdvisor                | SQL优化工具        | C、MySQL | 运维     | 2017  | [Git](https://github.com/Meituan-Dianping/SQLAdvisor) | +    |
| 7    | Tair       | Tair                              | 键值对数据存储系统 | C        | 基础服务 | 2016  | [Git](https://github.com/alibaba/tair)                | +    |
| 8    | MyFlash    | Meituan MyFlash                   | MySQL 闪回工具     |          | 运维     | 2017  | [Git]( https://github.com/Meituan-Dianping/)          | +    |
| 9    | squirrel   | Meituan squirrel                  | 键值对内存数据库   | Redis    | 基础服务 | 2017  | /                                                     | -    |

## :bear:4.大数据

| 序号 | 名称          | 全称            | 简介               | 技术栈          | 应用               | 时间  | 网址                                | 发展 |
| ---- | ------------- | --------------- | ------------------ | --------------- | ------------------ | ----- | ----------------------------------- | ---- |
| 1    | Presto        | Facebook Presto | 分布式SQL查询引擎  | Hive、HDFS      | 基础服务           | 2014  | [官网](https://prestodb.io/)        | +    |
| 2    | Hadoop        | Apache Hadoop   | 分布式系统基础架构 | HDFS、MapReduce | 基础服务           | 2014- | [官网](http://hadoop.apache.org/)   | ++   |
| 3    | Hive          | Apache Hive     | 数据仓库系统       | HDFS、HBase     | 基础服务           | 2014- | [官网](http://hive.apache.org/)     | -    |
| 4    | Kafka         | Apache Kafka    | 分布式日志系统     | zookeeper       | 酒旅               | 2015  | [官网](http://kafka.apache.org/)    | +    |
| 5    | Spark         | Apache Spark    | 大数据并行计算框架 | YARN、HDFS      | 基础服务、数据平台 | 2016  | [官网](http://spark.apache.org/)    | ++   |
| 6    | Zeppelin      | Apache Zeppelin | 数据分析可视化     | Spark           | 基础服务           | 2016  | [官网](http://zeppelin.apache.org/) | +    |
| 7    | Storm         | Apache Storm    | 实时计算框架       | /               | 基础服务           | 2016  | [官网](http://storm.apache.org/)    | +    |
| 8    | Elasticsearch | Elasticsearch   | 搜索和数据分析引擎 | Java、Lucene    | 酒旅               | 2016  | [官网](https://www.elastic.co/)     | ++   |
| 9    | Flink         | Apache Flink    | 实时计算框架       | Scala           | 基础服务           | 2017  | [官网](https://flink.apache.org/)   | ++   |
| 10   | kylin         | Apache kylin    | 分析型数据仓库     | Java            | 基础服务           | 2016  | [官网](http://kylin.apache.org/cn/) | +    |

## :cow:5.算法与AI

| 序号 | 名称    | 全称                            | 简介                      | 技术栈      | 应用         | 时间 | 网址 | 发展 |
| ---- | ------- | ------------------------------- | ------------------------- | ----------- | ------------ | ---- | ---- | ---- |
| 1    | POI     | POI推荐                         | 机器学习的POI品类推荐算法 | Naive Bayes | 商家数据中心 | 2014 | /    | -    |
| 2    | AlexNet | AlexNet                         | 卷积神经网络              | CNN         | 图像识别     | 2017 | /    | +    |
| 3    | GBDT    | Gradient Boosted Decision Trees | 梯度提升决策树            | /           | ETA配送      | 2017 | /    | +    |
| 4    |         |                                 |                           |             |              |      |      |      |

## :monkey:6.运维

| 序号 | 名称      | 全称                                     | 简介                   | 技术栈            | 应用     | 时间 | 网址                            | 发展 |
| ---- | --------- | ---------------------------------------- | ---------------------- | ----------------- | -------- | ---- | ------------------------------- | ---- |
| 1    | Docker    | Docker                                   | 开源的应用容器引擎     | Linux、GO、Glance | 基础服务 | 2015 | [官网](https://www.docker.com/) | +++  |
| 2    | Ursa      | Meituan Ursa                             | 分布式块存储系统       | /                 | 美团云   | 2016 | /                               | -    |
| 3    | Mt-Falcon | Mt-Falcon                                | 监控系统               | Open-Falcon       | SRE      | 2017 | /                               | ++   |
| 4    | AWP       | /                                        | 静态化发布系统         | /                 | 酒旅     | 2017 | /                               | -    |
| 5    | OPS       | Operation and Maintenance Release System | 运维发布系统           | /                 | 酒旅     | 2017 | /                               | -    |
| 6    | Jenkins   | Jenkins                                  | 持续集成工具           | Java              | 基础服务 | 2017 | [官网](https://www.jenkins.io/) | +++  |
| 7    | HULK      | Meituan HULK                             | 容器管理及弹性伸缩平台 | /                 | 基础服务 | 2017 | /                               | -    |

## :camel:7.安全

| 序号 | 名称    | 全称           | 简介               | 技术栈 | 应用     | 时间 | 网址                                                | 发展 |
| ---- | ------- | -------------- | ------------------ | ------ | -------- | ---- | --------------------------------------------------- | ---- |
| 1    | Nmap    | Network Mapper | 端口扫描器         | python | 基础服务 | 2017 | [官网](https://nmap.org/)                           | +    |
| 2    | Masscan | Masscan        | 端口扫描器         | /      | 基础服务 | 2017 | [Git](https://github.com/robertdavidgraham/masscan) | ++   |
| 3    | drozer  | drozer         | 移动端渗透测试工具 | /      | Android  | 2017 | [链接](https://labs.f-secure.com/tools/drozer/)     | -    |
| 4    |         |                |                    |        |          |      |                                                     |      |

## :panda_face:8.测试

| 序号 | 名称     | 全称            | 简介                    | 技术栈   | 应用     | 时间 | 网址                                        | 发展 |
| ---- | -------- | --------------- | ----------------------- | -------- | -------- | ---- | ------------------------------------------- | ---- |
| 1    | Emma     | Emma            | 代码覆盖工具            | Java     | 基础服务 | 2014 | [官网](http://emma.sourceforge.net/)        | +    |
| 2    | KIF      | KIF             | iOS自动化测试和持续集成 | iOS      | 猫眼     | 2016 | [Git](https://github.com/kif-framework/KIF) | +    |
| 3    | Spider   | Dianping Spider | App自动化测试           | /        | 基础服务 | 2016 | /                                           | --   |
| 4    | Appium   | Appium          | App自动化测试           | Cucumber | 酒旅     | 2016 | [官网](http://appium.io)                    | +    |
| 5    | JaCoCo   | JaCoCo          | 代码覆盖率工具          | Java     | 到店     | 2017 | [Git](https://github.com/jacoco/jacoco)     | -    |
| 6    | sysbench | sysbench        | 数据库测试工具          | MySQL    | 基础服务 | 2017 | [Git](https://github.com/topics/sysbench)   | +    |
| 7    | JMeter   | Apache JMeter   | 压测工具                | Java     | 基础服务 | 2017 | [官网](https://jmeter.apache.org/)          | ++   |

## :baby_chick:9.移动端

| 序号 | 名称      | 全称                          | 简介               | 技术栈          | 应用       | 时间 | 网址                                                 | 发展 |
| ---- | --------- | ----------------------------- | ------------------ | --------------- | ---------- | ---- | ---------------------------------------------------- | ---- |
| 1    | Lint      | Android Lint                  | 静态代码检查工具   | Java            | 酒旅       | 2016 | [官网](http://tools.android.com/tips)                | -    |
| 2    | Hertz     | Meituan Hertz                 | 移动端性能监控     | /               | 酒旅、外卖 | 2016 | /                                                    | -    |
| 3    | Walle     | Meituan Walle                 | 快速渠道包生产工具 | Java、Groovy    | 酒旅       | 2017 | [Git](https://github.com/Meituan-Dianping/walle)     | +    |
| 4    | Shield    | Shield                        | 模块化 UI 界面     | JS              | 到店       | 2017 | [Git](https://github.com/Meituan-Dianping/Shield)    | +    |
| 5    | Flutter   | Flutter                       | 跨平台UI框架       | JS              | 外卖       | 2018 | [Git](https://github.com/flutter/flutter)            | ++   |
| 6    | Picasso   | Meituan Picasso               | 跨平台动态化框架   | DSL、TypeScript | 外卖、酒旅 | 2018 | /                                                    | -    |
| 7    | EasyReact | Meituan EasyReact             | 客户端开发框架     | Objective-C     |            | 2018 | [Git](https://github.com/meituan-dianping/EasyReact) | -    |
| 8    | Logan     | Meituan Logan                 | 移动端基础日志组件 | C、JS           | 基础服务   | 2018 | [Git](https://github.com/Meituan-Dianping/Logan)     | +    |
| 9    | MCI       | Mobile continuous integration | 流程研发系统       | /               | 基础服务   | 2018 | /                                                    | -    |
| 10   | Robust    | Robust                        | 热修复框架         | /               | 外卖       | 2018 | [Git](https://github.com/Meituan-Dianping/Robust)    | -    |
| 11   | Holmes    | Meituan Holmes                | 动态日志系统       | Android         | /          | 2018 | /                                                    | -    |

