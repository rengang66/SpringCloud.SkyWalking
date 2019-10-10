SpringCloud.SkyWalking示例项目

# 180--spring cloud + skywalking

skywalking示例项目

This case is based on Spring cloud to implement the micro-service call chain, which uses SkyWalking framework.

本案例基于Spring cloud来实现微服务调用链，微服务调用链采用SkyWalking框架。

启动步骤：
（1）启动 elasticsearch服务；
（2）启动 apache-skywalking-apm-bin
（3）启动 service-discovery ；java -Dfile.encoding=utf-8  -javaagent:skywalking-agent.jar -jar service-discovery-0.0.1-SNAPSHOT.jar
（4）启动 user-service；java -Dfile.encoding=utf-8  -javaagent:skywalking-agent.jar -jar user-service-0.0.1-SNAPSHOT.jar
（5）启动 product-service。java -Dfile.encoding=utf-8  -javaagent:skywalking-agent.jar -jar product-service-0.0.1-SNAPSHOT.jar


