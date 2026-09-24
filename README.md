OOP with C++ — All 18 Real-Time Applications
# Object Oriented Programming with C++
## Practical Programs – Unit III

### Student Information

| Field | Details |
|---------|---------|
| Student Name | Shravani Thakur |
| PRN | 125UAD1098 |
| Class/Division | SY.Btech / A |
| Course Name | Object Oriented Programming using C++ |
| Unit | Unit III – Operator Overloading & Polymorphism |

Overview

This repository contains 18 C++ programs organized into six units, with three real-time applications in each unit. The programs demonstrate Object-Oriented Programming concepts and their application to practical software systems.

The collection progresses from fundamental class-based programming and static members to inheritance, polymorphism, operator overloading, file handling, exception handling, templates, STL containers, algorithms, and data analytics.

The repository contains:

18 individual C++ source files

1 combined C++ source file containing all 18 programs

Unit-wise organization

Real-world application examples

C++17-compatible implementations

Unit-wise Program List

Unit I — Classes, Objects and Basic OOP

1. Smart Agriculture Sensor Monitor

File: Unit_1_Program_1_Smart_Agriculture_Sensor_Monitor.cpp

Demonstrates a simple sensor-monitoring system using a SoilSensor class. The application stores sensor IDs, moisture readings, and timestamps, displays readings for multiple sensors, and updates a sensor reading.

Concepts:

Classes and objects

Encapsulation

Constructors

Member functions

vector of objects

2. Student Attendance Management System

File: Unit_1_Program_2_Student_Attendance_Management_System.cpp

Implements a student attendance system that records total attendance days and present days and calculates attendance percentages.

Concepts:

Classes and objects

Data members

Encapsulation

Constructors

Member functions

Percentage calculation

3. E-Commerce Product Catalog

File: Unit_1_Program_3_E_Commerce_Product_Catalog.cpp

Models products in an online catalog. Each product stores an ID, name, price, and stock quantity. A static member tracks the total number of active product objects.

Concepts:

Classes and objects

Constructors and destructors

Static data members

Static member functions

Inline functions

Encapsulation

Unit II — Inheritance and Runtime Polymorphism

4. Employee Payroll System

File: Unit_2_Program_4_Employee_Payroll_System.cpp

Provides a payroll model with an abstract Employee base class and different employee types such as full-time and part-time employees. Salary calculation is performed through overridden virtual functions.

Concepts:

Inheritance

Abstract classes

Pure virtual functions

Runtime polymorphism

Function overriding

Virtual destructors

5. Digital Payment Gateway

File: Unit_2_Program_5_Digital_Payment_Gateway.cpp

Models a payment gateway supporting different payment methods, including credit-card and UPI payments. A common payment interface is used to process different transaction types.

Concepts:

Abstract classes

Inheritance

Runtime polymorphism

Virtual functions

Smart pointers

STL vectors

6. Vehicle Fleet Management

File: Unit_2_Program_6_Vehicle_Fleet_Management.cpp

Demonstrates management of different vehicle types in a fleet. Vehicles contain identification, registration, and fuel information, while derived classes provide specialized information.

Concepts:

Inheritance

Polymorphism

Method overriding

Encapsulation

vector

Smart pointers

Unit III — Operator Overloading and Compile-Time Polymorphism

7. CAD Shape Drawing System

File: Unit_3_Program_7_CAD_Shape_Drawing_System.cpp

Implements a simplified CAD-style drawing system. Shapes such as circles, rectangles, and triangles implement common operations such as area calculation and drawing.

Concepts:

Abstract classes

Pure virtual functions

Runtime polymorphism

Inheritance

STL vectors

Smart pointers

8. Complex Number Calculator

File: Unit_3_Program_8_Complex_Number_Calculator.cpp

Implements arithmetic operations on complex numbers using overloaded operators.

Supported operations include:

Addition

Subtraction

Multiplication

Equality comparison

Concepts:

Operator overloading

Classes and objects

Encapsulation

