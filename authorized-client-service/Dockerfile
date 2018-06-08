FROM java:8-jdk

ADD build/libs/authorized-client-service.jar /refund-manager

ENTRYPOINT ["java", "-jar", "/refund-manager/authorized-client-service.jar"]

EXPOSE 8073