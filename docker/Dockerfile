FROM openjdk:8-jdk-slim
ENV REPO_HOME=/home/service-discovery
RUN export JAVA_HOME && mkdir -p ${REPO_HOME}
COPY target/service-discovery-0.0.1.war ${REPO_HOME}
WORKDIR ${REPO_HOME}