Smart Queue Management System
1. Project Overview

The Smart Queue Management System is a Python-based terminal application designed to manage queues at college offices, canteens, clinics, and other service counters.

Traditional queues can result in long waiting times and difficulty in managing customers during busy periods. The proposed system provides a digital approach where users can generate a token, join a queue, track their position, and receive service in an organized manner.

The system also provides administrative functionality for managing the queue, calling the next customer, completing services, cancelling tokens, handling priority customers, and viewing basic queue statistics.

The project demonstrates Python programming and problem-solving concepts through queue data structures, priority-based queue management, modular programming, data processing, validation, and error handling.

2. Problem Statement

Long waiting times and unorganized queues at college offices, canteens, clinics, and service counters create inconvenience for students and other users.

Traditional queue systems provide limited information about a user's position and waiting status and can become difficult for administrators to manage during busy periods.

The Smart Queue Management System aims to provide a terminal-based digital queue system where users can generate a token, join an appropriate queue, track their queue position, and receive service in an organized manner.

The system also allows administrators to manage waiting customers, call the next customer, complete or cancel services, handle priority customers, and view basic queue statistics.

3. Objectives

The main objectives of this project are:

To develop a simple digital queue management system using Python.
To generate unique tokens for users requesting different services.
To implement FIFO-based queue management for normal customers.
To implement priority-based queue handling.
To allow users to track their token and queue position.
To allow administrators to call, complete, and cancel customer services.
To provide basic statistics about the current queue.
To apply Python programming and problem-solving concepts to a real-world problem.
4. Key Features
4.1 Token Generation
Generates a unique token for every customer.
Allows the user to select the required service.
Supports normal and priority customers.
Stores basic customer information.
4.2 Queue Management
Maintains the current waiting queue.
Follows FIFO (First In, First Out) for normal customers.
Allows the administrator to call the next customer.
Allows the current service to be marked as completed.
Allows waiting tokens to be cancelled.
4.3 Token Tracking
Allows users to enter their token number.
Displays customer details.
Displays selected service.
Displays current token status.
Displays queue position for waiting customers.
4.4 Queue Analytics

The system provides basic information such as:

Total tokens generated.
Number of customers waiting.
Number of customers currently being served.
Number of completed services.
Number of cancelled tokens.
5. Functional Requirements

The project is divided into the following major functional modules:

Module 1: Token Generation

The system shall allow users to:

Enter their name.
Select a service.
Select normal or priority service.
Generate a unique token.
Module 2: Queue Management

The system shall allow administrators to:

View the current queue.
Call the next customer.
Complete the current service.
Cancel a waiting token.
Module 3: Token Tracking

The system shall allow users to:

Search for a token.
View its current status.
View the queue position when applicable.
Module 4: Queue Analytics

The system shall calculate and display:

Total customers.
Waiting customers.
Customers currently being served.
Completed customers.
Cancelled customers.
6. Non-Functional Requirements
Usability

The application should provide a simple menu-driven terminal interface that is easy to understand and operate.

Reliability

The system should maintain the correct order of customers and update customer status correctly during normal operation.

Performance

Queue operations should be performed efficiently for the expected number of users.

Error Handling

The system should handle invalid menu choices, empty names, invalid service selections, and invalid token numbers without unexpectedly terminating the application.

Maintainability

The program should be organized into logical functions and modules with meaningful names and appropriate comments.

7. Technologies Used
Technology	Purpose
Python	Core programming language
collections.deque	FIFO queue management
heapq	Priority queue management
dataclasses	Representing customer information
datetime	Recording token creation time
Git	Version control
GitHub	Source code repository and project submission

The project is currently implemented as a terminal-based application and does not require external Python libraries.

8. Python Concepts Used

The project applies the following Python and problem-solving concepts:

Variables and data types
Conditional statements
Loops
Functions
Lists
Dictionaries
Queue data structure
FIFO queue operations
Priority queue
Searching
Data processing
Exception and input validation
Modular programming
Object-oriented concepts through classes
Basic analytics
9. System Workflow

The basic workflow of the system is:

Start
  ↓
Display Main Menu
  ↓
Generate Token
  ↓
Select Service
  ↓
Select Priority / Normal
  ↓
Add Customer to Queue
  ↓
Customer Tracks Token
  ↓
Administrator Calls Next Customer
  ↓
Service is Provided
  ↓
Complete / Cancel Service
  ↓
Update Statistics
  ↓
Return to Main Menu
  ↓
Exit
10. Project Structure
smart-queue-management-system/
│
├── main.py
├── README.md
├── statement.md
│
├── tests/
│   ├── test_queue.py
│   ├── test_tokens.py
│   └── test_analytics.py
│
└── docs/
    ├── architecture.png
    ├── workflow.png
    └── uml_diagrams/

The project will be organized into separate modules as development progresses to maintain a clean and maintainable code structure.

11. How to Run the Project
Prerequisites
Python 3.x
A terminal or command prompt
VS Code, IDLE, or another Python-compatible editor
Installation

Clone the repository:

git clone <your-github-repository-url>

Navigate to the project directory:

cd smart-queue-management-system

Run the application:

python main.py

No external Python packages are required for the current terminal-based version.

12. Example Usage
========================================
       SMART QUEUE MANAGEMENT SYSTEM
========================================

1. Generate Token
2. Display Queue
3. Call Next Customer
4. Complete Current Service
5. Track Token
6. Cancel Token
7. Show Analytics
8. Exit

Enter your choice: 1

Enter customer name: Akshat

Select Service:
1. Accounts
2. Examination
3. HelpDesk

Enter choice: 2

Priority customer? (y/n): n

Token generated successfully: E001

The administrator can then view the queue and call the next customer.

13. Testing

The system will be tested using different input and operational scenarios, including:

Generating multiple tokens.
Adding normal customers.
Adding priority customers.
Displaying the queue.
Calling the next customer.
Completing a service.
Cancelling a token.
Searching for a valid token.
Searching for an invalid token.
Entering invalid menu choices.
Entering empty customer names.
Verifying queue order and customer status.
14. Design Documentation

The project documentation will include the following design artifacts:

Problem Statement
Objectives
Functional Requirements
Non-Functional Requirements
System Architecture Diagram
Process / Workflow Diagram
Use Case Diagram
Class Diagram
Sequence Diagram
Testing Documentation

An ER diagram will be included if persistent database storage is added to the project.

15. Challenges

Some expected challenges during development include:

Maintaining the correct FIFO queue order.
Managing priority customers without disrupting normal queue operations.
Keeping customer status synchronized with queue operations.
Handling invalid user input.
Designing the program in a modular and maintainable manner.
Testing different queue conditions and edge cases.
16. Future Enhancements

Possible future improvements include:

Graphical user interface.
Database-based persistent storage.
Multiple service counters.
Real-time waiting-time estimation.
SMS or notification integration.
Daily and monthly queue reports.
Web-based interface.
Admin authentication.

These features are outside the scope of the current terminal-based implementation.

17. Learning Outcomes

Through this project, the following concepts will be practiced:

Applying Python to a real-world problem.
Understanding and implementing queue data structures.
Understanding priority-based processing.
Designing algorithms and workflows.
Writing modular Python programs.
Handling user input and errors.
Performing basic data analysis.
Testing and debugging Python applications.
Using Git and GitHub for version control.
18. Repository

GitHub Repository:
<Add your GitHub repository link here>

19. Project Information

Project Name: Smart Queue Management System
Subject: Python / Problem Solving
Project Type: Terminal-Based Application
Programming Language: Python
Development Approach: Modular Programming
