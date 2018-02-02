使用了zuul 做API 网关。

eureka 做服务发现。

config 做配置中心。

启动顺序：

1. eureka server
2. config server 
3. config-client config-client2
4. zuul 