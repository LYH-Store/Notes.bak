## Computer hardware and software design

编写的目的：1. 如何查看硬件参数；2. 服务器的硬件；

### 1. Person Computer

了解服务器基础设备就先了解个人电脑，大小规格、芯片设计、供电设计、散热设计、售后服务；

#### 机箱

规格：E-ATX、ATX、M-ATX、ITX

主要与其他配件的大小要符合，通常越大的机箱扩展性就越强，反之则越小。其外可以考虑优秀的设计，比如散热、静音、硬盘卡槽、塔式等设计成分。

#### 供电

规格：ATX、SFX、FlexATX（以家用的为例）

由于供电设计、电能转化、电流设计等等是专业的学问，此文不做累述，此处只是简单的说明外观和。

Notes：专业的事让专业的人处理，终端用户考虑其售后和质量（可参考电源的评测文章）

> 更详细的内容（包含供电线路接口设计解析），请查阅 Wikipedia Link： [PC 电源供电器](https://zh.wikipedia.org/wiki/電源供應器)

#### 主板

规格：ITX、M-ATX、ATX、E-ATX（按大小排序）

涉及：供电芯片、DIMM、音频芯片、散热、“CPU 针扣”、PCIe 槽、M2 槽、SATA 槽等等，详情请查阅主板的说明书

Notes：考虑一块主板的核心就是供电、散热及扩展性，其次就是自己需求

**USB**

USB2.0、USB3.0、USB3.1-Gen2

**指令**

开关、重启、硬盘指示灯、光驱指示灯

#### PCIe

**网卡**，百兆、千兆、万兆（光纤），注意：目前 Windows 不支持聚合链路

可扩展 STAT、RAID、显卡、M.2、检测卡等高速的数据处理的扩展卡。注意：专业的设备请配合专业的驱动使用。

#### 外部接口

USB、HDMI、VGA、DP、RJ45、3.5mm 音频等

### 2. Server Computer

更为专业化的设备，具备特定的设计

Notes：噪音极大，平均 50db 以上，只能躲在专业化的机房里

#### 机箱

##### 1. 塔式

存放于机柜中，其设计为便利式拆卸（及模块化设计），分区明显偏向于可维护设计（比如硬盘卡槽设计）

一个参考示例：尾部（供电/PCIe/网卡），中部（CPU/内存/风扇），前部（简式指令/卡式存储/调试接口）

##### 2. NAS

用于专业的存储的设备，存储卡扣式设计为基本，集成其他功能（比如 RAID、千兆网卡）

分类为家用、商用的区别，且价格较贵。个人或小企业可以使用 FreeNAS（开源，且功能较为齐全）

#### 供电

双路供电，单路供电，优先考虑其稳定性和可扩展，为后面的升级、扩展提供强有力的电力支持。

Notes：估计目前和未来的功耗计算，算好功耗搭配稳定安全电源的供应商或集成商家即可

#### 主板

更强的可扩展性：内存、CPU、PCIe、供电。

更高速的传输通道 PCIe * 4 more。



#### 前置面板

USB，提供便捷式且通用的传输方式。

指示灯，用于错误排查和供电信号确认。

#### PCIe

卡位式设计，方便设备的可扩展

#### 外部接口

### 3. System and Software

首先系统本身就是一个集成的软件平台，无需额外调查第三方软件查阅电脑硬件信息。相比之下成熟的现成方案可以提供优秀的解决方法，优先考虑集成化，可定制，更为符合业务需求最好不过了。

Windows、Linux、macOS

Windows：关于电脑、设备管理器、第三方程序

Linux 利用程序

> [利用程序命令查看电脑信息](https://linux.cn/article-11422-1.html)

macOS，About System



