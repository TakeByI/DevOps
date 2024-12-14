FROM openjdk:23-jdk

WORKDIR /app

# Копируем только необходимый JAR-файл из директории Backend
COPY devops/Backend/frontend-backend-0.0.1-SNAPSHOT.jar ./
COPY devops/Backend/data.txt ./

# Запуск JAR-файла
CMD ["java", "-Dspring.profiles.active=backend", "-jar", "frontend-backend-0.0.1-SNAPSHOT.jar"]
