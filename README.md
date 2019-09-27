# 关于

- 本仓库将以面试题为导向，将 Java 后台开发面试中遇到的问题和解题思路或答案整理输出，一方面是为了方便自己复盘，另一方面也是希望对其他胖友能有所帮助；
- 由于水平有限，本仓库中部分题目来源于面试所遇，一部分源于网上；
- 面试题只是为了让我们在学习这些技术的时候知道如何抓住重点，但不能只浮于表面，而是要稳扎稳打，把基础打牢，勿在浮沙筑高台；
- 源码之中，了无秘密，即使现在没有太多源码阅读的经验，后续也一定要多多阅读源码。

# 前言

- 整理不易，如果觉得有帮助请点个 `star`

# 目录

## Java基础
## Java并发
## JVM
## 框架
- [Spring](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring)
  - [Spring Framework](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-framework)
  - [Spring Bean](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-bean)
  - [Spring IoC](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-ioc)
  - [Spring 注解](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-%E6%B3%A8%E8%A7%A3)
  - [Spring AOP](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-aop)
  - [Spring 事务](https://github.com/bigrotor187/awesome-java-interview/tree/master/framework#spring-%E4%BA%8B%E5%8A%A1)
## 分布式系统
### 分布式缓存
- Memcached

- Redis
  - Redis 是什么？都有哪些使用场景？
  - Redis 有哪些功能？
  - Redis 和 memecache 有什么区别？
  - Redis 为什么是单线程的？
  - 什么是缓存穿透？怎么解决？
  - Redis 支持的数据类型有哪些？
  - Redis 支持的 java 客户端都有哪些？
  - Jedis 和 redisson 有哪些区别？
  - 怎么保证缓存和数据库数据的一致性？
  - Redis 持久化有几种方式？
  - Redis 怎么实现分布式锁？
  - Redis 分布式锁有什么缺陷？
  - Redis 如何做内存优化？
  - Redis 淘汰策略有哪些？
  - Redis 常见的性能问题有哪些？该如何解决？

### 分布式服务框架
- Dubbo
  - Dubbo简介
  - 待续

### 分布式协调服务
- Zookeeper
  - 简述Zookeeper
  - 简述ZAB协议
  - 简述Paxos算法
  - ZK如何保证数据的一致性？
  - Dubbo简介及以Zookeeper为注册中心
  - Zookeeper的leader选举过程
  - 2PC and 3PC
  - 简述Zookeeper的watcher
  - 简述ZAB集群数据同步的过程
  - 简述Zookeeper中的ACL
  - Zookeeper底层是如何实现数据一致性的？
  - Zookeeper在yarn框架中如何实现避免脑裂的?
  
### 分布式消息队列
- RabbitMQ
  - 什么是RabbitMQ?
  - 为什么要使用RabbitMQ?
  - 消息队列的优缺点？
  - RabbitMQ 与 Kafka 有什么区别？
  - RabbitMQ 的使用场景有哪些？
  - RabbitMQ 有哪些重要的角色？
  - RabbitMQ 有哪些重要的组件？
  - RabbitMQ 中 vhost 的作用是什么？
  - RabbitMQ 的消息是怎么发送的？
  - RabbitMQ 怎么保证消息的稳定性？
  - RabbitMQ 怎么避免消息丢失？
  - 要保证消息持久化成功的条件有哪些？
  - RabbitMQ 持久化有什么缺点？
  - RabbitMQ 有几种广播类型？
  - RabbitMQ 怎么实现延迟消息队列？
  - RabbitMQ 集群有什么用？
  - RabbitMQ 节点的类型有哪些？
  - RabbitMQ 集群搭建需要注意哪些问题？
  - RabbitMQ 每个节点是其他节点的完整拷贝吗？为什么？
  - RabbitMQ 集群中唯一一个磁盘节点崩溃了会发生什么情况？
  - RabbitMQ 对集群节点停止顺序有要求吗？
- Kafka
  - Kafka 都有哪些特点？
  - 请简述下你在哪些场景下会选择 Kafka？
  - 简述Kafka 的设计架构
  - Kafka 分区的目的
  - Kafka 是如何做到消息的有序性的？
  - Kafka 的高可靠性是怎么实现的？
  - 请谈一谈 Kafka 数据一致性原理
  - ISR、OSR、AR 是什么？
  - LEO、HW、LSO、LW等分别代表什么
  - Kafka 在什么情况下会出现消息丢失？
  - 怎么尽可能保证 Kafka 的可靠性
  - 消费者和消费者组有什么关系？
  - Kafka 的每个分区只能被一个消费者线程，如何做到多个线程同时消费一个分区？
  - 数据传输的事务有几种？
  - Kafka 消费者是否可以消费指定分区消息？
  - Kafka消息是采用Pull模式，还是Push模式？
  - 如何为Kafka集群选择合适的Topics/Partitions数量
  - 待续

### 分布式搜索引擎

- Elasticsearch
  - Elasticsearch简介

- Solr
  - Solr简介
  - 简述Solr的倒排索引
  - 为什么要使用Solr?
  - Solr和elasticsearch的区别？

### 分布式事务
- 刚性分布式事务
- 柔性分布式事务
- 两阶段提交协议&三阶段提交协议
- 一致性哈希算法

## 数据库
  - 数据库的三范式是什么？

  - 一张自增表里面总共有 7 条数据，删除了最后 2 条数据，重启 mysql 数据库，又插入了一条数据，此时 id 是几？

  - 如何获取当前数据库版本？

  - 说一下 ACID 是什么？

  - char 和 varchar 的区别是什么？

  - float 和 double 的区别是什么？

  - mysql 的内连接、左连接、右连接有什么区别？

  - mysql 索引是怎么实现的？

  - 怎么验证 mysql 的索引是否满足需求？

  - 说一下数据库的事务隔离？

  - 说一下 mysql 常用的引擎？

  - 说一下 mysql 的行锁和表锁？

  - 说一下乐观锁和悲观锁？

  - mysql 问题排查都有哪些手段？

  - 如何做 mysql 的性能优化？

## 设计模式
## 数据结构和算法
