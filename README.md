# LAB_ASSIGN-_JAVA_5


📘 Student Management System (Java, OOP, File Handling, Exceptions)

This project is a console-based Student Management System built in Java.
It demonstrates the use of Object-Oriented Programming, Interfaces, Custom Exceptions, File I/O, Collections, Multithreading, and RandomAccessFile operations.

The system allows users to add, view, search, delete, update, and sort student records, with all data stored persistently in a text file.

✨ Features
✔ Object-Oriented Design

Uses abstract class Person

Extends into Student class with additional attributes

Uses interface RecordActions for CRUD operations

Demonstrates encapsulation, inheritance, and abstraction

✔ Student Operations

Add student

View all students

Search student by name

Delete student by name

Update student details by roll number

Sort students by marks (descending)

Display student grade (A/B/C/D based on marks)

✔ Exception Handling

Includes custom exceptions:

InvalidInputException

StudentNotFoundException

Handles:

Wrong number formats

Missing fields

Invalid marks

Duplicate roll numbers

✔ File Handling (Persistent Storage)

Stores all records in a text file named:

students.txt


Supports:

Saving student data in CSV format

Loading data at startup

Skipping invalid/broken records

RandomAccessFile demo (reads first record)

✔ Multithreading

Uses a Loader class with a separate thread to display:

Adding student...
Updating student...
Saving records...

Menu Option Overview


<img width="601" height="272" alt="image" src="https://github.com/user-attachments/assets/65a897bd-e5c6-4239-9036-1a2f542624e3" />


Sample Output


<img width="523" height="122" alt="image" src="https://github.com/user-attachments/assets/4ee32fa7-cbfc-4df3-99c9-da76848e1122" />




