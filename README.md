# Hello World Java Project

This is a simple Java project that demonstrates the basic structure of a Java application. The project contains a single class that prints "Hello, World!" to the console.

## Project Structure

```
hello-world-java
├── src
│   └── main
│       └── java
│           └── com
│               └── example
│                   └── HelloWorld.java
├── .gitignore
├── pom.xml
└── README.md
```

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Apache Maven installed on your machine.

## Building the Project

To build the project, navigate to the project directory and run the following command:

```
mvn clean install
```

## Running the Application

After building the project, you can run the application using the following command:

```
mvn exec:java -Dexec.mainClass="com.example.HelloWorld"
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.