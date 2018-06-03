FROM java:8-jdk

RUN mkdir /refund-manager
WORKDIR /refund-manager
COPY build/libs/com.auth.server.api.config-server.jar /refund-manager
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/refund-manager/com.auth.server.api.config-server.jar", "--spring.profiles.active=docker"]
EXPOSE 8070