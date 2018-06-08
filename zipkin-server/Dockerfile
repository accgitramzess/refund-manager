FROM java:8-jdk

ADD build/libs/zipkin-server.jar /refund-manager-app

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/zipkin-server.jar" ]

EXPOSE 8070