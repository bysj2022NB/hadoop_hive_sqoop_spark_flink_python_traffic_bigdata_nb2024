# 计算机毕业设计吊炸天遥遥领先Hadoop+Spark+Hive+Flink交通大数据 地铁客流量分析大数据 数据仓库 大数据毕业设计 大数据毕设

## 要求
### 源码有偿一套(论文 PPT 源码+sql脚本+虚拟机)
### 
### 加好友前帮忙start一下，并备注github有偿获取源码
### 我的QQ号是2877135669 

### 或者 微信 bysj2023nb

### 加qq好友说明（被部分  网友整得心力交瘁）：
    1.加好友务必按照格式备注git虚拟机电影推荐
    2.避免浪费各自的时间



# 背景

该项目主要分析深圳通刷卡数据，通过大数据技术来研究深圳地铁客运能力及探索优化服务的方向 

主要讲解Flink流处理实时分析部分，离线部分较简单，暂时略过 



# 流程

采用python请求深圳地铁数据API，将数据发送至Kafka和MySQL。 

kafka部分用于实时计算，MySQL部分模仿业务数据，用于离线分析 

Flink连接Kafka进行实时统计各站收入情况 

将统计的结果Sink到Mysql进行可视化展示 

离线部分用sqoop将业务数据导入到hive中进行分析，最终将分析完的数据导出到MySQL用于可视化展示 

整体使用azkaban进行调度 







## 开发技术
python 3.6.6 

java  1.8 

scala 2.11 

kafka_2.11-2.4.1 

zookeeper_3.4.6 

flink 1.14.0 

hadoop 2.7.6 

sqoop 1.4.6 

hive 1.2.1 

azkaban 2.5.0 

mysql 5.7 

FineReport 11 

## 创新点

实时计算、离线计算、大屏、爬虫、虚拟机



## 补充说明
适合大数据毕业设计、数据分析、爬虫类计算机毕业设计









# 运行截图

![](1.png)

![2](2.png)

![3](3.png)

![4](4.png)

![5](5.png)

![6](6.png)







# 演示视频

https://www.bilibili.com/video/BV1J14y1H7Ug/?spm_id_from=333.999.0.0

或者去我B站搜交通大数据

https://space.bilibili.com/474562629