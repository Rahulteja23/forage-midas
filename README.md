# Midas Core – Java Developer Virtual Experience 🚀

This repository contains my work and progress for the **JPMorgan Chase & Co. Software Engineering Virtual Experience Program** through **Forage**. The project focuses on understanding real-world software engineering workflows using Java, Spring Boot, Maven, Kafka, and H2 database integration.

## 📌 Project Overview

The objective of this project is to gain hands-on experience with:

* Spring Boot application structure
* Java development setup
* Maven project management
* Dependency management
* Application configuration
* Testing and debugging workflows
* Real-world software engineering practices

---

## 🛠 Technologies Used

* Java 17
* Spring Boot 3.2.5
* Maven
* Apache Kafka
* H2 Database
* JPA (Java Persistence API)
* JUnit Testing

---

## ✅ Task 1 – Environment Setup and Project Initialization

### Completed Steps

### 1. Repository Setup

* Forked and cloned the project repository
* Configured local development environment

### 2. Java Installation and Configuration

* Installed Java 17
* Configured `JAVA_HOME`
* Verified installation using:

```bash
java -version
javac -version
```

### 3. IDE Setup

* Opened project in IntelliJ IDEA
* Imported project as Maven project
* Configured Java SDK

### 4. Codebase Exploration

Explored project structure:

```text
forage-midas
│
├── src
├── services
├── pom.xml
├── application.yml
├── README.md
└── .mvn
```

Reviewed:

* Source files
* Configuration files
* Existing scaffold classes
* Test files

---

### 5. Added Required Dependencies

Added and configured:

* Spring Boot Starter Web
* Spring Boot Data JPA
* Spring Kafka
* H2 Database
* Spring Boot Starter Test
* Kafka Test Dependencies
* Testcontainers Kafka

---

### 6. Updated Application Configuration

Configured:

```yaml
general:
  kafka-topic: trader-updates
```

---

### 7. Build and Run Project

Build command:

```bash
mvn clean install
```

Run application:

```bash
mvn spring-boot:run
```

---

### 8. Automated Test Execution

Executed Task 1 tests:

```bash
mvn -Dtest=TaskOneTests test
```

Result:

✅ Tests Passed Successfully
✅ Application Booted Successfully
✅ Build Successful

---

## 🎯 Learning Outcomes

Through this task I gained practical experience in:

* Setting up enterprise Java environments
* Understanding Spring Boot architecture
* Working with Maven dependencies
* Managing project configurations
* Running and interpreting automated tests
* Troubleshooting environment issues

---

## 🚀 Current Status

Task 1: ✅ Completed

Continuing with upcoming tasks in the JPMorgan Chase Software Engineering Virtual Experience Program.

---

### Author

**Rahul Teja**
B.Tech CSE (AI) Student
Passionate about Software Development, AI, and building real-world solutions.
