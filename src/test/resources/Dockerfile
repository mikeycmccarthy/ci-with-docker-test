FROM centos

RUN yum update -y
RUN yum install -y java-1.7.0-openjdk

ADD ${project.build.finalName}.jar /

CMD ["java", "-jar", "docker-tested-app-1.0.jar"]

EXPOSE 8080
EXPOSE 8081
