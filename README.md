#项目目录结构说明
## ServiceRegistration
        使用Eureka-Server来完成服务的注册与发现，该项目为所有微服务的注册中心
## ServiceConfiguration
        使用Spring-Cloud-Config-Server来完成分布式的配置中心，然后结合Eureka-Server来完成所有微服务的配置管理
## ServiceApiGateway
        使用Spring-Cloud-Starter-Zuul来完成智能路由，可以统一向外部系统提供REST API。Spring Cloud中使用Zuul作为API Gateway。
    Zuul提供了动态路由、监控、回退、安全等功能。
                                       
