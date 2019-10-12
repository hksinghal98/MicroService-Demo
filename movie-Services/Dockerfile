FROM openjdk:11
ADD ./target/movie-service-1.0.0.jar /usr/src/movie-service-1.0.0.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "movie-service-1.0.0.jar"]