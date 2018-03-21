FROM openjdk:8-jre-alpine

VOLUME /tmp

WORKDIR /opt/app

ADD build/libs/hello-0.1.0.jar app.jar
ADD tooling/docker/entrypoint entrypoint

ENTRYPOINT ["/opt/app/entrypoint"]
