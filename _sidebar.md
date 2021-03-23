  - [1 INTRODUCTION](/INTRODUCTION.md)
  - [2 NewSQL](/NewSQL/README.md)
    - [2.1 Aurora](/NewSQL/Aurora/README.md)
      
    - [2.2 F1](/NewSQL/F1/README.md)
      
    - [2.3 TiDB](/NewSQL/TiDB/README.md)
      - [2.3.1 TiFlash](/NewSQL/TiDB/TiFlash/README.md)
        
      - 2.3.2 TiKV
        - [2.3.2.1 副本与分片](/NewSQL/TiDB/TiKV/副本与分片.md)
        - [2.3.2.2 存储](/NewSQL/TiDB/TiKV/存储/README.md)
          - [2.3.2.2.1 Raft 优化](/NewSQL/TiDB/TiKV/存储/Raft%20优化.md)
          - [2.3.2.2.2 存储架构](/NewSQL/TiDB/TiKV/存储/存储架构.md)
  - [3 关系型数据库](/关系型数据库/README.md)
    - [3.1 MySQL](/关系型数据库/MySQL/README.md)
      
    - [3.2 PostgreSQL](/关系型数据库/PostgreSQL/README.md)
      - [3.2.1 数据类型](/关系型数据库/PostgreSQL/数据类型/README.md)
        - [3.2.1.1 时间与日期](/关系型数据库/PostgreSQL/数据类型/时间与日期.md)
      - [3.2.2 架构机制](/关系型数据库/PostgreSQL/架构机制/README.md)
        - [3.2.2.1 并发控制](/关系型数据库/PostgreSQL/架构机制/并发控制.md)
        - [3.2.2.2 持久化与缓冲区管理](/关系型数据库/PostgreSQL/架构机制/持久化与缓冲区管理.md)
        - [3.2.2.3 数据库架构](/关系型数据库/PostgreSQL/架构机制/数据库架构.md)
        - [3.2.2.4 日志备份与恢复](/关系型数据库/PostgreSQL/架构机制/日志备份与恢复.md)
        - [3.2.2.5 查询处理](/关系型数据库/PostgreSQL/架构机制/查询处理.md)
      - [3.2.3 管理与配置](/关系型数据库/PostgreSQL/管理与配置/README.md)
        - [3.2.3.1 数据库管理](/关系型数据库/PostgreSQL/管理与配置/数据库管理.md)
        - [3.2.3.2 部署与配置](/关系型数据库/PostgreSQL/管理与配置/部署与配置.md)
    - [3.3 RocksDB](/关系型数据库/RocksDB/README.md)
      
    - [3.4 SQLServer](/关系型数据库/SQLServer/README.md)
      
  - [4 图数据库](/图数据库/README.md)
    - [4.1 Neo4j](/图数据库/Neo4j/README.md)
      
    - [4.2 查询语言](/图数据库/查询语言/README.md)
      
    - 4.3 系统设计
      - [4.3.1 图数据库案例](/图数据库/系统设计/图数据库案例.md)
  - 5 搜索引擎
    - [5.1 ElasticSearch](/搜索引擎/ElasticSearch/README.md)
      - 5.1.1 SDK 使用
        - [5.1.1.1 Java](/搜索引擎/ElasticSearch/SDK%20使用/Java.md)
      - 5.1.2 数据操作
        - [5.1.2.1 数据检索](/搜索引擎/ElasticSearch/数据操作/数据检索.md)
        - [5.1.2.2 索引操作](/搜索引擎/ElasticSearch/数据操作/索引操作.md)
      - [5.1.3 架构原理](/搜索引擎/ElasticSearch/架构原理/README.md)
        
      - [5.1.4 集群与高可用](/搜索引擎/ElasticSearch/集群与高可用/README.md)
        
    - [5.2 MeiliSearch](/搜索引擎/MeiliSearch/README.md)
      
  - [6 数据库理论](/数据库理论/README.md)
    - [6.1 事务](/数据库理论/事务/README.md)
      - [6.1.1 ACID](/数据库理论/事务/ACID.md)
      - [6.1.2 可序列化](/数据库理论/事务/可序列化.md)
      - [6.1.3 快照隔离和可重复读](/数据库理论/事务/快照隔离和可重复读.md)
      - [6.1.4 读已提交](/数据库理论/事务/读已提交.md)
      - [6.1.5 防止丢失更新](/数据库理论/事务/防止丢失更新.md)
      - [6.1.6 隔离级别](/数据库理论/事务/隔离级别.md)
    - [6.2 大数据](/数据库理论/大数据/README.md)
      - [6.2.1 不作恶](/数据库理论/大数据/不作恶.md)
      - [6.2.2 大数据平台](/数据库理论/大数据/大数据平台.md)
      - [6.2.3 大数据生态圈](/数据库理论/大数据/大数据生态圈.md)
      - [6.2.4 大数据的未来](/数据库理论/大数据/大数据的未来.md)
      - [6.2.5 数据的特性](/数据库理论/大数据/数据的特性.md)
    - [6.3 存储引擎](/数据库理论/存储引擎/README.md)
      - [6.3.1 B+ 树](/数据库理论/存储引擎/B+%20树.md)
      - [6.3.2 LSM 树](/数据库理论/存储引擎/LSM%20树.md)
      - 6.3.3 全文索引
        - [6.3.3.1 全文索引](/数据库理论/存储引擎/全文索引/全文索引.md)
        - [6.3.3.2 动态全文索引](/数据库理论/存储引擎/全文索引/动态全文索引.md)
      - [6.3.4 其他索引](/数据库理论/存储引擎/其他索引.md)
      - [6.3.5 哈希索引](/数据库理论/存储引擎/哈希索引.md)
      - [6.3.6 无索引](/数据库理论/存储引擎/无索引.md)
      - [6.3.7 编码](/数据库理论/存储引擎/编码.md)
    - [6.4 数据仓库](/数据库理论/数据仓库/README.md)
      - [6.4.1 列存储](/数据库理论/数据仓库/列存储/README.md)
        - [6.4.1.1 写入与更新](/数据库理论/数据仓库/列存储/写入与更新.md)
      - [6.4.2 多维数据模型](/数据库理论/数据仓库/多维数据模型/README.md)
        - [6.4.2.1 Data Cube](/数据库理论/数据仓库/多维数据模型/Data%20Cube.md)
        - [6.4.2.2 元数据](/数据库理论/数据仓库/多维数据模型/元数据.md)
        - [6.4.2.3 星型与雪花模型](/数据库理论/数据仓库/多维数据模型/星型与雪花模型.md)
      - 6.4.3 数据流
        - [6.4.3.1 混合存储](/数据库理论/数据仓库/数据流/混合存储.md)
      - [6.4.4 记录与衍生](/数据库理论/数据仓库/记录与衍生/README.md)
        - [6.4.4.1 变更数据捕获](/数据库理论/数据仓库/记录与衍生/变更数据捕获.md)
        - [6.4.4.2 物化视图](/数据库理论/数据仓库/记录与衍生/物化视图.md)
        - [6.4.4.3 观察衍生数据状态](/数据库理论/数据仓库/记录与衍生/观察衍生数据状态.md)
        - [6.4.4.4 避免错误](/数据库理论/数据仓库/记录与衍生/避免错误.md)
    - [6.5 数据库简史](/数据库理论/数据库简史/README.md)
      - [6.5.1 DBMS](/数据库理论/数据库简史/DBMS.md)
      - [6.5.2 NoSQL](/数据库理论/数据库简史/NoSQL.md)
      - [6.5.3 性能评测](/数据库理论/数据库简史/性能评测.md)
    - [6.6 数据模型](/数据库理论/数据模型/README.md)
      - [6.6.1 关系模型](/数据库理论/数据模型/关系模型.md)
      - [6.6.2 图模型](/数据库理论/数据模型/图模型.md)
      - [6.6.3 文档模型](/数据库理论/数据模型/文档模型.md)
      - [6.6.4 时序模型](/数据库理论/数据模型/时序模型.md)
      - [6.6.5 查询语言](/数据库理论/数据模型/查询语言.md)
  - 7 文档型数据库
    - [7.1 Mongodb](/文档型数据库/Mongodb/README.md)
      
  - [8 时序数据库](/时序数据库/README.md)
    - [8.1 AliyunTSDB](/时序数据库/AliyunTSDB/README.md)
      
    - [8.2 InfluxDB](/时序数据库/InfluxDB/README.md)
      - [8.2.1 存储引擎](/时序数据库/InfluxDB/存储引擎.md)
      - [8.2.2 数据模型](/时序数据库/InfluxDB/数据模型.md)
      - [8.2.3 部署配置](/时序数据库/InfluxDB/部署配置.md)
    - [8.3 OpenTSDB](/时序数据库/OpenTSDB/README.md)
      - [8.3.1 系统设计](/时序数据库/OpenTSDB/系统设计.md)
    - [8.4 Prometheus](/时序数据库/Prometheus/README.md)
      - [8.4.1 Alert](/时序数据库/Prometheus/Alert/README.md)
        - [8.4.1.1 Alerting Rules](/时序数据库/Prometheus/Alert/Alerting%20Rules.md)
        - [8.4.1.2 Alertmanager](/时序数据库/Prometheus/Alert/Alertmanager.md)
      - [8.4.2 Exporter](/时序数据库/Prometheus/Exporter/README.md)
        
      - 8.4.3 PTSDB
        - [8.4.3.1 REAMDE](/时序数据库/Prometheus/PTSDB/REAMDE.md)
        - [8.4.3.2 存储](/时序数据库/Prometheus/PTSDB/存储.md)
        - [8.4.3.3 文件格式](/时序数据库/Prometheus/PTSDB/文件格式.md)
      - [8.4.4 PromQL](/时序数据库/Prometheus/PromQL/README.md)
        - [8.4.4.1 HTTP API](/时序数据库/Prometheus/PromQL/HTTP%20API.md)
        - [8.4.4.2 Recording Rules](/时序数据库/Prometheus/PromQL/Recording%20Rules.md)
        - [8.4.4.3 内置函数](/时序数据库/Prometheus/PromQL/内置函数.md)
        - [8.4.4.4 操作符](/时序数据库/Prometheus/PromQL/操作符.md)
        - [8.4.4.5 数据查询](/时序数据库/Prometheus/PromQL/数据查询.md)
        - [8.4.4.6 数据模型](/时序数据库/Prometheus/PromQL/数据模型.md)
        - [8.4.4.7 聚合操作](/时序数据库/Prometheus/PromQL/聚合操作.md)
      - 8.4.5 SDK
        - [8.4.5.1 Go](/时序数据库/Prometheus/SDK/Go.md)
        - [8.4.5.2 Java](/时序数据库/Prometheus/SDK/Java.md)
      - [8.4.6 快速开始](/时序数据库/Prometheus/快速开始/README.md)
        - [8.4.6.1 单机部署](/时序数据库/Prometheus/快速开始/单机部署.md)
        - [8.4.6.2 参数配置](/时序数据库/Prometheus/快速开始/参数配置.md)
        - [8.4.6.3 应用监控](/时序数据库/Prometheus/快速开始/应用监控.md)
        - [8.4.6.4 集群部署](/时序数据库/Prometheus/快速开始/集群部署.md)
    - [8.5 TimescaleDB](/时序数据库/TimescaleDB/README.md)
      - [8.5.1 系统设计](/时序数据库/TimescaleDB/系统设计.md)
    - [8.6 时序对比](/时序数据库/时序对比.md)
    - [8.7 系统设计](/时序数据库/系统设计.md)
  - 9 键值型数据库
    - [9.1 BoltDB](/键值型数据库/BoltDB/README.md)
      
    - [9.2 LevelDB](/键值型数据库/LevelDB/README.md)
      - [9.2.1 架构机制](/键值型数据库/LevelDB/架构机制.md)
      - [9.2.2 部署配置](/键值型数据库/LevelDB/部署配置.md)
    - [9.3 Redis](/键值型数据库/Redis/README.md)
      - [9.3.1 KeyDB](/键值型数据库/Redis/KeyDB/README.md)
        - [9.3.1.1 架构机制](/键值型数据库/Redis/KeyDB/架构机制.md)
      - 9.3.2 工程实践
        - [9.3.2.1 性能优化](/键值型数据库/Redis/工程实践/性能优化.md)
        - [9.3.2.2 持久化](/键值型数据库/Redis/工程实践/持久化.md)
        - [9.3.2.3 自定义脚本](/键值型数据库/Redis/工程实践/自定义脚本.md)
        - [9.3.2.4 部署与配置](/键值型数据库/Redis/工程实践/部署与配置.md)
      - [9.3.3 数据操作](/键值型数据库/Redis/数据操作/README.md)
        - [9.3.3.1 事务与管道](/键值型数据库/Redis/数据操作/事务与管道.md)
        - [9.3.3.2 其他类型](/键值型数据库/Redis/数据操作/其他类型.md)
        - [9.3.3.3 基础类型](/键值型数据库/Redis/数据操作/基础类型.md)
        - [9.3.3.4 数据类型实现](/键值型数据库/Redis/数据操作/数据类型实现.md)
        - [9.3.3.5 键基础](/键值型数据库/Redis/数据操作/键基础.md)
        - [9.3.3.6 集合类型](/键值型数据库/Redis/数据操作/集合类型.md)
      - [9.3.4 架构机制](/键值型数据库/Redis/架构机制/README.md)
        - [9.3.4.1 单线程架构](/键值型数据库/Redis/架构机制/单线程架构.md)
        - [9.3.4.2 命令执行](/键值型数据库/Redis/架构机制/命令执行.md)
        - [9.3.4.3 多进程架构](/键值型数据库/Redis/架构机制/多进程架构.md)
        - [9.3.4.4 客户端通信](/键值型数据库/Redis/架构机制/客户端通信.md)
        - [9.3.4.5 深入事件循环](/键值型数据库/Redis/架构机制/深入事件循环.md)
      - [9.3.5 集群](/键值型数据库/Redis/集群/README.md)
        - [9.3.5.1 Codis](/键值型数据库/Redis/集群/Codis.md)
        - [9.3.5.2 Redis Cluster](/键值型数据库/Redis/集群/Redis%20Cluster.md)
        - [9.3.5.3 Redis 分片](/键值型数据库/Redis/集群/Redis%20分片.md)
        - [9.3.5.4 Sentinel](/键值型数据库/Redis/集群/Sentinel.md)
    - 9.4 RocksDB
      - [9.4.1 READNE](/键值型数据库/RocksDB/READNE.md)