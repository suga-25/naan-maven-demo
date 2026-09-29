# Naan Mudhalvan - Java Build Automation and Project Management using Apache Maven

A professional Java application template built as part of the **Naan Mudhalvan** skilling initiative to demonstrate project configuration, automated unit testing, and artifact packaging using Java 11 and Apache Maven.

**Project Overview**

This project serves as a hands-on demonstration of:

• Build Automation: Compiling and packaging Java applications cleanly using Apache Maven.

• Dependency & Property Management: Configuring Java compiler versions and dependencies via pom.xml.

• Automated Unit Testing: Running and validating tests seamlessly with JUnit and the Maven Surefire Plugin.

**Prerequisites**

Ensure you have the following installed in your environment:

• Java Development Kit (JDK) 11

• Apache Maven

**How to Build, Test, and Run**

1. **Clone the Repository:** git clone [https://github.com/suga-25/naan-maven-demo.git](https://github.com/suga-25/naan-maven-demo.git)
cd naan-maven-demo

2. **Run Unit Tests:**
mvn clean test

3. **Package the Application into a JAR:**
mvn clean package

4. **Execute the Compiled Application:**
java -cp target/naan-maven-demo-1.0-SNAPSHOT.jar com.example.App

**Author**
Name: https://github.com/suga-25
