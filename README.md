# Campus Course & Records Manager (CCRM)

A comprehensive Java console application for managing students, courses,
enrollments, and grades in an educational institution.

------------------------------------------------------------------------

## 📋 Project Overview

CCRM is a Java SE application that provides a complete solution for
managing academic records, including: - Student information - Course
catalog - Enrollment management - Grade tracking - Data persistence

------------------------------------------------------------------------

## 🚀 Features

-   **Student Management**: Create, update, list, and deactivate student
    records\
-   **Course Management**: Manage courses with credits, instructors, and
    departments\
-   **Enrollment System**: Enroll/unenroll students with credit limit
    validation\
-   **Grading System**: Record marks and compute GPA with letter grades\
-   **File Operations**: Import/export CSV data and backup
    functionality\
-   **Reporting**: Generate transcripts and academic reports

------------------------------------------------------------------------

## 🛠️ Technical Requirements

-   Java JDK 17+\
-   Eclipse IDE (recommended) or any Java IDE\
-   Windows/Linux/macOS operating system

------------------------------------------------------------------------

## 📦 Installation & Setup

### 1. Install Java JDK

-   Download JDK 17+ from Oracle's website\
-   Run the installer and follow installation steps\
-   Set environment variables:
    -   `JAVA_HOME`: Path to JDK installation directory\
    -   Add `%JAVA_HOME%\bin` to PATH variable

**Verification:**

``` bash
java -version
javac -version
```

------------------------------------------------------------------------

### 2. Eclipse IDE Setup

-   Download and install Eclipse IDE\
-   Create new Java project:
    -   File → New → Java Project\
    -   Project name: `CCRM`\
    -   Use JRE 17+\
-   Import source code into the project structure\
-   Enable assertions:
    -   Right-click project → Properties → Run/Debug Settings\
    -   Edit configuration → Arguments → VM arguments: `-ea`

------------------------------------------------------------------------

### 3. Project Structure

    CCRM/
    ├── src/
    │   └── edu/
    │       └── ccrn/
    │           ├── cli/           # Command-line interface
    │           ├── config/        # Configuration classes
    │           ├── domain/        # Entity classes
    │           ├── exception/     # Custom exceptions
    │           ├── io/            # File operations
    │           ├── service/       # Business logic
    │           ├── util/          # Utilities
    │           └── Main.java      # Entry point
    ├── test-data/                 # Sample CSV files
    ├── backups/                   # Automated backups
    ├── screenshots/               # Documentation images
    └── README.md

------------------------------------------------------------------------

## 🎯 How to Run

### Using Eclipse:

1.  Open the project in Eclipse\
2.  Right-click on `Main.java`\
3.  Select **Run As → Java Application**

### Using Command Line:

``` bash
# Compile the project
javac -d bin src/edu/ccrm/*.java src/edu/ccrm/**/*.java

# Run the application
java -cp bin -ea edu.ccrm.Main
```

------------------------------------------------------------------------

## 📊 Sample Data

