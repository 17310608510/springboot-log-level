需求背景
SpringBoot用法：动态修改日志输出级别

问题痛点
SpringBoot在 spring-boot-starter-actuator 模块中提供了日志相关的EndPoint，通过该EndPoint可以在项目运行时不需要重启服务就可以修改日志的打印级别，解决了以前修改日志打印级别必须要重启服务的烦恼。