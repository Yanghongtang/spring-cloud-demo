# spring-cloud-demo
学习springcloud知识点的demo，有Eureka集群的服务端7001、7002、7003，微服务三个：8001、8002、8003，使用Hystrix做服务端的熔断机制、利用，成功注册到Eureka服务端，客户端用Feign做服务降级。客户端消费微服务方式有两种，第一种是使用restTemplate的restful接口直接调用，第二种是Feign做客户端，用Spring Cloud Ribbon实现客户端负载均衡。getway的zuul做服务网关，利用了spring cloud config进行服务配置，并成功调用。
