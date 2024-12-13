FROM openjdk:23-jdk
WORKDIR /app
COPY . .
RUN ./mvnw package -DskipTests
CMD ["java", "-Dspring.profiles.active=frontend", "-jar", "target/frontend-backend-0.0.1-SNAPSHOT.jar"]