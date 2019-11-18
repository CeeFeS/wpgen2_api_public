FROM openjdk:8
ADD workpackgen2api.jar workpackgen2api.jar
COPY resources resources
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "workpackgen2api.jar"]
