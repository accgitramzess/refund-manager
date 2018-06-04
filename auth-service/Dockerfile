FROM java:8-jdk

RUN mkdir /refund-manager
WORKDIR /refund-manager
COPY build/libs/auth-service.jar /refund-manager
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/refund-manager/auth-service.jar", "--spring.profiles.active=docker"]
EXPOSE 8071