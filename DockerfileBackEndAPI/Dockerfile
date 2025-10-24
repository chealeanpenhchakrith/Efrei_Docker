FROM openjdk:17-jdk-slim

WORKDIR /app
COPY Main.java .

# Compile the Java source
RUN javac Main.java

# Run the compiled class
CMD ["java", "Main"]