The application includes sample CSV files in the **test-data/**
directory: - `students.csv` - Sample student records\
- `courses.csv` - Course catalog with department information\
- `instructors.csv` - Faculty members by department

------------------------------------------------------------------------

## 🎮 Usage Guide

**Main Menu Options:** - Manage Students → Add, update, list, and search
students\
- Manage Courses → Course catalog management\
- Manage Enrollments → Student course registration\
- Manage Grades → Record and view academic performance\
- Import/Export Data → CSV file operations\
- Backup Operations → Data backup and restoration\
- Generate Reports → Academic transcripts and statistics\
- Java Platform Info → Technical information

**Key Operations:** - Enroll Students: Maximum **18 credits per
semester** enforced\
- GPA Calculation: Automatic GPA computation with letter grades\
- Data Persistence: Export to CSV format for external use\
- Backup System: Timestamped automatic backups

------------------------------------------------------------------------

## 📚 Java Evolution Timeline

-   **1995**: Java 1.0 released by Sun Microsystems\
-   **1997**: Java 1.1 with JDBC and RMI\
-   **2004**: Java 5 with generics, annotations, autoboxing\
-   **2014**: Java 8 with lambdas and Stream API\
-   **2017**: Java 9 with module system\
-   **2018**: Java 11 LTS release\
-   **2021**: Java 17 LTS (current stable version)\
-   **2023**: Java 21 LTS with virtual threads

------------------------------------------------------------------------

## ⚖️ Java Platform Comparison

  -------------------------------------------------------------------------------
  Aspect           Java ME              Java SE              Java EE (Enterprise
                   (Embedded/Mobile)    (Desktop/Server)     Web)
  ---------------- -------------------- -------------------- --------------------
  **Target**       IoT devices          General purpose      Large-scale apps

  **Scope**        Limited API          Standard API         Extended API

  **Use Case**     IoT, small devices   General              Enterprise
                                        desktop/server       applications

  **Deployment**   Small devices        JVM-based            Application servers

  **Libraries**    Minimal              Comprehensive        Enterprise-focused
  -------------------------------------------------------------------------------

------------------------------------------------------------------------

## 🏗️ Java Architecture

### JDK (Java Development Kit)

-   **Purpose**: Development environment for Java applications\
-   **Components**: Compiler (`javac`), tools, libraries, JRE\
-   **Usage**: Developers use JDK to create Java applications

### JRE (Java Runtime Environment)

-   **Purpose**: Runtime environment for executing Java applications\
-   **Components**: JVM, class libraries, supporting files\
-   **Usage**: End-users need JRE to run Java applications

### JVM (Java Virtual Machine)

-   **Purpose**: Execute Java bytecode, provide platform independence\
-   **Function**: Just-In-Time compilation, memory management\
-   **Feature**: *"Write once, run anywhere"* capability

**Interaction Flow:** 1. Developer writes Java code (`.java` files)\
2. JDK compiles code to bytecode (`.class` files)\
3. JRE loads bytecode into JVM\
4. JVM executes bytecode on target platform

------------------------------------------------------------------------

## 🧪 Enabling Assertions

Assertions are enabled using the `-ea` flag:

``` bash
# Command line
java -ea -cp bin edu.ccrm.Main
```

**Eclipse:** - VM arguments in Run Configuration → `-ea`

**Assertions are used for:** - Validating method preconditions\
- Checking invariant conditions\
- Ensuring non-null parameters\
- Credit limit validations

------------------------------------------------------------------------

## 📋 Syllabus Topic Mapping

  Java Topic              Implementation Location
  ----------------------- -------------------------------------
  OOP Principles          `domain/` package classes
  Inheritance             `Person → Student, Instructor`
  Polymorphism            `getDisplayInfo()` method
  Encapsulation           Private fields with getters/setters
  Exception Handling      `exception/` package
  File I/O (NIO.2)        `FileService` class
  Stream API              Search and filter operations
  Lambda Expressions      Comparators and predicates
  Design Patterns         Singleton, Builder patterns
  Collections Framework   `ArrayList`, `List` usage
  Date/Time API           `LocalDate` for timestamps
  Enums                   Semester, Grade enumerations

------------------------------------------------------------------------

## 👥 Development Team

-   **Course**: Java Programming\
-   **Project**: Campus Course & Records Manager\
-   **Version**: 1.0.0\
-   **Academic Integrity**: This project is developed for educational
    purposes following academic integrity guidelines.

------------------------------------------------------------------------

## 📞 Support

For technical issues or questions about the CCRM system, please refer to
the documentation or consult with the development team.

------------------------------------------------------------------------

## 📄 License

This project is developed for academic purposes as part of a Java
programming course.


## Daily Activity Log
- [2026-07-29 21:36:07] Automated activity update (1/10)
- [2026-07-29 21:36:10] Automated activity update (2/10)
- [2026-07-29 21:36:13] Automated activity update (3/10)
- [2026-07-29 21:36:17] Automated activity update (4/10)
- [2026-07-29 21:36:20] Automated activity update (5/10)
- [2026-07-29 21:36:28] Automated activity update (6/10)
- [2026-07-29 21:36:32] Automated activity update (7/10)
- [2026-07-29 21:36:35] Automated activity update (8/10)
- [2026-07-29 21:36:38] Automated activity update (9/10)
- [2026-07-29 21:36:42] Automated activity update (10/10)
- [2026-07-30 21:02:48] Automated activity update (1/10)
- [2026-07-30 21:02:54] Automated activity update (2/10)
- [2026-07-30 21:02:57] Automated activity update (3/10)
- [2026-07-30 21:03:06] Automated activity update (4/10)
- [2026-07-30 21:03:10] Automated activity update (5/10)
- [2026-07-30 21:03:13] Automated activity update (6/10)
- [2026-07-30 21:03:16] Automated activity update (7/10)
- [2026-07-30 21:03:19] Automated activity update (8/10)
- [2026-07-30 21:03:22] Automated activity update (9/10)
- [2026-07-30 21:03:25] Automated activity update (10/10)
- [2026-07-31 10:20:47] Automated activity update (1/10)
- [2026-07-31 10:20:50] Automated activity update (2/10)
- [2026-07-31 10:20:53] Automated activity update (3/10)
- [2026-07-31 10:20:56] Automated activity update (4/10)
- [2026-07-31 10:20:59] Automated activity update (5/10)
- [2026-07-31 10:21:02] Automated activity update (6/10)
- [2026-07-31 10:21:05] Automated activity update (7/10)
- [2026-07-31 10:21:08] Automated activity update (8/10)
- [2026-07-31 10:21:11] Automated activity update (9/10)
- [2026-07-31 10:21:14] Automated activity update (10/10)
- [2026-08-01 12:38:33] Automated activity update (1/10)
- [2026-08-01 12:38:36] Automated activity update (2/10)
- [2026-08-01 12:38:47] Automated activity update (3/10)
- [2026-08-01 12:38:52] Automated activity update (4/10)
- [2026-08-01 12:38:55] Automated activity update (5/10)
- [2026-08-01 12:38:58] Automated activity update (6/10)
- [2026-08-01 12:39:01] Automated activity update (7/10)
- [2026-08-01 12:39:04] Automated activity update (8/10)
- [2026-08-01 12:39:08] Automated activity update (9/10)
- [2026-08-01 12:39:11] Automated activity update (10/10)
- [2026-08-02 00:57:20] Automated activity update (1/10)
- [2026-08-02 00:57:23] Automated activity update (2/10)
- [2026-08-02 00:57:26] Automated activity update (3/10)
- [2026-08-02 00:57:29] Automated activity update (4/10)