Binary operators

9. Input Validation Service

File: Unit_3_Program_9_Input_Validation_Service.cpp

Provides a reusable validation service for different input types. The same validate() function name is overloaded for marks, monetary amounts, and names.

Concepts:

Function overloading

Compile-time polymorphism

String processing

Input validation

Unit IV — File Handling and Persistence

10. Student Record File System

File: Unit_4_Program_10_Student_Record_File_System.cpp

Stores student records in a text file and reads them back for display. Student information is serialized into comma-separated records and reconstructed when reading the file.

Concepts:

File handling

ofstream

ifstream

String streams

Text file storage

Serialization-style record handling

11. Server Log Analyzer

File: Unit_4_Program_11_Server_Log_Analyzer.cpp

Creates and analyzes a sample server log file. It reads log entries and identifies records containing ERROR or CRITICAL messages.

Concepts:

File input/output

Text file processing

String searching

STL vectors

Log analysis

12. Binary File for Fixed-Size Records

File: Unit_4_Program_12_Binary_File_for_Fixed_Size_Records.cpp

Demonstrates storing fixed-size image metadata records in a binary file and reading them back.

Concepts:

Binary file handling

ofstream

ifstream

ios::binary

Fixed-size records

Raw memory serialization

Unit V — Exceptions and Templates

13. Secure Banking Transaction Module

File: Unit_5_Program_13_Secure_Banking_Transaction_Module.cpp

Implements a bank account system with exception handling. It defines a custom insufficient-funds exception and validates account operations such as deposits and withdrawals.

Concepts:

Exception handling

Custom exceptions

try, catch, and throw

std::exception

std::invalid_argument

std::runtime_error

14. Generic Sorting Service

File: Unit_5_Program_14_Generic_Sorting_Service.cpp

Provides a generic sorting function using C++ templates. The same sorting logic can operate on integers, floating-point values, and strings.

Concepts:

Function templates

Generic programming

STL vectors

Comparison operators

Reusable algorithms

15. Template-Based Stack

File: Unit_5_Program_15_Template_Based_Stack.cpp

Implements a generic stack data structure using a class template. The stack supports push, pop, empty-checking, and display operations and handles overflow and underflow conditions through exceptions.

Concepts:

Class templates

Dynamic memory

Stack data structure

Constructors and destructors

Exception handling

Resource management

Unit VI — STL, Algorithms and Data Analytics

16. Employee Directory and Salary Lookup

File: Unit_6_Program_16_Employee_Directory_and_Salary_Lookup.cpp

Maintains employee records and creates a salary lookup using map. Employees can also be sorted according to age using the STL sorting algorithm.

Concepts:

STL vector

STL map

sort()

Lambda expressions

Searching and lookup

Data organization

17. Web Server Log Analysis

File: Unit_6_Program_17_Web_Server_Log_Analysis.cpp

Analyzes web-server request records and counts requests made by different IP addresses. The results are ranked to identify request activity.

Concepts:

STL vector

STL map

pair

Sorting

Lambda expressions

Frequency analysis

18. Student Grade Analytics

File: Unit_6_Program_18_Student_Grade_Analytics.cpp

Analyzes student marks using STL algorithms and containers. The application calculates average, minimum, maximum, sorted marks, top performers, and unique marks.

Concepts:

vector

set

priority_queue

accumulate()

min_element()

max_element()

sort()

Data analysis

Concepts Covered Across All Units

Unit

Major Concepts

Unit I

Classes, Objects, Encapsulation, Constructors, Destructors, Static Members

Unit II

Inheritance, Abstract Classes, Virtual Functions, Runtime Polymorphism

Unit III

Operator Overloading, Function Overloading, Compile-Time Polymorphism

Unit IV

Text Files, Binary Files, File Streams, Record Processing

Unit V

Exception Handling, Custom Exceptions, Function Templates, Class Templates

Unit VI

STL, Maps, Vectors, Sets, Priority Queues, Algorithms, Lambda Expressions

