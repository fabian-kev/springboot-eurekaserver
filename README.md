# springboot-eurekaserver

.yml

server:
  port: 8761
eureka:
  instance:
    hostname: localhost
  client:
    registerWithEureka: false
    fetchRegistry: false
    serviceUrl:
      defaultZone: http://${eureka.instance.hostname}/eureka/
spring:
  application:
    name: eureka-server
