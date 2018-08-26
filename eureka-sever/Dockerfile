FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/eureka-sever.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/eureka-sever.jar"]

EXPOSE 4000
