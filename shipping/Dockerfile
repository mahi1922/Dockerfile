FROM maven
WORKDIR /app
COPY pom.xml .
COPY src ./src
RUN mvn clean package && \
    mv target/shipping-1.0.jar shipping.jar
EXPOSE 8080
CMD ["java", "-jar", "shipping.jar"]
