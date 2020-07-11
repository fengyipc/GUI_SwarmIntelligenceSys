# SwarmIntelligenceSystem

这是一个集Web前端实时控制、服务器与多智能体无线通信、多智能体集群调度、嵌入式系统开发于一身的综合系统平台。

### 我的工作：
1. 以TCP/UDP协议为基础，通过上层封装实现具有实时性、高可靠性的多播网络通信模块。
2. 完成服务器MySQL数据库的设计与集群控制端SQL读写访问。
3. 设计多智能体集群编队任务的多线程算法控制模块，并完成大部分代码的编写与调优。

### 开发环境： Windows 10 、树莓派Linux

### 开发语言： Python 3

### 文件功能：
- Comunication文件：里面实现数据库所在终端与集群机器人之间进行TCP，UDP多播通信（python）。
- css文件：GUI的样式文件。
- fonts文件：GUI字体库。
- js文件：GUI交互javascript代码。
- GUI.html:GUI界面。
- mysql文件：php数据库接口：get_all.php返回每个ID下的最新数据；get_single.php返回指定ID最新数据；post_command.php上传GUI控制指令到command表。
- test_get_all.html：测试get_all.php接口；
- test_get_single.html:测试get_single.php接口；

### 数据库结构：
查看数据库结构pdf文件
