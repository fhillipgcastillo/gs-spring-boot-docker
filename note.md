
to execute with gradle
./gradlew build && java -jar build/libs/gs-spring-boot-docker-0.1.0.jar

installing with mbnw and build
./mvnw install dockerfile:build

Using Spring Profiles
Running your freshly minted Docker image with Spring profiles is as easy as passing an environment variable to the Docker run command

$ docker run -e "SPRING_PROFILES_ACTIVE=prod" -p 8080:8080 -t springio/gs-spring-boot-docker