# HadoopSourceLearnNote
一、hadoop源码中比较重要的一些project

1,hadoop-common-project:Hadoop基础库所在的目录，该目录中包含了其他所有模块及工程可能会用到的基础库，包括RPC、Metrics、Counter等。

2，hadoop-mapreduce-project:Mapreduce框架的实现，有了YARN框架后，该project仅包含非常简单的任务分配功能。

3，hadoop-hdfs-project:Hadoop分布式文件系统实现，支持HA，解决了NameNode单点故障问题。

4，hadoop-yarn-project:Hadoop资源管理系统YARN平台。该系统能够同意管理系统中的资源，并按照一定的策略分配给各个应用程序。

二、YARN系统主要分为5部分：API、Common、Applications、Client、Server

1、hadoop-yarn-api:给出YARN内容涉及的4个主要RPC协议的java声明和Protocol Buffers定义，这4个RPC协议分别是ApplicationClientProtocol、ApplicationMasterProtocol、ContainerManagementProtocol和ResourceManagerAdministrationProtocol。

2、hadoop-yarn-common：该部分包含了YARN底层库实现，包括事件库、服务库、状态机库等。

3、hadoop-
