# test-repo

A simple Hello World application built with Maven.

## Prerequisites

- Java 17 or higher
- Maven 3.x

## Building the Project

To compile the project:

```bash
mvn compile
```

To package the application as a JAR:

```bash
mvn package
```

## Running the Application

After building, you can run the application with:

```bash
java -jar target/hello-world-1.0-SNAPSHOT.jar
```

Expected output:
```
Hello World!
```

## Project Structure

```
.
├── pom.xml                              # Maven build configuration
└── src/main/java/com/example/
    └── HelloWorld.java                  # Main application class
```