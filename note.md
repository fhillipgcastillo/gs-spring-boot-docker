## Resources
    https://spring.io/guides/gs/spring-boot-docker/
    https://github.com/palantir/gradle-docker
    

## Todo:
* Update this notes with the lastest changes

## To execute with gradle the project
* ./gradlew build 
* java -jar build/libs/gs-spring-boot-docker-0.1.0.jar

## installing with mbnw and build
./mvnw install dockerfile:build

## Running it up
docker run -p 8080:8080 -t springio/gs-spring-boot-docker

## Using Spring Profiles
Running your freshly minted Docker image with Spring profiles is as easy as passing an environment variable to the Docker run command

$ docker run -e "SPRING_PROFILES_ACTIVE=prod" -p 8080:8080 -t springio/gs-spring-boot-docker

## Run multiple projectrs /modules sources
* https://spring.io/guides/gs/multi-module/
* https://docs.gradle.org/current/userguide/gradle_wrapper.html
* https://github.com/spring-guides/gs-spring-boot-docker.git
