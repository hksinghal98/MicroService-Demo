FROM openjdk:11
ADD ./target/user-services-0.0.1-SNAPSHOT.jar /usr/src/user-services-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "user-services-0.0.1-SNAPSHOT.jar"]