
---

#Campus Course & Records Manager (CCRM)

GitHub Repository

Overview

Campus Course & Records Manager (CCRM) is a modular Java SE command-line application for managing academic records in educational institutes. 

Features

Student Management: Add, list, update, deactivate students; enroll/unenroll in courses.

Course Management: Add, list, update, deactivate courses; assign instructors; search/filter courses.

Grades & Transcripts: Record grades, compute GPA, generate transcripts, and display top students.

File Utilities: Import/export CSV data, backup/archive, recursive directory operations.

CLI Navigation: Menu-driven interface for all operations.



---

Technical Highlights

Java Version: 17+

OOP Principles: Encapsulation, Inheritance, Abstraction, Polymorphism

Advanced Features: Lambdas, Streams, Functional Interfaces

Design Patterns: Singleton (AppConfig), Builder (Course.Builder)

File Handling: Java NIO.2 for import/export and backups

Date/Time API: Modern handling of academic dates

Exception Handling: Custom exceptions like DuplicateEnrollmentException, MaxCreditLimitExceededException

Recursion Utilities: Directory scanning and file operations

Assertions & Validation: Runtime checks enabled with -ea



---

Project Structure

Java-VITyarthi/
├── .gitignore
├── README.md
├── USAGE.md
├── test-data/
└── src/
    └── edu/
        └── ccrm/
            ├── cli/
            ├── config/
            ├── domain/
            ├── exceptions/
            ├── service/
            └── util/

---

Sample CSV Formats

students.csv

regNo,fullName,email
2025001,John Smith,john.smith@email.com
2025002,Emily Johnson,emily.johnson@email.com

courses.csv

code,title,credits,semester,department
CS101,Introduction to Programming,3,FALL,Computer Science


---

Setup & Run

Install Java 17+

Download from AdoptOpenJDK

Verify installation:


java -version

Clone Repository

git clone https://github.com/poonamgupta17/Java-VITyarthi.git
cd Java-VITyarthi

Compile & Run

javac -d out src/edu/ccrm/cli/MainMenu.java
java -cp out edu.ccrm.cli.MainMenu

> Or use IntelliJ IDEA/Eclipse "Run" action on MainMenu.java.



Enable Assertions (Optional)

java -ea -cp out edu.ccrm.cli.MainMenu


---

Usage Flow

1. Launch CLI menu.


2. Navigate options: Students → Courses → Enrollments/Grades → File Operations → Backup → Reports.


3. Perform CRUD operations, import/export CSV, generate transcripts, or view GPA distribution.


4. Exit to save changes.




---

Author

Poonam Gupta

Email: poonam.24bce1011@vitbhopal.ac.in

Institution: VIT Bhopal

GitHub: poonamgupta17


> This project is individual work following VIT’s honor code. All code and documentation are original unless cited.




---
