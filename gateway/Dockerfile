FROM java:8-jdk

RUN mkdir /refund-manager
WORKDIR /refund-manager
COPY build/libs/gateway.jar /refund-manager
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/refund-manager/gateway.jar", "--spring.profiles.active=docker"]
EXPOSE 8072