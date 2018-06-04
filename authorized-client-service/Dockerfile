FROM java:8-jdk

RUN mkdir /refund-manager
WORKDIR /refund-manager
COPY build/libs/authorized-client-service.jar /refund-manager
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/refund-manager/authorized-client-service.jar", "--spring.profiles.active=docker"]
EXPOSE 8073