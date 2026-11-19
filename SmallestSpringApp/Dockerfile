FROM eclipse-temurin:21-jre

WORKDIR /app

COPY target/example.smallest-0.0.1-SNAPSHOT.jar app.jar

EXPOSE 8011

CMD ["java", "--add-opens", "java.base/java.lang=ALL-UNNAMED", "-jar", "app.jar"]
