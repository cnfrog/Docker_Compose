FROM griefed/baseimage-ubuntu-jdk-8

#复制上下文目录下的jar包到容器里  使用COPY命令亦可
ADD sentinel-dashboard-1.8.3.jar sentinel-dashboard-1.8.3.jar

EXPOSE 8080

#指定容器启动程序及参数   <ENTRYPOINT> "<CMD>"
ENTRYPOINT ["java","-jar","sentinel-dashboard-1.8.3.jar"]