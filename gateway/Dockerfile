FROM java:8-jdk

ADD build/libs/gateway.jar /refund-manager-app

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/gateway.jar" ]

EXPOSE 8072