# Library Management System (Java Swing + JDBC)

A simple Library Management desktop app built with Java Swing and SQLite (JDBC).  
Features: add/edit/delete books & members, issue & return books, simple UI.

## Demo
![demo](images/demo.gif)

## Features
- Add / edit / delete books
- Add / edit / delete members
- Issue & return books with due date
- Search and view current issues

## Tech
- Java 11+
- Swing (GUI)
- SQLite (file `library.db`) via sqlite-jdbc

## Run (compile & run)
1. Put `sqlite-jdbc-<version>.jar` in `lib/` or add to your classpath.
2. Compile:
   ```bash
   javac -cp ".:lib/sqlite-jdbc-3.36.0.3.jar" -d out src/*.java
