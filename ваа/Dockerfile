FROM ubuntu:latest 
RUN apt-get update && apt-get install -y \
    openjdk-8-jre \
    x11-apps

COPY calc.jar /app/calc.jar

CMD ["java", "-jar", "/app/calc.jar"]
