#### System Migration

适用于个人的主机 Widnows 系统迁移，部署不在本文的讨论范围；

目前的基本方式：1. 硬链接；2. 压缩迁移；

目前的工具：Windows PE、傲梅分区助手、Windows Tools；

##### 一、相关基础

###### 1.硬链接

复制一份完整的数据文件到一台电脑或磁盘，更改系统的启动方式；

缺点：点对点传输，必须在“同一条数据传输线”中；

###### 2.压缩后迁移

包含硬链接的技术上，压缩目标系统，跨距离或远程传输、

特点：高可用性、可便携随身。

##### 二、应用

以下工具并不存在“全能”的情况，以需求为主它们是你解决问题的一个集合；

###### 1. Windows PE+第三工具

最为简单，例如分区管理、磁盘管理等程序都可完成预期的迁移计划；

支持官方、第三方的 ISO、GHOST、WIN 等镜像，集成其他管理工具、网络工具、文件工具等，适用于IT人员；

###### 2. Windows Tools

control - system - backup，支持定时备份，可选存储网络或本地；

###### ３. 其他第三方

Vmware 物理机虚拟化、AcronisTrueImage 等等；

###### 4. Notes

相关的使用教程、图文并茂的文章，此处不做具体的描述。

核心的参考书：Google：PE 重装、迁移、密码管理、磁盘管理；

#### 附录

[Google](https://www.google.com)





