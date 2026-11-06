Medical Inventory Management System Using Data Structures and Algorithms

1. Introduction

The Medical Inventory Management System is a C++-based application designed to manage and maintain medicine inventory efficiently. The project focuses on applying fundamental and advanced Data Structures and Algorithms (DSA) concepts to solve real-world inventory management problems.

The system provides functionalities for managing medicine records, monitoring stock availability, tracking expiry dates, processing transactions, and maintaining inventory records through file handling.

The primary objective is to demonstrate the practical implementation of data structures and in an inventory management environment.

2. Project Objectives

- Develop an efficient medicine inventory management application.
- Implement different data structures for storing and organizing medicine records.
- Maintain accurate medicine stock and batch information.
- Monitor medicine expiry dates and reduce inventory wastage.
- Implement efficient searching and sorting techniques.
- Manage medicine dispensing using the FEFO (First Expired, First Out) algorithm.
- Maintain transaction records using stack and queue operations.
- Ensure data persistence through file handling.

3. Core Functionalities

Medicine Management

- Add new medicine records.
- Update existing medicine information.
- Delete medicine records.
- Display complete medicine inventory.
- Search medicines using unique identifiers or names.

Inventory Management

- Maintain medicine quantities and stock availability.
- Generate low-stock notifications.
- Calculate total inventory value.
- Update stock automatically after transactions.

Expiry Management

- Maintain batch-wise expiry information.
- Identify expired medicines.
- Detect medicines approaching their expiry dates.
- Prioritize medicine dispensing based on expiry dates.

Transaction Management

- Process medicine purchase and sales transactions.
- Maintain transaction history.
- Manage pending customer orders.
- Update inventory after successful transactions.

Alternative Medicine Management

- Maintain predefined relationships between alternative medicines.
- Apply graph traversal using Breadth-First Search (BFS).
- Identify available alternatives when a particular medicine is out of stock.

Alternative medicine suggestions are informational and require verification by a qualified pharmacist.

4. Data Structures and Algorithms

The project incorporates the following data structures and algorithms:

Data Structure / Algorithm| Application
Arrays| Basic medicine record storage
Linked Lists| Dynamic medicine batch management
Hash Tables| Efficient medicine searching
Min Heap| Expiry date prioritization
Queue| Customer order management
Stack| Recent transaction management
Graph| Medicine alternative relationships
BFS| Alternative medicine traversal
Sorting Algorithms| Organizing medicine records
Binary Search| Searching sorted medicine records
FEFO Algorithm| Expiry-based medicine dispensing

All major data structures are intended to be implemented manually to demonstrate their internal working and operations without relying on STL containers.

5. Technology Stack

Component| Technology
Programming Language| C++
Development Environment| Visual Studio Code
Compiler| GCC / MinGW
Data Management| File Handling
Core Concepts| Data Structures and Algorithms
Application Interface| Console-Based Interface

6. System Architecture

The application is divided into the following modules:

1. Medicine Management Module
2. Inventory and Stock Management Module
3. Expiry Tracking Module
4. Medicine Dispensing Module
5. Transaction Management Module
6. Alternative Medicine Module
7. File Handling and Data Persistence Module

Each module is designed to perform a specific operation while maintaining coordination with the overall inventory management system.

7. Project Directory Structure

Medical-Inventory-System/
│
├── main.cpp
│
├── medicine.h
├── medicine.cpp
│
├── linkedlist.h
├── linkedlist.cpp
│
├── hashtable.h
├── hashtable.cpp
│
├── minheap.h
├── minheap.cpp
│
├── queue.h
├── queue.cpp
│
├── stack.h
├── stack.cpp
│
├── graph.h
├── graph.cpp
│
├── data/
│   ├── medicine.dat
│   └── transactions.dat
│
└── README.md

8. Installation and Execution

Prerequisites

- C++ compiler (GCC or MinGW).
- Visual Studio Code or any compatible C++ IDE.
- Basic understanding of C++ programming.

Step 1: Clone the Repository

git clone https://github.com/your-username/Medical-Inventory-System.git

Step 2: Navigate to the Project Directory

cd Medical-Inventory-System

Step 3: Compile the Application

g++ main.cpp medicine.cpp linkedlist.cpp hashtable.cpp minheap.cpp queue.cpp stack.cpp graph.cpp -o medical_inventory

Step 4: Execute the Application

Windows:

medical_inventory.exe

Linux / macOS:

./medical_inventory

Note: Update the compilation command according to the actual source files included in the project.

9. File Handling and Data Persistence

The application uses file handling to maintain medicine and transaction records.

The system is designed to:

- Store medicine information in data files.
- Retrieve existing records during application startup.
- Update records after inventory operations.
- Maintain transaction information.
- Preserve data between application executions.

10. Future Enhancements

The project can be extended with the following features:

- Graphical User Interface.
- Barcode-based medicine identification.
- Supplier and purchase management.
- Automated inventory replenishment.
- Advanced inventory analytics.
- Role-based access control.
- Detailed sales and stock reports.
- Database integration.

11. Learning Outcomes

This project provides practical exposure to:

- Implementation of linear and non-linear data structures.
- Searching and sorting algorithms.
- Hashing and collision handling.
- Priority queue implementation using heaps.
- Graph representation and traversal.
- Stack and queue operations.
- File handling and data persistence.
- Application of DSA in real-world problem solving.

12. Project Scope and Limitations

This application is primarily intended for academic and educational purposes. It demonstrates the use of data structures and algorithms in medical inventory management.

The initial implementation focuses on local data storage using file handling rather than a centralized database. The system does not replace professional pharmacy management software or provide medical recommendations.

13. License

This project is developed for educational purposes. The source code may be modified and extended for learning and academic use.
