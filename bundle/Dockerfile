FROM openjdk:17
ADD springboot-eks.jar springboot-eks.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","springboot-eks.jar"]

#use this command--> docker build --provenance false -t spring-exception .