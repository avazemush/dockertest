FROM java:8-jre
MAINTAINER ss <aaa@qq.com>

ADD ./target/dockertest-0.0.1-SNAPSHOT.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/dockertest-0.0.1-SNAPSHOT.jar"]

EXPOSE 8888