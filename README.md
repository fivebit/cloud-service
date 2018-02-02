使用了zuul 做API 网关。

eureka 做服务发现。

config 做配置中心。

启动顺序：

1. eureka server: http://127.0.0.1:8889/
2. config server 
3. config-client config-client2: http://127.0.0.1:9881/hi http://127.0.0.1:9882/hi
4. zuul :http://127.0.0.1:8181/hi