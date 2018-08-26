FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

CMD ["mkdir", "/app"]
ADD ./target/eureka-sever-1.4.0.RELEASE.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/eureka-sever-1.4.0.RELEASE.jar"]

EXPOSE 4000
