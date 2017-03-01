# mqant
mqant是一款基于Golang语言的简洁,高效,高性能的分布式游戏服务器框架,研发的初衷是要实现一款能支持高并发,高性能,高实时性,的游戏服务器框架,也希望mqant未来能够做即时通讯和物联网方面的应用

#	特性
1. 分模块机制
2. 基于golang协程,开发过程全程做到无callback回调,代码可读性更高
3. RPC支持本地和远程自动切换
4. 远程RPC默认使用rabbitmq,未来可以添加更多种类的通信协议
5. 网关采用MQTT协议,无需再开发客户端底层库,直接套用已有的MQTT客户端代码库,可以支持IOS,Android,websocket,PC等多平台通信

# 社区
QQ交流群 :463735103

#	文档

 快速上手:
 
 [mqant wiki](https://github.com/liangdas/mqant/wiki)

 [全平台聊天Demo](https://github.com/liangdas/mqantserver)
 
 [在线Demo演示（随时可能关闭）](https://www.h5link.com/mqant/index.html)
 

#	框架架构
[mqant的设计动机](https://github.com/liangdas/mqant/wiki/mqant%E7%9A%84%E8%AE%BE%E8%AE%A1%E5%8A%A8%E6%9C%BA)

[框架架构](https://github.com/liangdas/mqant/wiki/mqant%E6%A1%86%E6%9E%B6%E6%A6%82%E8%BF%B0)
	

##下一步计划
1. 插件系统
2. 日志模块
3. 讨论社区
4. 分布式架构管理工具
5. 可伸缩服务器部署
。。。


##贡献者

欢迎提供dev分支的pull request

bug请直接通过issue提交

凡提交代码和建议, bug的童鞋, 均会在下列贡献者名单者出现