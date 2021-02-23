FROM openjdk:14-alpine
COPY build/libs/io.hashimati.requestsservice-*-all.jar RequestsService.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "RequestsService.jar"]