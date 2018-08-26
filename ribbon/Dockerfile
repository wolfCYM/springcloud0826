FROM index.alauda.cn/demo100/piggyjava 
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD ./target/ribbon-1.4.0.RELEASE.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/ribbon-1.4.0.RELEASE.jar"]

EXPOSE 7072