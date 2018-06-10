FROM java:8-jdk

ADD build/libs/authorized-client-service.jar /refund-manager-app

ENTRYPOINT ["java", "-jar", "/refund-manager-app/authorized-client-service.jar"]

EXPOSE 8073