Architecture Decision Record (ADR) System

About the Project

The Architecture Decision Record (ADR) System is a console-based Java application used to document and manage architectural decisions in software projects. It stores decision details such as context, decision, status, and consequences using MongoDB.

Technologies Used

Java (JDK 11 or above)

MongoDB

MongoDB Java Driver

Command Line Interface (CLI)

Features

Create, view, update, and delete ADRs

List all ADRs

Search ADRs by title

Project Structure
Adr.java
AdrRepository.java
AdrService.java
Cli.java
Main.java

How to Run

Install and start MongoDB.

Open the project in a Java IDE.

Add MongoDB driver JAR files.

Run Main.java.

Use CLI commands to manage ADRs.

Commands

create – Create a new ADR

list – List all ADRs

view <id> – View ADR details

update <id> – Update an ADR

delete <id> – Delete an ADR

search <keyword> – Search ADRs

exit – Exit the application

Conclusion

This project provides a simple and effective way to record and manage architectural decisions, improving decision traceability and maintainability in software development.

<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/ed5eaa70-c6d8-4924-8439-9a73ed9e7b1e" />
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/7e9f78fe-2da7-4c64-ba7d-70a635ecb884" />

