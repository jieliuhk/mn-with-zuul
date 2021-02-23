FROM openjdk:14-alpine
COPY build/libs/io.hashimati.offersservice-*-all.jar OffersService.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "OffersService.jar"]