paopao
======

跑炮--跑到另一个城市约炮去，是这个节奏么？

开发环境说明
------------

暂时我们使用 github + 本地服务器的方式。

本地服务器的主要问题在于暂时没有静态IP。
后面我们托管到阿里云之后，问题就会得到相应的解决。

目前的临时解决方案是：

当前的代码库中开一个branch `ip_realtime`，
服务器上用一个脚本定期的获取外部ip并push到github上。

任务管理使用redmine，代码使用github，详细的说明，稍后补充。
