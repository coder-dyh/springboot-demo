# from 表示新的镜像基于 basic_centos:latest
FROM openjdk:8-jdk-alpine

# maintainter 作者信息
MAINTAINER "Deng Yuanhua"<1374697383@qq.com>

VOLUME /tmp

# 通过 ADD 指令将该 jar 添加到 Docker 镜像（自动解压）
#ADD @project.build.finalName@.jar springboot-demo-0.0.1.jar

## 将当前应用暴露到容器的 8080 端口
#EXPOSE 8080
#
## 设置容器启动时需要执行的命令（可被覆盖）
#CMD java -jar docker-springboot-application.jar