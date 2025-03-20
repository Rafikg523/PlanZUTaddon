FROM eclipse-temurin:21-jdk-jammy

WORKDIR /app
COPY data/Plan_ZUT-1.0-SNAPSHOT.jar app.jar
COPY run.sh /run.sh

RUN chmod +x /run.sh

CMD ["/run.sh"]
