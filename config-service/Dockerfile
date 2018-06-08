FROM java:8-jdk

# RUN mkdir /refund-manager-app

# The `WORKDIR` line specifies a new default directory within the image's file system.
# The COPY and ADD instructions allow you to copy files into your image's filesystem.
#WORKDIR /refund-manager-app

# copy the jar to docker container
#COPY build/libs/config-service.jar /refund-manager-app

ADD build/libs/config-service.jar /refund-manager-app

# ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/refund-manager-app/config-service.jar", "--spring.profiles.active=docker"]

# -Djava.security.egd=file:/dev/./urandom - ???? WHAT IS IT ??????
# --spring.profiles.active=docker - ????? WHAT IS IT ??????

ENTRYPOINT [ "java", "-jar", "/refund-manager-app/config-service.jar" ]

EXPOSE 8888