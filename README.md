## 项目介绍　　
mmorpg，是一个用java编写的轻量级高性能mmorpg手游服务端框架。项目提供各种支持快速二次开发的组件，以及对生产环境的服务进行管理的工具。同时，为了使用户能够快速上手，项目提供了若干常用业务功能作为演示。

## 项目特点  
* 使用状态同步实现pk技能同步  
* 允许socket/websocket同时接入，兼容手游/页游服务端架构    
* 有独立http后台网站，为游戏运维/运营提供支持  
* 框架提供多种组件，可以直接二次开发业务逻辑  
* 提供热更机制以及jmx接口，方便对生产项目进行监控与维护    
* 尽可能使用springboot组件进行搭建    



## 使用spring/springboot的组件 
名称 | 用途 
----|------
spring cache | 数据缓存 
springdatajdbc | 多数据源orm框架  
springmvc | 管理后台接口


## ToDoList  
* 场景寻路及分屏算法  
* 主动技能/被动技能实现  
* buff系统  
* 更多基础设施与业务演示  

## 与jforgame项目的主要不同之处 
* 使用spring-boot框架，力求最便利使用spring组件
* 网络io选用了Netty/Mina, 依赖管理选用了gradle
* 重点用于演示场景及技能系统  
* 尝试使用一些新技术栈  


## 快速开始  
1. 使用git下载代码 git clone https://github.com/kingston-csj/mmorpg;  
2. 将代码导入带有gradle插件的IDE;    
3. 启动服务端，入口为ServerStartup类;  
4. 启动客户端，入口为ClientStartup类;  
注意：项目使用了lombok库，用于代码简写，开发环境需要下载对应插件，请自行百度


欢迎star/fork，欢迎学习/使用，期待一起贡献代码！！

## 请作者喝杯咖啡
如果您觉得有所收获，可以请作者喝杯咖啡。大家的支持，促使我不断改进优化，谢谢！  
![](/screenshots/wx.png "微信收款码")
![](/screenshots/zfb.jpg "支付宝收款码")


## 一起交流
如果您发现bug，或者有任何疑问，请提交issue !!  
或者加入交流QQ群：780465774

## 免责申明
本项目只用于学习研究，禁止用于非法获利和商业活动。如产生法律纠纷与作者无关！！

