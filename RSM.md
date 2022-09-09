类别 | 主题 |  | Content
:-:|:-:|:-:|:-:
数据库系统 | 存储| LSM-tree 存储| [LSM-tree存储优化](https://arxiv.org/abs/1812.07527) 
-- | --| 索引| [B+-tree技术](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.219.7269&rep=rep1&type=pdf)
-- | 查询| 数据库查询执行引擎| [火山模型,MPP](https://zhuanlan.zhihu.com/p/100949808 ) 
-- | -- |                        |                                                              
-- |--|NewSQL中数据库查询引擎| [Presto](https://prestosql.io/Presto_SQL_on_Everything.pdf), [Google F1](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/41344.pdf), [Snowflake](http://pages.cs.wisc.edu/~yxy/cs839-s20/papers/snowflake.pdf)
-- | 事务| 并发控制| [2PL, OCC, Basic Timestamp Ordering](https://www.guru99.com/dbms-concurrency-control.html), [MVCC](http://www.vldb.org/pvldb/vol10/p781-Wu.pdf)
-- | --| 日志| [日志与缓冲区策略](http://www.cs.washington.edu/education/courses/cse544/11wi/papers/franklin97.pdf), [ARIES](https://dl.acm.org/doi/10.1145/128765.128770) 
--|分布式事务 |--|[2PC](https://documentation.progress.com/output/ua/OpenEdge_latest/index.html#page/dmadm/how-the-database-engine-implements-two-phase-com.html), [Pecolator](https://research.google/pubs/pub36726/), [Vector Timestamps](https://www.cs.princeton.edu/courses/archive/fall18/cos418/docs/L4-vc.pdf), [Spanner](https://research.google/pubs/pub39966/), [非数据库层面解决方法： 消息队列， TCC](https://medium.com/@Alibaba_Cloud/breaking-the-limits-of-relational-databases-an-analysis-of-cloud-native-database-middleware-2-d3e790de0673) , [Bailis的文章](http://www.vldb.org/pvldb/vol7/p181-bailis.pdf)
--|Benchmark|--| [TPC-C, TPC-E, TPC-H, TPC-DS](http://www.tpc.org/tpcc/), 
-- |NewSQL数据库架构|云数据库|[Megastore](https://research.google/pubs/pub36971/), [Aurora](https://awsmedia.awsstatic-china.com/blog/2017/aurora-design-considerations-paper.pdf), [PolarDB](https://zhuanlan.zhihu.com/p/87934090)
--  |--|HTAP|[TiDB](http://www.vldb.org/pvldb/vol13/p3072-huang.pdf),[OB](https://github.com/oceanbase/oceanbase)
分布式系统 | 分布式存储| 文件存储 | [GFS](https://research.google.com/archive/gfs-sosp2003.pdf),[HDFS](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5496972) 
--|--| 分布式KV扩展| Dynamo,Bigtable,  Cassandra , Consistent Hashing 
--|分布式共识| Raft, ZAB| [Raft](https://raft.github.io/raft.pdf), [Zookeeper](https://www.usenix.org/legacy/events/atc10/tech/full_papers/Hunt.pdf) 
--|--| Paxos | Basic Paxos, Multi-Paxos 
--|--| E-Paxos| [E-Paxos](https://www.cs.cmu.edu/~dga/papers/epaxos-sosp2013.pdf)
--|--| PBFT | [PBFT](http://nil.csail.mit.edu/6.824/2017/papers/castro-practicalbft.pdf) 
--     |    分布式计算    |           --           | [MapReduce](https://pdos.csail.mit.edu/6.824/papers/mapreduce.pdf) 
--     |       缓存       |           --           | [Memcache](https://pdos.csail.mit.edu/6.824/papers/memcache-fb.pdf) 
--     |        --        |           --           |           [Redis](https://redis.com/whitepapers/)            
--     |        --        |           --           | [一致性模型](https://zhuanlan.zhihu.com/p/48157076)， [内存计算核心技术](https://zhuanlan.zhihu.com/p/35668651) 
实现技术  |       网络       |          RPC           |[gRPC](https://grpc.io/) 
--|--|IO复用| [一文看懂IO多路复用](https://zhuanlan.zhihu.com/p/115220699)，[事件驱动与协程](https://zhuanlan.zhihu.com/p/31410589) 
--|多线程编程|竞争与等待|
--|--|无锁技术| [lock-free data structure](https://www.cnblogs.com/lucifer1982/archive/2009/04/08/1431992.html)
--|--|锁实现| [Rethinking Lock](https://zhuanlan.zhihu.com/p/179245291)
计算机基础|书籍|--|《深入理解计算机系统》
--|--|--|《分布式系统概念》
--|--|--|《数据库系统概念》、《数据库系统实现》
--|--|--|[《数据密集型应用》](http://ddia.vonng.com/#/)
视频课程|--|--|[cmu 15-445(Intro to Database Systems)](https://15445.courses.cs.cmu.edu/fall2022/)
--|--|--|[cmu 15-721(Advanced Database System)](https://15721.courses.cs.cmu.edu/spring2020/)
--|--|--|[mit 6.824(Distributed Systems)](https://pdos.csail.mit.edu/6.824/)
区块链论文|2019|VLDB|[CAPER: A Cross-Application Permissioned Blockchain](https://arxiv.org/pdf/1812.02386.pdf)
--|--|--|[BlockchainDB - A Shared Database on Blockchains](https://arxiv.org/pdf/1812.02386.pdf)
--|--|--|[Fine-Grained, Secure and Efficient Data Provenance on Blockchain Systems](https://arxiv.org/pdf/1812.02386.pdf)
--|--|--|[Blockchain Meets Database: Design and Implementation of a Blockchain Relational Database](https://arxiv.org/pdf/1812.02386.pdf)
--|--|ICDE|[SEBDB:Semantics Empowered BlockChain DataBase](https://arxiv.org/pdf/1812.02386.pdf)
--|--|SIGMOD|[Towards Scaling Blockchain Systems via Sharding](https://www.comp.nus.edu.sg/~hungdang/papers/sharding.pdf)
--|--|--|[Blurring the Lines between Blockchains and Database Systems: the Case of Hyperledger Fabric](https://dl.acm.org/doi/pdf/10.1145/3299869.3319883?download=true)
--|--|--|[vChain: Enabling Verifiable Boolean Range Queries over Blockchain Databases](https://arxiv.org/pdf/1812.02386.pdf)
--|--|SOSP|[Teechain: A Secure Payment Network with Asynchronous Blockchain Access](https://arxiv.org/pdf/1812.02386.pdf)
--|--|--|[Fast and Secure Global Payments with Stellar](https://arxiv.org/pdf/1812.02386.pdf)
--|--|--|[Notary: A Device for Secure Transaction Approval](https://pdos.csail.mit.edu/papers/notary:sosp19.pdf)
