FROM java:8-jdk

ADD build/libs/auth-service.jar /refund-manager-app

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/auth-service.jar" ]

EXPOSE 8071