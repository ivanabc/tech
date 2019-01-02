# 2018 - 精选技术文章

## 1. 游戏
* [游戏服务端架构发展史](http://www.skywind.me/blog/archives/1265)
* [《王者荣耀》后台技术架构](https://mp.weixin.qq.com/s/4FT8cKAuz2zAEvLJnqMx4w)
* [天涯明月刀后台技术创新](https://mp.weixin.qq.com/s/8eFHvQj2d2aEJn5oHjz0mw)
* [谈谈腾讯的技术价值观与技术人才修炼](https://mp.weixin.qq.com/s/Vn0eKvY5AU1DEOrxbOxABQ)
* [由全民吃鸡引发的网游加速学习总结](https://mp.weixin.qq.com/s/Zaqj421ASh0kWGnR2ksHJA)
    * 游戏延时级别
    * 丢包率：千兆网卡在流量大于200Mbps时,丢包率小于万分之五;百兆网卡在流量大于60Mbps时,丢包率小于万分之一
* [“端改手”怎么做？《穿越火线：枪战王者》客户端技术方案详解](https://zhuanlan.zhihu.com/p/49791254)


#### 帧同步
* [《王者荣耀》技术总监：我们为什么要在技术架构与网络同步方案上做出这些改变？](https://mp.weixin.qq.com/s/ab1nBX0RbP-s-52__NjMWQ)
* [帧锁定同步算法](http://www.skywind.me/blog/archives/131)
* [从王者荣耀聊聊游戏的帧同步](http://gad.qq.com/article/detail/32563)
* [Gaffer On Games --- BLOG](https://gafferongames.com/)
* [《守望先锋》架构设计与网络同步](http://gad.qq.com/article/detail/28682)
* [《守望先锋》回放技术-阵亡镜头、全场最佳和亮眼表现](http://gad.qq.com/article/detail/29595)
* [《守望先锋》中的网络脚本化的武器和技能系统](http://gad.qq.com/article/detail/28219)
* [帧同步联机战斗（预测，快照，回滚）](https://zhuanlan.zhihu.com/p/38468615)
* [lockstep 网络游戏同步方案](https://blog.codingnow.com/2018/08/lockstep.html)

#### NavMesh
* [Unreal Engine 3导航网格寻路算法概述](http://gad.qq.com/article/detail/10042)
* [Navigation Mesh与Line-of-Sight Test](http://www.cnblogs.com/neoragex2002/archive/2007/09/09/887556.html)
* [基于导航网格的A星寻路(Navigation mesh)](http://www.cnblogs.com/tuzhiye/archive/2010/09/26/1835899.html)

#### ECS
* [游戏开发中的ECS 架构概述](https://zhuanlan.zhihu.com/p/30538626)
* [浅谈《守望先锋》中的 ECS 构架](https://blog.codingnow.com/2017/06/overwatch_ecs.html)

---
## 2. 网络
* [深入了解 gRPC：协议](https://mp.weixin.qq.com/s/wk1GpvjP821_FPQq3e6Ymw)
* [定位服务器数据丢弃包问题](https://mp.weixin.qq.com/s/R7ruf7r6a0CuopN14FTBBg)
* [SYN丢包的几个例子](https://huoding.com/2017/10/31/643)
* [压力测试竟然会导致sendmsg()报非法参数错误](https://mp.weixin.qq.com/s?__biz=MzAxOTk3OTgxOQ==&mid=2247483682&idx=1&sn=2ca07cf456f237b023ccd58719d5b6b8)
* [怎么让不可靠的UDP可靠？](http://www.infoq.com/cn/articles/how-to-make-udp-reliable)
* [HTTPS 的故事](https://qianduan.group/posts/5a6560b00cf6b624d2239c6f)
* [Redis高负载下的中断优化](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651747704&idx=3&sn=cd76ad912729a125fd56710cb42792ba&from=1083293010&wm=3333_2001&weiboauthoruid=1840408525)
* [闲话高并发的那些神话，看京东架构师如何把它拉下神坛](https://mp.weixin.qq.com/s/FLpdT9wZFT0sJBmNTCIObw)
    * 并行计算工业化应用的模型主要有两种，一种是共享内存模型，另外一种是消息传递模型。
    * 消息传递模型有两个重要的分支，一个是Actor模型，一个是CSP模型。
    * CSP模型和Actor模型的一个感官上的区别是在CSP模型里面，生产者（消息发送方）和消费者（消息接收方）是完全松耦合的，生产者完全不知道消费者的存在，但是在Actor模型里面，生产者必须知道消费者，否则没办法发送消息。
* [getaddrinfo引发的血案](http://www.hulkdev.com/posts/getaddrinfo_cause_unbalance)
* [关于NTP，你需要知道的一切](https://www.jianshu.com/p/8096c0477230)
* [白话TCP拥塞控制：运粮的河道堵塞了怎么办？](https://mp.weixin.qq.com/s/j0WeTRgJMohIYr-SraMyBw)
* [给Linux系统/网络管理员准备的Nmap命令的29个实用范例](http://blog.jobbole.com/54595/)
* [How to achieve low latency with 10Gbps Ethernet](https://blog.cloudflare.com/how-to-achieve-low-latency/)
* [Python 中的 Socket 编程（指南）](https://segmentfault.com/a/1190000016501735)
* [阿里云安全组之静默丢包](https://zhuanlan.zhihu.com/p/52622856)

#### UDP
* [KCP](https://github.com/skywind3000/kcp)
* [可靠UDP，KCP协议快在哪？](https://wetest.qq.com/lab/view/391.html)
* [KCP: 快速可靠的ARQ协议](http://kaiyuan.me/2017/07/29/KCP%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/)
* [KCP WIKI](https://github.com/skywind3000/kcp/wiki)
* [KCP 游戏项目使用异常](https://github.com/skywind3000/kcp/issues/100)
* [kcptun](https://github.com/xtaci/kcptun)
    * fec Reed-Solomon 
* [UDPspeeder](https://github.com/wangyu-/UDPspeeder)
---
## 3. 数据库
* [淘宝 - 数据库内核月报](http://mysql.taobao.org/monthly/)
* [我必须得告诉大家的MySQL优化原理](http://www.jianshu.com/p/d7665192aaaf)
* [浅入浅出MySQL 和 InnoDB](http://draveness.me/mysql-innodb.html)
* [阿里云新一代关系型数据库 PolarDB 剖析](http://www.infoq.com/cn/news/2017/08/ali-polardb)
* [浅析 Bigtable 和 LevelDB 的实现](http://draveness.me/bigtable-leveldb.html)
* [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)
* [mysql - percona monitoring and management](https://www.percona.com/software/database-tools/percona-monitoring-and-management)
* [当Facebook创造的cassandra遇上饿了么](https://mp.weixin.qq.com/s/fDQc6QrnX2IcaVOZ0Lb82w)
* [HBaseFsck（hbck）是用于检查region一致性和表完整性问题，修复失效HBase的一个工具](http://lsr1991.github.io/2015/05/10/hbck-document-translation/)
* [OceanBase1.0 分布式技术架构](https://mp.weixin.qq.com/s/9nEW5aLVLFvpot95OkPBDw)
    * 存储引擎
        1. B+ tree
        2. LSM tree
    * **关系数据库写入放大问题**：用户数据是按行写入的，但是关系数据库却是按页面管理的，有时只写了一行数据，却不得不把整个页面刷入磁盘。
    * OceanBase本质上是一个`基线加增量`的存储引擎
* [SSTable and Log Structured Storage: LevelDB](https://www.igvita.com/2012/02/06/sstable-and-log-structured-storage-leveldb/)
* [换个角度看Aurora：缘何“万能”？对比TiDB有何不同？](https://mp.weixin.qq.com/s/iOqRC2M8e5E5-89At-w2Lw)
    * 事务处理引擎
        * 查询处理引擎
        * 存储引擎
* [阿里巴巴分布式缓存服务Tair的热点数据散列机制](https://mp.weixin.qq.com/s/93wAyqIbwwSo5G803LGcag)
    * 热点读 - 多级缓存
    * 热点写 - 合并写入
* [OceanBase vs. Aurora](https://mp.weixin.qq.com/s/-kfX5WZm3DuuFlQqQvo0gQ)
* [boltDB](https://mp.weixin.qq.com/s/5y7q2DU9_ZWsZ7jzpkqiKQ)
* [MMKV--基于 mmap 的 iOS 高性能通用 key-value 组件](https://mp.weixin.qq.com/s/cZQ3FQxRJBx4px1woBaasg)
    * protobuf kv
    * append kv,从后往前读数据，越后越新
    * 数据整理与扩容
    * crc32
* [MySQL数据库SYS CPU高的可能性分析](http://mysql.taobao.org/monthly/2015/05/02/)
* [疯狂的Anna：快、可扩展、支持多种一致性模型的KVS](https://mp.weixin.qq.com/s/pxEgijJzBlqR_gDhytGdqQ)
    * 异步消息通知架构
        * 一个线程绑定一个CPU核，避免线程切换、L1 cache miss
        * 每个CPU线程运行一个event loop从输入队列中响应用户及其它CPU线程发来的请求
        * 每个线程访问自己的私有内存结构，避免内核/用户态锁切换、CPU缓存一致性开销
        * 线程与线程之间通过消息队列异步非阻塞通信，避免同步阻塞开销
    * Amazon Dynamo的反熵是一种基于状态的异步副本同步协议，它会定期在副本结点间传递副本的Merkle树，如果发现有副本不一致，则通过向量时钟机制在系统层面自动进行数据版本合并；如果版本冲突不能合并，需要交给应用层来解决。应用层与系统层在冲突解决逻辑上紧密耦合，降低了系统的鲁棒性，也容易导致应用层代码逻辑错误。
    * Anna采用基于操作的异步副本同步协议，定期广播一段时间内的副本更新日志到相关副本结点，借鉴Bloom语言实现Lattice属性数据类型的思想，以系统化、模块化的编码方式实现actor私有的一致性状态数据结构，通过其合并函数（支持用户自定义）完成数据版本的合并及冲突解决。
* [MySQL索引背后的数据结构及算法原理](https://www.kancloud.cn/kancloud/theory-of-mysql-index/41849)
* [开源NewSQL – CockroachDB在百度内部的应用与实践](https://mp.weixin.qq.com/s/eIaKxarBsmfwKrQow2ozUw)
* [一文带你了解LSM Compaction](https://mp.weixin.qq.com/s/KoAMXsfCgt6jTaZNxtZI7w)
    * 读放大
    * 写放大
    * 空间放大
* [Redis 5.0](https://mp.weixin.qq.com/s/6oSfF1rvcfpdsRMf5UCmGA)
* [MySQL8与PG10：新版本下的较量谁更胜一筹？](https://mp.weixin.qq.com/s/noz2NYogspS1rt5xDyjVJw)
* [Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/)
* [青铜到王者，看看你的MySQL数据库是什么段位，如何提升？](https://mp.weixin.qq.com/s/uS1OLI03MuOBUZQuh8IQNw)
* [性能优化：MySQL 性能提升之降龙十八掌](https://mp.weixin.qq.com/s/R_mDllYSCW36cQK2ud3y0g)
* [WiscKey: Separating Keys from Values
in SSD-conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf)
* [现代存储系统背后的算法](http://www.infoq.com/cn/articles/algorithms-behind-modern-storage-systems)
* [永远不要在 MySQL 中使用「utf8」](https://mp.weixin.qq.com/s/Z3uG3r2Yb-Wq_KL3VQ90rQ)
* [一步完成 MySQL 向 Redis 迁移](https://www.oschina.net/translate/mysql-to-redis-in-one-step)
* [MySQL · 物理备份 · Percona XtraBackup 备份原理](http://mysql.taobao.org/monthly/2016/03/07/)
* [数据库内核月报](http://mysql.taobao.org/monthly/)
* [WiscKey：LSM-Tree 写放大优化](https://www.jianshu.com/p/1b438f850844)
* [GitHub 的 MySQL 高可用性实践分享](https://mp.weixin.qq.com/s/vjnLX9iaIPk42Q_RKBzlYA)
* [记录一次数据同步到数据仓库的架构与实践](https://mp.weixin.qq.com/s/tWTmRYdY1mEO972y5Qb8QQ)

---
## 4. 数据结构 & 算法
* [Data Structure and Algorithms](http://www.golangprograms.com/data-structure-and-algorithms.html)
* [A Fast General Purpose Lock-Free Queue for C++](http://moodycamel.com/blog/2014/a-fast-general-purpose-lock-free-queue-for-c++)
* [consistent hashing](https://github.com/RJ/ketama)
    1. Take your list of servers (eg: 1.2.3.4:11211, 5.6.7.8:11211, 9.8.7.6:11211)
    2. Hash each server string to several (100-200) unsigned ints
    3. Conceptually, these numbers are placed on a circle called the continuum. (imagine a clock face that goes from 0 to 2^32)
    4. Each number links to the server it was hashed from, so servers appear at several points on the continuum, by each of the numbers they hashed to.
    5. To map a key->server, hash your key to a single unsigned int, and find the next biggest number on the continuum. The server linked to that number is the correct server for that key.
    6. If you hash your key to a value near 2^32 and there are no points on the continuum greater than your hash, return the first server in the continuum.
* [一种高性能B+树实现](https://mp.weixin.qq.com/s/ABVxksLe5we1I9P_3zSYqA)
* [一致性哈希算法的理解与实践](https://yikun.github.io/2016/06/09/%E4%B8%80%E8%87%B4%E6%80%A7%E5%93%88%E5%B8%8C%E7%AE%97%E6%B3%95%E7%9A%84%E7%90%86%E8%A7%A3%E4%B8%8E%E5%AE%9E%E8%B7%B5/)
* [visualising data structures and algorithms through animation](https://visualgo.net/en)
* [排序算法稳定性](https://baike.baidu.com/item/%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95%E7%A8%B3%E5%AE%9A%E6%80%A7)
    * 假定在待排序的记录序列中，存在多个具有相同的关键字的记录，若经过排序，这些记录的相对次序保持不变，即在原序列中，ri=rj，且ri在rj之前，而在排序后的序列中，ri仍在rj之前，则称这种排序算法是稳定的；否则称为不稳定的。
* [Different uses for read-optimized B-trees and write-optimized LSM-trees](https://queue.acm.org/detail.cfm?id=3220266)
* [从B树、B+树、B*树谈到R 树](https://blog.csdn.net/v_july_v/article/details/6530142)

---
## 5. 分布式系统
* [Distributed systems for fun and profit](http://book.mixu.net/distsys/single-page.html)
* [分布式系统(Distributed System)资料](https://github.com/ty4z2008/Qix/blob/master/ds.md)
* [分布式系统](http://www.cnblogs.com/bangerlee/category/668967.html)
* [WHAT WE TALK ABOUT WHEN WE TALK ABOUT DISTRIBUTED SYSTEMS](http://alvaro-videla.com/2015/12/learning-about-distributed-systems.html)
* [A Brief Tour of FLP Impossibility](http://the-paper-trail.org/blog/a-brief-tour-of-flp-impossibility/)
* [小米开源分布式KV存储系统Pegasus](https://mp.weixin.qq.com/s/_jHWHWkIqkcDQDYvdfRQ7w)
* [How Ringpop from Uber Engineering Helps Distribute Your Application](https://eng.uber.com/intro-to-ringpop/)
* [etcd v3原理分析](https://yuerblog.cc/2017/12/10/principle-about-etcd-v3/)
    * Btree(内存索引) + bbolt(磁盘存储)
* [Cloudflare如何分析每秒上百万的DNS查询](https://mp.weixin.qq.com/s/hkBvVU4zrZlRUuQR1CKxNQ)
* [Zeppelin：一个分布式KV存储平台之概述](https://mp.weixin.qq.com/s/cfMtQ1YAZiCId3OM7bxXrg)
* [Go 在 TiDB 的实践](https://mp.weixin.qq.com/s/FHkIETZnb0mXi5KiJFbxXw)
* [从Elasticsearch来看分布式系统架构设计](https://mp.weixin.qq.com/s/gqxeNWjiVs2p0H9TCKWnEg)
* [SERF中去中心化系统的原理和实现](https://mp.weixin.qq.com/s/QcmMN_qX3D5pWu6m1FlriQ)
* [分布式系统架构经典资料](https://mp.weixin.qq.com/s/KbNNU246BAeJmLoWbKie6g)
* [万万没想到，分布式存储系统的一致性是......
](https://mp.weixin.qq.com/s/ZGYOwGjg06GSqCW3VoIzYg)
* [业务增长400%，Uber如何快准稳扩容HDFS集群？](https://mp.weixin.qq.com/s?__biz=MzU1NDA4NjU2MA==&mid=2247490167&idx=1&sn=6e4259c91760ee1c12ab44315bf63817&from=1084393010&wm=3333_2001&weiboauthoruid=5901272611)
* [面向云数据库，超低延迟文件系统PolarFS诞生了](https://mp.weixin.qq.com/s/4s7lDKlQjV1mUoVv558Y7Q)
    * POLARDB作为存储与计算分离结构的一款数据库。
    * 分布式系统的设计有两种范式：中心化和去中心化。
* [深入浅出下一代互联网基础IPFS](https://mp.weixin.qq.com/s/lZGOoILf3mvEEqQbAwDmlQ)
* [ESearch：58集团基于C++语言自主研发的搜索内核](https://mp.weixin.qq.com/s/qh88sawJUZedv3X0LIRsAQ)
* [比拼Kafka，大数据分析新秀Pulsar到底好在哪](https://mp.weixin.qq.com/s/v4A--nGiDTt58pZyIzepeg)
* [这可能是讲分布式系统最到位的一篇文章](https://mp.weixin.qq.com/s?__biz=MzU1NDA4NjU2MA==&mid=2247494017&idx=1&sn=6962ac4416f54018c67c410bec0a6093) 
    * `涉及多个进程协作才能提供一个完整功能的系统就是“分布式系统”`
* [万亿级数据洪峰下的分布式消息引擎](https://mp.weixin.qq.com/s/FuUICaNihx1PPKfxRTN1Fg)
    * GC日志的输出会发生文件IO，有时候也会造成不必要的停顿，可以将GC日志输出到tmpfs（内存文件系统）中，但tmpfs会消耗内存；
    * 容量保障三大法宝: 降级，限流和熔断；

#### Kafka
* [Apache Kafka：大数据的实时处理时代](http://www.infoq.com/cn/presentations/apache-kafka-real-time-processing-of-big-data?utm_source=infoq&utm_medium=videos_homepage&utm_campaign=videos_row1#)
* [kafka设计解析](http://www.jasongj.com/tags/Kafka/)
* [Kafka官方文档翻译——设计](http://www.cnblogs.com/hzmark/p/kafka_design.html)
* [浅谈分布式消息技术：Kafka](http://geek.csdn.net/news/detail/229569)
* [大规模Kafka集群的管理利器: LinkedIn最新开源的Cruise Control带来了什么？](https://mp.weixin.qq.com/s/9ou_hm8SrNceEggmeKNQPw)
* [Kafka 最佳实践](http://matt33.com/2017/09/04/kafka-best-pratice/) 
* [Kafka数据可靠性深度解读](http://www.infoq.com/cn/articles/depth-interpretation-of-kafka-data-reliability)
* [Kafka不只是个消息系统](http://www.infoq.com/cn/news/2017/10/Kafka-not-just-messag-system)
* [kafka 迈进了光荣的1.0](https://mp.weixin.qq.com/s/5r7M7KvV-qJqVzct3W5G-A)
    * 流动的数据就代表着这个世界的变化，是变化的。而一个表，代表这个世界在某个时间点的一个状态，是确定的。
    * exact-once语义
* [Exactly Once语义与事务机制原理](http://www.jasongj.com/kafka/transaction/)
* [批处理ETL已死，Kafka才是数据处理的未来？](https://mp.weixin.qq.com/s?__biz=MzIwMzg1ODcwMw==&mid=2247487484&idx=1&sn=ef8db9b61745f5f61bc797bb4f619d22&from=1082093010&wm=3333_2001&weiboauthoruid=5815864126)
* [Apache Kafka：优化部署的 10 种最佳实践](https://mp.weixin.qq.com/s/tjsnMTeKffVDYSLWZZf4LQ)


#### Raft
* [Raft 一致性算法论文译文](http://blog.luoyuanhang.com/2017/02/02/raft-paper-in-zh-CN/)
* [Raft - PingCAP](https://pingcap.com/RAFT/bloglist-zh)
* [Raft Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/)
* [基于Raft分布式一致性协议实现的局限及其对数据库的风险](https://mp.weixin.qq.com/s/zXbqF8PYH4Lta8XPH5-w3w)
* [分布式数据库数据一致性原理说明与实现](https://my.oschina.net/wangzhonnew/blog/1553841)
* [Elasticell-Multi-Raft实现](https://mp.weixin.qq.com/s/CwCjTS_mCYAiEnV-T2r19w)
* [Raft算法原理](https://lichuang.github.io/post/20180921-raft/)


#### Paxos
* [阿里如何实现高性能分布式强一致的独立 Paxos 基础库？](https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650997287&idx=1&sn=4b3ef76bb90c2e28e259802866dc934e)
* [phxpaxos](https://github.com/Tencent/phxpaxos/wiki)
* [PhxSQL设计与实现](https://mp.weixin.qq.com/s/-tc8MSpu6h5q3h8xuaRtcw)
* [微信分布式数据存储协议对比——Paxos和Quorum](http://geek.csdn.net/news/detail/193224)

#### 配置系统
* [Apollo](https://github.com/ctripcorp/apollo)
* [disconf](https://github.com/knightliao/disconf)
* [QConf](https://github.com/Qihoo360/QConf)

#### 监控系统
* [Open-Falcon](https://github.com/open-falcon)
* [ELKstack 中文指南](https://www.gitbook.com/book/chenryn/elk-stack-guide-cn/details)


---
## 6. 编程语言

#### Go
* [Go插件系统](https://mp.weixin.qq.com/s/XB2zGG5bD3MFe6nRcRdG5w)
* [Go 1.9中值得关注的几个变化](http://tonybai.com/2017/07/14/some-changes-in-go-1-9/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
* [调试Go语言的核心转储](http://xiecode.cn/post/cn_04_debugging_go_core_dumps/)
* [Go 1.9 新特性 Type Alias 详解](http://www.infoq.com/cn/news/2017/08/go-1-9-Type-Alias)
* [Go包管理的前世今生](http://www.infoq.com/cn/articles/history-go-package-management)
* [gops - A tool to list and diagnose Go processes currently running on your system](https://github.com/google/gops)
* [go-torch - Stochastic flame graph profiler for Go programs](https://github.com/uber/go-torch)
* [记一次获得3倍性能的Go程序优化实践](http://www.infoq.com/cn/articles/optimization-practice-of-go-program)
* [GOCN - 每日新闻](https://gocn.io/topic/%E6%AF%8F%E6%97%A5%E6%96%B0%E9%97%BB)
* [Go, don't collect my garbage](https://blog.cloudflare.com/go-dont-collect-my-garbage/)
* [热重启golang服务器(graceful restart golang http server)](http://kuangchanglang.com/golang/2017/04/27/golang-graceful-restart)
* [Go Profiling and Optimization](https://docs.google.com/presentation/d/1n6bse0JifemG7yve0Bb0ZAC-IWhTQjCNAclblnn2ANY/present?slide=id.g3a3e2af65_029)
* [年终盘点！2017年超有价值的Golang文章](http://colobu.com/2017/12/28/top-golang-articles-of-2017/)
* [Profiling Go programs with pprof](https://jvns.ca/blog/2017/09/24/profiling-go-with-pprof/)
    *   -inuse_space      Display in-use memory size
    *   -inuse_objects    Display in-use object counts
    *   -alloc_space      Display allocated memory size
    *   -alloc_objects    Display allocated object counts
* [How To Use Go Interfaces](https://blog.chewxy.com/2018/03/18/golang-interfaces/)
    * Postel’s Law: Be conservative with what you do, be liberal with you accept
* [An introduction to LLVM in Go](https://felixangell.com/blog/an-introduction-to-llvm-in-go)
* [Go Generate](https://blog.golang.org/generate)
* [Go Release](https://tonybai.com/articles/)
* [Go在谷歌：以软件工程为目的的语言设计](https://www.oschina.net/translate/go-at-google-language-design-in-the-service-of-software-engineering?lang=chs&#)
* [前端遇上Go: 静态资源增量更新的新实践](https://mp.weixin.qq.com/s/hCqQW1F8FngPPGZAisAWUg)
    * 包管理工具：glide
    * 增量补丁的生成算法 [go-diff](https://github.com/sergi/go-diff)
* [Golang’s Real-time GC in Theory and Practice](https://making.pusher.com/golangs-real-time-gc-in-theory-and-practice/)
* [Getting to Go: The Journey of Go's Garbage Collector](https://blog.golang.org/ismmkeynote)
* [Go 调度器: M, P 和 G](http://colobu.com/2017/05/04/go-scheduler/)
* [从Go高性能日志库zap看如何实现高性能Go组件](https://mp.weixin.qq.com/s/i0bMh_gLLrdnhAEWlF-xDw)
* [Golang - 调度剖析](https://segmentfault.com/a/1190000016038785)
    1.  PC 是下一个指令，而不是当前指令
    2.  上下文切换的延迟取决于不同的因素，大概在在 50 到 100 纳秒之间。考虑到硬件应该能够合理地(平均)在每个核心上每纳秒执行 12 条指令，那么一次上下文切换可能会花费 600 到 1200 条指令的延迟时间
* [Go1.11和WebAssembly](https://mp.weixin.qq.com/s/jqISsdQ9tDzy9Zg6g6u5xw)
    * `GOARCH=wasm GOOS=js go build -o a.out.wasm hello.go`
* [Tips and Tricks](https://github.com/davecheney/gophercon2018-performance-tuning-workshop/blob/master/6-tips-and-tricks/1-tips-and-tricks.md)
    * [Using []byte as a map key](https://github.com/davecheney/gophercon2018-performance-tuning-workshop/blob/master/6-tips-and-tricks/1-tips-and-tricks.md#using-byte-as-a-map-key)
* [Allocator Wrestling](https://about.sourcegraph.com/go/gophercon-2018-allocator-wrestling/)
* [Golang 里一个有趣的小细节](https://zhuanlan.zhihu.com/p/44851211)
* [Scheduling In Go - Part II](https://www.ardanlabs.com/blog/2018/08/scheduling-in-go-part2.html)
* [五种加速 Go 的特性](https://mp.weixin.qq.com/s/9BAYq4_ntGuACL1gQLi3EA)
* [Go语言最佳实战 一](https://mp.weixin.qq.com/s?__biz=MjM5OTcxMzE0MQ==&mid=2653371497&idx=1&sn=1dfc90bb65d61d710d7d1cf6783d4464)
* [Go语言最佳实战 二](https://mp.weixin.qq.com/s/vVhnZdhCB9DLmvxTkeZgoQ)
* [Gorilla web toolkit](http://www.gorillatoolkit.org/)


#### Python
* [打通Python和C++](http://blog.guoyb.com/2017/11/05/boost-python/)

#### Rust
* [Rust 程序设计语言（第一版） 简体中文版](https://www.gitbook.com/book/kaisery/rust-book-chinese/details)
* [Rust in Detail: Writing Scalable Chat Service from Scratch](https://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html)

#### C++
* [Preshing on Programming](http://preshing.com/)
* [C++ Core Guidelines](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines#main)
* [C++11那些事(1)](https://zhuanlan.zhihu.com/p/34795849)
    * C 标准库的 assert.h 中定义了NDEBUG宏。要使断言失效，只要在使用断言的文件中，在包含 assert.h 之前加入如下宏定义即可：#define NDEBUG

#### C
* [The C preprocessor](http://devarea.com/the-c-preprocessor/#.WnhQUZP1VGN)


#### Java
* [谈谈JVM的垃圾回收器](https://mp.weixin.qq.com/s/nEV7iPB4kOYIQVHY8cYygA)

---
## 7. 工具

#### Git
* [起底Git](http://yanhaijing.com/git/2017/01/19/deep-git-1/)
* [pro git](https://git-scm.com/book/zh/v2)
* [gitlab安装](https://about.gitlab.com/installation/#centos-7)
* [阿里云 - gitlab安装](https://yq.aliyun.com/articles/74395)
* [如何使用 Issue 管理软件项目](http://www.ruanyifeng.com/blog/2017/08/issue.html)
* [Git分支管理策略](http://www.ruanyifeng.com/blog/2012/07/git.html)
* [通过SSH 密钥连接GitHub/Bitbucket](https://blog.csdn.net/lue2009/article/details/46551201)
* [一些你可能会用到的Git实用技巧和命令](https://mp.weixin.qq.com/s?__biz=MzIzNjUxMzk2NQ==&mid=2247489702&idx=1&sn=d65d1458ef18fc65b30ce628ce2e3ab5)
* [彻底搞懂 Git-Rebase](http://jartto.wang/2018/12/11/git-rebase/)

#### Code Review
* [phabricator](https://phacility.com/phabricator/) **重点关注**
* [Gerrit Code Review](https://www.gerritcodereview.com/)

#### 命令
* [10个例子教你学会wget命令](https://github.com/lujun9972/linux-document/blob/master/examples/10%20wget%20command%20examples.org)
* [工具参考篇](http://linuxtools-rst.readthedocs.io/zh_CN/latest/tool/index.html)
* [tcpdump examples](https://hackertarget.com/tcpdump-examples/)

#### Mac
* [iTerm2 + oh my zsh +agnoster 打造最强Mac终端](http://www.siguoya.name/pc/home/article/256)
* [iTerm2 Oh-my-zsh配置与agnoster主题配置](https://wangwang4git.github.io/blog/2017/04/22/iterm2-oh-my-zsh-config-and-agnoster-theme-config/)
* [iTerm2 + OhMyZsh + agnoster + Powerline + solarized = 漂亮的Mac终端](https://blog.huihut.com/2017/03/11/FancyMacTerminal/)


---

## 8. 性能
* [火焰图- PingCAP](https://mp.weixin.qq.com/s/gR2XOrRXCgOzGJP2witgfw)
* [白话火焰图](https://huoding.com/2016/08/18/531)
* [Web服务器如何实现高吞吐低延迟？Dropbox从操作系统到应用层优化指南](https://mp.weixin.qq.com/s/Jx4DZWvDBCpWGJeSq84Eog)
* [如何读懂火焰图？](http://www.ruanyifeng.com/blog/2017/09/flame-graph.html)
* [使用 SystemTap 对系统进行动态追踪](http://www.jianshu.com/p/98ba9a1e7ac1?from=groupmessage&isappinstalled=0)
* [使用 Systemtap 排查隐形 Killer](http://www.jianshu.com/p/671014356c41)
* [gperftools](https://github.com/gperftools/gperftools/wiki)
* [CentOS7.2安装systemtap](http://www.hl10502.com/2017/09/26/centos-install-systemtap/)
* [Brendan Gregg's Blog](http://www.brendangregg.com/blog/index.html)
* [AddressSanitizer, ThreadSanitizer, MemorySanitizer](https://github.com/google/sanitizers)
* [如何使用TcMalloc解决OOM问题？](http://rdc.hundsun.com/portal/article/898.html)
* [Linux的page cache使用情况/命中率查看和操控](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652664563&idx=1&sn=ae34db814a25e8a0b824edba551c163e&from=1085193010&wm=3333_2001&weiboauthoruid=2155808472)
* [Brendan D. Gregg](http://www.brendangregg.com/)
* [记一次 TCMalloc Debug 经历](https://zhuanlan.zhihu.com/p/37696341)
* [引擎V8推出“并发标记”，可节省60%-70%的GC时间](https://mp.weixin.qq.com/s/t1RYfx5L13q8I3XwUCjrXA)
    1. V8 使用每个对象的两个 mark-bits 和一个标记工作表来实现标记。两个 mark-bits 编码三种颜色：白色（00），灰色（10）和黑色（11）。最初所有对象都是白色的，这意味着收集器还没有发现它们。当收集器发现它并将其推到标记工作表上时，白色对象变灰。当收集器将它从标记工作列表中弹出并访问其全部字段时，灰色对象变黑，这种方案被称为三色标记法。当没有灰色对象时，标记结束。所有剩余的白色对象都可以安全地被回收。
* [
软件开发中常见的十大系统瓶颈](https://www.csdn.net/article/2012-11-08/2811571-Big-List-Of-20-Common-Bottlenecks)
* [Linux I/O Performance Messungen mit iostat](https://www.thomas-krenn.com/de/wiki/Linux_I/O_Performance_Messungen_mit_iostat)
* [RedHat7 性能调节指南](https://access.redhat.com/documentation/zh-cn/red_hat_enterprise_linux/7/html-single/performance_tuning_guide/)
* [Redis高负载下的中断优化](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651747704&idx=3&sn=cd76ad912729a125fd56710cb42792ba&chksm=bd12ac358a6525235f51e3937d99ea113ed45542c51bc58bb9588fa1198f34d95b7d13ae1ae2#rd)
* [Investigating Linux Performance with Off-CPU Flame Graphs](https://www.memsql.com/blog/linux-off-cpu-investigation/)
* [千亿级HttpDNS服务是怎样炼成的](https://mp.weixin.qq.com/s?__biz=MzA3ODgyNzcwMw==&mid=2649021597&idx=1&sn=ec34bedde480e5d564ff88c46ffb148b&chksm=87aca545b0db2c535a09fad570537e608e61cc2bcb0394ae98d3a56e4ec99a2c8cfbf491ba17&scene=0&ascene=7&devicetype=android-24&version=2607023a&nettype=WIFI&abtest_cookie=BQABAAoACwANABIAEwAFACOXHgBZmR4AaZkeAG2ZHgB+mR4AAAA=&lang=zh_CN&pass_ticket=mXJ2sLok0aGpZNW+Zvn0xKFd1wdSa4nI2MlBW807KE1/JUt+RFUUmAc4J6EExasG&wx_header=1)
* [on-cpu、off-cpu、cpi火焰图文章汇总与视频讲解](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652665522&idx=1&sn=624336a89a40bb7c7ab8596663d14357)
* [我为什么关掉了超线程](https://mp.weixin.qq.com/s?__biz=MzIzODQyNjE1NA==&mid=2247484184&idx=1&sn=93f8957b2ecd5e5d38cc7b27a412d39a)


---
## 9. Linux
* [Difference between CLOCK_REALTIME and CLOCK_MONOTONIC?](https://stackoverflow.com/questions/3523442/difference-between-clock-realtime-and-clock-monotonic)
* [gettimeofday、vdso和阿里云](https://mp.weixin.qq.com/s?__biz=MzU3NDA1NDY0Ng==&mid=2247483774&idx=1&sn=9a689d34411130c9aadc7b5e26ab05e8)
* [为什么手工DROP_CACHES之后CACHE值并未减少？](http://linuxperf.com/?p=201)
* [/PROC/MEMINFO之谜](http://linuxperf.com/?p=142)
* [用户态文件系统(FUSE)框架分析和实战](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652662485&idx=1&sn=842f4e813ce198f567089a9b6cff26e6&chksm=810f2c48b678a55e56af866e8d05bd14307c475f0b871d0491d46b96441b9286c9e9b8643eef#rd)
* [Interactive map of Linux kernel](http://www.makelinux.net/kernel_map/)
* [Different I/O Access Methods for Linux, What We Chose for Scylla, and Why](http://www.scylladb.com/2017/10/05/io-access-methods-scylla/)
* [Linux的任督二脉——进程调度和内存管理](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652662197&idx=1&sn=8c75937824893e26ae920ed515a15d4c&chksm=810f2f28b678a63eab7c2b889c2a25967ce0f06719692ff6a29bfa0e843c7d49b59e52fefb96&scene=21#wechat_redirect)
* [Virtual Memory Tricks](http://ourmachinery.com/post/virtual-memory-tricks/)
* [Linux进程调度技术的前世今生之“前世”](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652662778&idx=1&sn=63b34df7baa0e924a52ef51c4ba7c96b&chksm=810f2d67b678a471f3bca52e785f9b6f31afe9c5b5118c5c74002d1b6c8235b48633f5282413#rd)
* [Linux 内核文件描述符表的演变](https://zhuanlan.zhihu.com/p/34280875?from=1083093010&wm=3333_2001&weiboauthoruid=1701018393)
* [read 系统调用剖析](https://mp.weixin.qq.com/s?__biz=MzAwMDUwNDgxOA==&mid=2652663862&idx=1&sn=8ebf565b3bf4ba32a79977c19d2e02fb&from=1083193010&wm=3333_2001&weiboauthoruid=2155808472)
* [Documentation for /proc/sys/vm/*	kernel version 2.6.29](https://www.kernel.org/doc/Documentation/sysctl/vm.txt)
* [Linux 文件系统 EXT4 的前世今生](https://www.oschina.net/translate/introduction-ext4-filesystem?lang=chs&page=1#)
* [so 无法 dlclose 问题初探](https://zhuanlan.zhihu.com/p/31120126)
* [Peeking into Linux kernel-land using /proc filesystem for quick’n’dirty troubleshooting](https://blog.tanelpoder.com/2013/02/21/peeking-into-linux-kernel-land-using-proc-filesystem-for-quickndirty-troubleshooting/)
* [FASTSOCKET System Configuration Script](https://github.com/fastos/fastsocket/tree/master/scripts)
    * nic.sh网卡相关脚本
* [应该知道的LINUX技巧](https://coolshell.cn/articles/8883.html)
* [理解虚拟内存](https://www.oschina.net/translate/understanding-virtual-memory) 
* [深入理解同步/异步与阻塞/非阻塞区别](https://www.jianshu.com/p/86e6f25d9e56)
* [Epoll is fundamentally broken](https://idea.popcount.org/2017-02-20-epoll-is-fundamentally-broken-12/)
* [About linux release](https://blog.stgolabs.net/)
* [facebook open source](https://opensource.fb.com/#linux)

---
## 10. 代码设计
* [10 Tips for Writing Better Code](https://my.oschina.net/editorial-story/blog/1525762)
* [如何像 NASA 顶级程序员一样编程 — 10 条重要原则](http://www.oschina.net/news/90499/nasa-programmer-rule)
* [系统设计的万能解法：SNAKE原则](https://mp.weixin.qq.com/s/u8NDvKcYv4ztVVRT_HaUJw)
    * Scenario（场景）
        - 枚举&排序
    * Necessary（限制）
        - 咨询&预测
    * Application（应用）
        - 重访&组合
    - Kilobit（数据）
        - 添加&选择
    - Evolve（进化）
        - 分析&回溯 
* [一分钟了解“好”接口的设计与实现](https://mp.weixin.qq.com/s/CwPno-g44lVxIOMt2u4lFw)
* [魔鬼在细节中](http://javatar.iteye.com/blog/1056664)
* [如何降低软件的复杂性？](http://www.ruanyifeng.com/blog/2018/09/complexity.html)


----
## 11. 服务
* [Envoy为什么能战胜Ngnix——线程模型分析篇](https://mp.weixin.qq.com/s/S9UMhUHSDEsvnksfz8PF5g)
* [RabbitMQ+Python入门经典 兔子和兔子窝](http://blog.ftofficer.com/2010/03/translation-rabbitmq-python-rabbits-and-warrens/)
* [libevent源码深度剖析](https://blog.csdn.net/sparkliang/article/details/4957667)

#### 负载均衡
* [关于现代网络负载均衡和代理](http://blog.54chen.com/post/load-balance/)
* [Google 是如何做负载均衡的？](https://mp.weixin.qq.com/s/2NQcwukKoHR4eFXZNtIb1w)
* [Facebook开源新一代网络负载均衡器Katran](http://www.infoq.com/cn/news/2018/06/Facebook-Katran)
* [maglev hashing](http://www.evanlin.com/maglev/)


---

## 12. 杂

* [QCon 上海 2017 PPT 合集](http://ppt.geekbang.org/qconsh2017)
* [技巧：多共享动态库中同名对象重复析构问题的解决方法](https://www.ibm.com/developerworks/cn/linux/l-cn-sdlstatic/index.html)
* [10 Things You Can Only Do With GDB](http://devarea.com/10-things-you-can-only-do-with-gdb/#.WnhT_ZP1VGM)
* [四个架构设计案例分析及其背后的架构师思维](https://mp.weixin.qq.com/s/FsZUYnfEnDZ0dAsJ3hcA5Q)
    * 抽象 + 分治
* [Deno 并不是下一代 Node.js](https://cnodejs.org/topic/5b14a93b57137f22415c48b3)
    * [mojo](https://chromium.googlesource.com/chromium/src/+/master/mojo/README.md) Chrome IPC
* [并发之痛 Thread，Goroutine，Actor](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=404242829&idx=1&sn=aacddf1c2c828281e6202eff8cd374f5&scene=21)
* [字符编码笔记：ASCII，Unicode 和 UTF-8](http://www.ruanyifeng.com/blog/2007/10/ascii_unicode_and_utf-8.html)
* [微信多媒体团队梁俊斌访谈：聊一聊我所了解的音视频技术](https://www.jianshu.com/p/930bb00376ae)
* [Google工程师教你编写垃圾回收器](http://blog.jobbole.com/53376/)
* [系统架构领域的一些学习材料](http://blog.jobbole.com/87194/)
* [如何选择开源许可证？](http://www.ruanyifeng.com/blog/2011/05/how_to_choose_free_software_licenses.html)
* [开源许可证教程](http://www.ruanyifeng.com/blog/2017/10/open-source-license-tutorial.html)
* [RESTful API 最佳实践](http://www.ruanyifeng.com/blog/2018/10/restful-api-best-practices.html)
* [CTO、技术总监、首席架构师的区别](https://mp.weixin.qq.com/s/6g-oTgBIILC4xFYHCRyDlw)
* [Google 图解 Chrome：浏览器也讲究事件分发策略 | 完结篇](https://mp.weixin.qq.com/s/sYPqmhDuMgwVCC2EUJOL8Q)
* [GitHub服务中断24小时11分钟事故分析报告](https://mp.weixin.qq.com/s/fFv1ASElHsVNEPPkP53qAQ)
    * 事故处理能够全面复盘，有记录，有总结，有改进；
    * 处理事故的时候，针对最高优先级（数据完整性）采取措施（服务降级）；
    * 服务设计之初就时候需要考虑各种备案应对问题（自动切换到手动；服务降级）；
* [OKR 工作法简介](https://mp.weixin.qq.com/s?__biz=MjM5NTIyNTUyMQ==&mid=2709545980&idx=1&sn=ce2bdde3526d0ee231a0d44f810333e9)
* [如何应对在线故障](http://www.rowkey.me/blog/2018/11/22/online-debug/)

----
