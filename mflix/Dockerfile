# base image of mflix container
FROM java:8

# port number the container exposes
EXPOSE 50000

# make the jar file available in the container image
COPY mflix-1.0-SNAPSHOT.jar ./mflix-1.0-SNAPSHOT.jar

# application run command
CMD ["java", "-jar", "./mflix-1.0-SNAPSHOT.jar"]
