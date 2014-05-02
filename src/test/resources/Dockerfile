FROM centos

RUN yum update -y
RUN yum install -y java-1.7.0-openjdk

ADD ${project.build.directory}/${project.build.finalName}.jar /

EXPOSE 8080
EXPOSE 8081

CMD ["java", "-version"]