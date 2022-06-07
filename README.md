# 大数据中最关键的技术
### 1.大数据采集技术
##### 1.数据库采集
##### 2.系统日志收集
1. Flume日志采集的基本概念<br>
   a. Flume 的核心是把数据从数据源（Source）收集过来，再将收集到的数据送到指定的目的地（Smk），为了保证输送的过程一定成功，在送到目的地之前，会先缓存数据到管道（Channel）,待数据真正到达目的地后，Flume 再删除缓存的数据.<br>
2. Flume使用方法<br>
   a. Flume的用法简单，主要是编写一个用户配置文件。在配置文件中描述source,channel和sink的具体实现，而后运行一个agent实例。
   b. 指定source,sink和channel，同时使用channel将source和sink连接起来。
##### 3.网络数据采集
1. 网络爬虫原理<br>
   a. 选取一部分种子URL放入队列，抓取这部分网页，同时提取其中的URL放入队列中，如此一直下去.<br>
   b. 通过必要的算法控制能够更全面的抓取互联网上的所有网页。这里有现成的Scrapy架构<br>
##### 4.感知设备数据
### 2.大数据预处理技术
##### 1.数据清理(数据分析和人工智能)
##### 2.数据集成
### 3.大数据存储及管理技术
##### 1.使用hadoop存储结构化和非结构化数据
### 4.大数据处理
##### 1.使批处理模式(一般大数据处理技术)
##### 2.流处理模式(实时大数据处理技术)
### 5.大数据处理(数据分析)
##### 1.分类
##### 2.线性回归
##### 3.聚类
##### 4.关联规则
### 6.大数据展示技术(数据可视化)
