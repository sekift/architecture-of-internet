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
| 13   | Bifrost   | Bifrost        | 微前端框架                       | vue        | 闪购                       | 2019  | /                                                     | -    |

## :hamster:2.后端

| 序号 | 名称         | 全称                 | 简介                     | 技术栈                            | 应用      | 时间 | 网址                                                         | 发展 |
| ---- | ------------ | -------------------- | ------------------------ | --------------------------------- | --------- | ---- | ------------------------------------------------------------ | ---- |
| 1    | Flume        | Apache Flume         | 日志收集系统             | ZooKeeper、gossip、Hadoop、Thrift | 基础服务  | 2013 | [官网](http://flume.apache.org/)                             | ++   |
| 2    | Solr         | Apache Solr          | 企业级搜索服务器         | Java、Lucene                      | CRM、美旅 | 2014 | [官网](https://lucene.apache.org/solr/)                      | ++   |
| 3    | Gradle       | Gradle Build Tool    | 自动化构建工具           | Java                              | 基础服务  | 2014 | [官网](https://gradle.org/)                                  | +++  |
| 4    | RabbitMQ     | RabbitMQ             | 消息队列                 | Erlang                            | 基础服务  | 2016 | [官网](www.rabbitmq.com/)                                    | ++   |
| 5    | celery       | celery               | 消息传递作业队列         | Python                            | 基础服务  | 2016 | [官网](https://docs.celeryproject.org)                       | -    |
| 6    | MTrace       | Meituan Trace        | 会话跟踪系统             | Java、Kafka、HBase、Hive          | 基础服务  | 2016 | /                                                            | -    |
| 7    | MTDDL        | Meituan MTDDL        | 数据访问层中间件         | Java                              | 外卖      | 2016 | /                                                            | --   |
| 8    | Leaf         | Meituan Leaf         | 分布式ID生成系统         | Java、MySQL                       | 基础服务  | 2016 | [Git](https://github.com/Meituan-Dianping/Leaf)              | -    |
| 9    | MGW          | Meituan Gateway      | 四层负载均衡网关         | DPDK、RSS                         | 美团云    | 2017 | /                                                            | -    |
| 10   | Cat          | Meituan Cat          | 实时应用监控平台         | Java                              | 基础服务  | 2017 | [Git](https://github.com/dianping/cat)                       | --   |
| 11   | Maze         | Maze                 | 规则引擎                 | /                                 | 外卖CRM   | 2017 | /                                                            | -    |
| 12   | Kerberos     | Kerberos             | 认证服务                 | /                                 | 基础服务  | 2017 | /                                                            | +    |
| 13   | Rhino        | Meituan Rhino        | 熔断组件                 | /                                 | 基础服务  | 2017 | /                                                            | -    |
| 14   | ProGuard     | ProGuard             | Java代码优化器           | Java、Kotlin                      | /         | 2018 | [官网](https://www.guardsquare.com)                          | +    |
| 15   | Netty        | Netty                | 网络通信层框架           | Java                              | 基础服务  | 2018 | [官网](https://netty.io/)                                    | ++   |
| 16   | Oceanus      | Oceanus              | HTTP服务治理框架         | Nginx、Lua                        | 基础服务  | 2018 | /                                                            | +    |
| 17   | UAS          | User Action System   | 用户行为系统             | /                                 | 基础服务  | 2018 | /                                                            | +    |
| 18   | Camus        | Camus                | kafka2hive数据工具       | Kafka、Hive                       | 基础服务  | 2018 | [Git](https://github.com/LinkedInAttic/camus)                | --   |
| 19   | Canal        | Canal                | 增量订阅和消费组件       | MySQL                             | 物流      | 2018 | [Git](https://github.com/alibaba/canal)                      | +    |
| 20   | Databus      | Meituan Databus      | 数据库变更实时传输系统   | /                                 | 物流      | 2018 | [Git](https://github.com/linkedin/databus)                   | -    |
| 21   | DataMan      | Meituan DataMan      | 数据质量监管平台         | /                                 | 美旅      | 2018 | /                                                            | -    |
| 22   | Quake        | Meituan Quake        | 全链路压测平台           | Mtrace、MySQL                     | /         | 2018 | /                                                            | -    |
| 23   | Gravity      | Meituan Gravity      | 流程管理组件             | activiti                          | 绩效系统  | 2018 | /                                                            | -    |
| 24   | Aviator      | Aviator              | 规则表达式引擎           | Java                              | 美旅      | 2018 | [Git](https://github.com/killme2008/aviator)                 | +    |
| 25   | BTrace       | BTrace               | 动态追踪服务工具         | Java                              | 打车      | 2019 | [Git](https://github.com/btraceio/btrace)                    | +    |
| 26   | OCTO         | Octopus              | 微服务通信框架及治理平台 | Java、Zookeeper                   | 基础服务  | 2019 | [Git](https://github.com/Meituan-Dianping/octo-rpc)、[Git](https://github.com/Meituan-Dianping/octo-ns)、[Git](https://github.com/Meituan-Dianping/octo-portal) | +    |
| 27   | Wedge        | Wedge                | 参数配置平台             | /                                 | 搜索广告  | 2019 | /                                                            | -    |
| 28   | Gulf         | Meituan Gulf         | 日期管理系统             | /                                 | 基础服务  | /    | /                                                            | -    |
| 29   | QA-Assistant | QA-Assistant         | 质量检查                 | /                                 | /         | /    | /                                                            | -    |
| 30   | MNS          | Meituan Name Service | 命名服务                 | OCTO、Zookeeper、Mesh             | 基础服务  | 2020 | /                                                            | +    |
| 31   | Crane        | Crane                | 分布式定时任务系统       | /                                 | /         | /    | /                                                            | +    |
| 32   | Service Mesh | Serive Mesh          | 服务网格微服务框架       | /                                 | 中间件    | 2020 | /                                                            | ++   |

## :frog:3.数据库

| 序号 | 名称       | 全称                              | 简介                    | 技术栈   | 应用     | 时间  | 网址                                                  | 发展 |
| ---- | ---------- | --------------------------------- | ----------------------- | -------- | -------- | ----- | ----------------------------------------------------- | ---- |
| 1    | OpenTSDB   | The Scalable Time Series Database | 时间序列数据库          | HBase    | 监控平台 | 2014  | [官网](http://opentsdb.net/)                          | +    |
| 2    | MySQL      | MySQL                             | 开源数据库              | /        | 基础服务 | 2010  | [官网](https://www.mysql.com/)                        | +++  |
| 3    | InfluxDB   | InfluxData                        | 时序数据库              | /        | 压测工具 | 2016  | [官网](www.influxdata.com/)                           | +    |
| 4    | Redis      | Redis                             | 键值对内存数据库        | ANSI C   | 基础服务 | 2013  | [官网](https://redis.io/)                             | ++   |
| 5    | DBProxy    | Meituan DBProxy                   | 数据库中间件            | C、Altas | 基础服务 | 2015+ | [Git](https://github.com/Meituan-Dianping/DBProxy)    | -    |
| 6    | SQLAdvisor | Meituan SQLAdvisor                | SQL优化工具             | C、MySQL | 运维     | 2017  | [Git](https://github.com/Meituan-Dianping/SQLAdvisor) | +    |
| 7    | Tair       | Tair                              | 键值对数据存储系统      | C        | 基础服务 | 2016  | [Git](https://github.com/alibaba/tair)                | +    |
| 8    | MyFlash    | Meituan MyFlash                   | MySQL 闪回工具          |          | 运维     | 2017  | [Git]( https://github.com/Meituan-Dianping/)          | +    |
| 9    | squirrel   | Meituan squirrel                  | 键值对内存数据库        | Redis    | 基础服务 | 2017  | /                                                     | -    |
| 10   | Zebra      | Zebra                             | 数据库访问层中间件      | /        | 物流     | 2016  | [Git](https://github.com/Meituan-Dianping/Zebra)      | -    |
| 11   | Alluxio    | Alluxio                           | 内存式存储系统          | Java     | 数据平台 | 2018  | [Git](https://github.com/Alluxio/alluxio)             | +    |
| 12   | Druid      | Apache Druid                      | 高性能实时分析数据库    | Java     | /        | 2018  | [Git](https://github.com/apache/druid/)               | +    |
| 13   | TiDB       | PingCAP TiDB                      | 在线事务/分析处理数据库 | Go       | 基础服务 | 2018  | [Git](https://github.com/pingcap/tidb)                | ++   |

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

| 序号 | 名称               | 全称                                                    | 简介                      | 技术栈      | 应用         | 时间 | 网址                                      | 发展 |
| ---- | ------------------ | ------------------------------------------------------- | ------------------------- | ----------- | ------------ | ---- | ----------------------------------------- | ---- |
| 1    | POI                | POI推荐                                                 | 机器学习的POI品类推荐算法 | Naive Bayes | 商家数据中心 | 2014 | /                                         | -    |
| 2    | AlexNet            | AlexNet                                                 | 卷积神经网络              | CNN         | 图像识别     | 2017 | /                                         | +    |
| 3    | GBDT               | Gradient Boosted Decision Trees                         | 梯度提升决策树            | /           | ETA配送      | 2017 | /                                         | +    |
| 4    | Core ML            | Core ML                                                 | 集成机器学习模型          | Python      | AR           | 2018 | /                                         | +    |
| 5    | ps-lite            | ps-lite                                                 | 模型的训练框架            | C++         | 猜你喜欢     | 2018 | [Git](https://github.com/dmlc/ps-lite)    | +    |
| 6    | Kaldi              | Kaldi                                                   | 语音识别系统              | C++         | /            | 2018 | [Git](https://github.com/kaldi-asr/kaldi) | ++   |
| 7    | Wide & Deep        | Wide & Deep                                             | 分类和回归模型            | TensorFlow  | 广告         | 2018 | /                                         | ++   |
| 8    | TensorFlow Serving | TensorFlow Serving                                      | 机器学习模型              | TensorFlow  | 广告         | 2018 | /                                         | ++   |
| 9    | Faster R-CNN       | Faster R-CNN                                            | 深度学习目标检测框架      | CNN         | OCR应用      | 2018 | /                                         | +    |
| 10   | XGBoost            | XGBoost                                                 | 机器学习平台              | /           | 配送         | 2019 | /                                         | +    |
| 11   | BERT               | Bidirectional Encoder Representations from Transformers | 深度双向语言表征模型      | Transformer | 搜索         | 2019 | /                                         | ++   |
| 12   | Jupyter            | Kaggle Kernels Jupyter                                  | 数据分析平台              | /           | 民宿         | 2019 | /                                         | +    |

## :monkey:6.运维

| 序号 | 名称       | 全称                                     | 简介                   | 技术栈            | 应用     | 时间 | 网址                            | 发展 |
| ---- | ---------- | ---------------------------------------- | ---------------------- | ----------------- | -------- | ---- | ------------------------------- | ---- |
| 1    | Docker     | Docker                                   | 开源的应用容器引擎     | Linux、GO、Glance | 基础服务 | 2015 | [官网](https://www.docker.com/) | +++  |
| 2    | Ursa       | Meituan Ursa                             | 分布式块存储系统       | /                 | 美团云   | 2016 | /                               | -    |
| 3    | Mt-Falcon  | Mt-Falcon                                | 监控系统               | Open-Falcon       | SRE      | 2017 | /                               | ++   |
| 4    | AWP        | /                                        | 静态化发布系统         | /                 | 酒旅     | 2017 | /                               | -    |
| 5    | OPS        | Operation and Maintenance Release System | 运维发布系统           | /                 | 酒旅     | 2017 | /                               | -    |
| 6    | Jenkins    | Jenkins                                  | 持续集成工具           | Java              | 基础服务 | 2017 | [官网](https://www.jenkins.io/) | +++  |
| 7    | HULK       | Meituan HULK                             | 容器管理及弹性伸缩平台 | /                 | 基础服务 | 2017 | /                               | -    |
| 8    | Kubernetes | Kubernetes                               | 资源管理和调度         | /                 | 基础服务 | 2018 | [官网](https://kubernetes.io/)  | +++  |

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
| 8    |          |                 |                         |          |          |      |                                             |      |

## :baby_chick:9.移动端

| 序号 | 名称          | 全称                          | 简介                   | 技术栈          | 应用       | 时间  | 网址                                                 | 发展 |
| ---- | ------------- | ----------------------------- | ---------------------- | --------------- | ---------- | ----- | ---------------------------------------------------- | ---- |
| 1    | Lint          | Lint/TSLint/ESLint            | 静态代码检查工具       | Java            | 酒旅       | 2016  | [官网](http://tools.android.com/tips)                | -    |
| 2    | Hertz         | Meituan Hertz                 | 移动端性能监控         | /               | 酒旅、外卖 | 2016  | /                                                    | -    |
| 3    | Walle         | Meituan Walle                 | 快速渠道包生产工具     | Java、Groovy    | 酒旅       | 2017  | [Git](https://github.com/Meituan-Dianping/walle)     | +    |
| 4    | Shield        | Shield                        | 模块化 UI 界面         | JS              | 到店       | 2017  | [Git](https://github.com/Meituan-Dianping/Shield)    | +    |
| 5    | Flutter       | Flutter                       | 跨平台UI框架           | JS              | 外卖       | 2018+ | [Git](https://github.com/flutter/flutter)            | +++  |
| 6    | Picasso       | Meituan Picasso               | 跨平台动态化框架       | DSL、TypeScript | 外卖、酒旅 | 2018  | /                                                    | -    |
| 7    | EasyReact     | Meituan EasyReact             | 客户端开发框架         | Objective-C     |            | 2018  | [Git](https://github.com/meituan-dianping/EasyReact) | -    |
| 8    | Logan         | Meituan Logan                 | 移动端基础日志组件     | C、JS           | 基础服务   | 2018  | [Git](https://github.com/Meituan-Dianping/Logan)     | +    |
| 9    | MCI           | Mobile continuous integration | 流程研发系统           | /               | 基础服务   | 2018  | /                                                    | -    |
| 10   | Robust        | Robust                        | 热修复框架             | /               | 外卖       | 2018  | [Git](https://github.com/Meituan-Dianping/Robust)    | -    |
| 11   | Holmes        | Meituan Holmes                | 动态日志系统           | Android         | /          | 2018  | /                                                    | -    |
| 12   | LiveDataBus   | LiveDataBus                   | 消息总线框架           | Android         | 收银       | 2018  | [Git](https://github.com/JeremyLiao/LiveDataBus)     | +    |
| 13   | modular-event | modular-event                 | 组件化消息总线框架     | Android         | 收银       | 2018  | /                                                    | -    |
| 14   | WMRouter      | WMRouter                      | Android路由框架        | Android         | 外卖       | 2018  | [Git](https://github.com/meituan/WMRouter)           | +    |
| 15   | Graver        | Meituan Graver                | UI 渲染框架            | iOS             | 外卖       | 2018  | [Git](https://github.com/Meituan-Dianping/Graver)    | -    |
| 16   | Hades         | Meituan Hades                 | 静态分析框架           | C、CouchDB      | 基础服务   | 2018  | /                                                    | -    |
| 17   | beeshell      | Meituan beeshell              | 基础组件库             | /               | 蜜蜂       | 2018  | [Git](https://github.com/meituan/beeshell)           | -    |
| 18   | OpenSTF       | OpenSTF                       | 云真机平台             | /               | 基础服务   | 2018  | /                                                    | +    |
| 19   | MTFlexbox     | Meituan Flexbox               | 跨平台动态化方案       | XML、CSS3       | 外卖       | 2019  | /                                                    | -    |
| 20   | Litho         | Litho                         | 声明式UI框架           | RecyclerView    | 终端       | 2019  | /                                                    | -    |
| 21   | MRN           | Meituan React Native          | 移动应用开发框架       | React Native    | 终端       | 2019  | /                                                    | +    |
| 22   | Probe         | Probe                         | Android线上OOM定位组件 | /               | 配送       | 2019  | /                                                    | -    |
| 23   | Sketch        | Meituan Sketch                | 积木UI统一解决方案     | /               | 前端       | 2020  | /                                                    | +    |

