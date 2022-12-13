# To build: docker build -t eclipse-temurin:17-jdk-jammy .
FROM openjdk:17

# add the compiled jar file
# ADD Main.class /
COPY Main.class /Main.class
# run the application
CMD ["java", "Main"]

