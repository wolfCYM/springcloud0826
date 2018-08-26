FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/eureka-server.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/eureka-server.jar"]

EXPOSE 4000
