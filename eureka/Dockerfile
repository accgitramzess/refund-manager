FROM java:8-jdk

ADD build/libs/eureka-server.jar /refund-manager-app

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/eureka-server.jar" ]

EXPOSE 8761