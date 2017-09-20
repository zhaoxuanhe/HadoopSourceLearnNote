# HadoopSourceLearnNote
一、hadoop源码中比较重要的一些project

1,hadoop-common-project:Hadoop基础库所在的目录，该目录中包含了其他所有模块及工程可能会用到的基础库，包括RPC、Metrics、Counter等。

2，hadoop-mapreduce-project:Mapreduce框架的实现，有了YARN框架后，该project仅包含非常简单的任务分配功能。

3，hadoop-hdfs-project:Hadoop分布式文件系统实现，支持HA，解决了NameNode单点故障问题。