Project Structure

OOP_CPP_All_Units_Real_Time_Applications/
│
├── README.md
├── ALL_18_PROGRAMS_COMBINED.cpp
│
└── Individual_Programs/
    ├── Unit_1_Program_1_Smart_Agriculture_Sensor_Monitor.cpp
    ├── Unit_1_Program_2_Student_Attendance_Management_System.cpp
    ├── Unit_1_Program_3_E_Commerce_Product_Catalog.cpp
    │
    ├── Unit_2_Program_4_Employee_Payroll_System.cpp
    ├── Unit_2_Program_5_Digital_Payment_Gateway.cpp
    ├── Unit_2_Program_6_Vehicle_Fleet_Management.cpp
    │
    ├── Unit_3_Program_7_CAD_Shape_Drawing_System.cpp
    ├── Unit_3_Program_8_Complex_Number_Calculator.cpp
    ├── Unit_3_Program_9_Input_Validation_Service.cpp
    │
    ├── Unit_4_Program_10_Student_Record_File_System.cpp
    ├── Unit_4_Program_11_Server_Log_Analyzer.cpp
    ├── Unit_4_Program_12_Binary_File_for_Fixed_Size_Records.cpp
    │
    ├── Unit_5_Program_13_Secure_Banking_Transaction_Module.cpp
    ├── Unit_5_Program_14_Generic_Sorting_Service.cpp
    ├── Unit_5_Program_15_Template_Based_Stack.cpp
    │
    ├── Unit_6_Program_16_Employee_Directory_and_Salary_Lookup.cpp
    ├── Unit_6_Program_17_Web_Server_Log_Analysis.cpp
    └── Unit_6_Program_18_Student_Grade_Analytics.cpp

Compilation Requirements

The programs use modern C++ features and are intended to be compiled with C++17 or later.

Requirements

GCC / G++

Clang++

Microsoft Visual C++

C++17-compatible compiler

Compile an Individual Program

Linux / macOS:

g++ -std=c++17 "filename.cpp" -o program
./program

Windows PowerShell:

g++ -std=c++17 "filename.cpp" -o program.exe
.\program.exe

Compile the Complete Combined Program

g++ -std=c++17 ALL_18_PROGRAMS_COMBINED.cpp -o all_programs

Windows PowerShell:

g++ -std=c++17 .\ALL_18_PROGRAMS_COMBINED.cpp -o all_programs.exe
.\all_programs.exe

Note: The combined source contains all 18 applications. Individual source files are recommended when you want to study or execute one application independently.

Learning Objectives

After completing these programs, a student should be able to:

Design classes and objects for real-world entities.

Apply encapsulation to protect object data.

Use constructors, destructors, static members, and member functions.

Implement inheritance and abstract interfaces.

Apply compile-time and runtime polymorphism.

Overload operators for user-defined data types.

Read and write text and binary files.

Handle runtime errors using exceptions.

Create reusable generic functions and classes using templates.

Use STL containers for practical data-management tasks.

Apply STL algorithms to sorting, searching, aggregation, and analysis.

Develop small real-time applications using multiple OOP concepts together.

Real-World Applications

The 18 examples connect OOP concepts to practical software domains including:

Smart agriculture

Student management

E-commerce

Employee payroll

Digital payments

Fleet management

CAD systems

Mathematical calculators

Input validation

File-based student records

Server monitoring

Binary data storage

Banking systems

Generic data processing

Stack data structures

Employee directories

Web-server analytics

Student performance analytics

Conclusion

This project provides a unit-wise collection of 18 real-time C++ applications that demonstrate the progression from basic object-oriented programming to advanced C++ programming techniques.

The examples combine OOP principles with practical programming tools such as:

Inheritance and polymorphism

Operator and function overloading

File handling

Exception handling

Templates

STL containers

STL algorithms

Lambda expressions

Data analysis

Together, these programs provide practical experience in designing and implementing C++ solutions for real-world-style problems.

Student Information

Field

Details
