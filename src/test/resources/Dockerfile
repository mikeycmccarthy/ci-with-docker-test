FROM centos

RUN yum update -y
RUN yum install -y java-1.7.0-openjdk

EXPOSE 8080
EXPOSE 8081

CMD ["java", "-jar", "docker-tested-app-1.0.jar"]