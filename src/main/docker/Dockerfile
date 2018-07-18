FROM openjdk

VOLUME /tmp
ADD maven/spring-boot-docker-1.0.0-Beta.jar myapp.jar
RUN sh -c 'touch /myapp.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/myapp.jar"]
