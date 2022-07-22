# 创建父pom
# 创建cloud-eureka
### @EnableEurekaServer注解
实质就是一个开关，导入EurekaServerMarkerConfiguration.Marker的bean入容器
这样一来EurekaServerAutoConfiguration中@ConditionalOnBean({EurekaServerMarkerConfiguration.Marker.class})就会生效
# 创建api-passenger