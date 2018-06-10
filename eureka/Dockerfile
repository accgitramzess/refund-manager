FROM java:8-jdk

ADD build/libs/eureka.jar /refund-manager-app

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/eureka.jar" ]

EXPOSE 8761