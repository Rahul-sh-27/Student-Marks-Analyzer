Student Marks Analyzer

Student Marks Analyzer is a Java Swing desktop application designed to manage and analyze student academic records through a clean, interactive GUI. The application allows entry of student details, subject-wise marks, and provides automated reports, search, and deletion functionalities.

Features

Student Management: Add, search, and delete student records using Name and USN.

Marks Entry & Analysis: Record marks for multiple subjects (Cloud Computing, Machine Learning, Advanced Java, Open Elective, DevOps) and generate detailed reports with averages, highest/lowest marks.

Interactive GUI: Modern form-based interface using Java Swing with GridBagLayout, scrollable output, and dialog-based interactions.

Validation & Reliability: Prevents empty inputs, ensures marks are valid integers, and handles errors gracefully.

Technology Stack

Programming Language: Java

GUI Framework: Java Swing

Data Structures: ArrayList, LinkedHashMap

IDE/Platform: VS Code / IntelliJ / Eclipse | Windows / Linux

How it Works

User enters Name, USN, and subject-wise marks.

Click Add Student to store validated data in memory.

Click Show Report to display all student details with computed statistics.

Search or Delete student records by USN.

Results and reports are dynamically displayed in the GUI output area.

Installation & Execution

Prerequisites: Java Development Kit (JDK) 8 or higher, any Java-supported IDE or VS Code.

Steps:

# Compile the program
javac StudentAnalyzerUI.java

# Run the application
java StudentAnalyzerUI


Ensure the file name matches the public class name: StudentAnalyzerUI.java.

Learning Outcomes

Hands-on experience with Java Swing GUI development and event-driven programming.

Strong understanding of OOP concepts (encapsulation, modular design).

Practical use of Java Collections (ArrayList, LinkedHashMap) for data management.

Experience in building user-friendly, maintainable desktop applications.

Limitations

Data is stored in memory (no database persistence).

Designed for single-user desktop usage.

No file import/export functionality.
