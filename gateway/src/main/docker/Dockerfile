FROM java:8
VOLUME /tmp
ADD gateway.jar gateway.jar
RUN bash -c 'touch /gateway.jar'
EXPOSE 80
ENTRYPOINT ["java","-Duser.timezone=GMT+08","-Djava.security.egd=file:/dev/./urandom","-jar","/gateway.jar"]
