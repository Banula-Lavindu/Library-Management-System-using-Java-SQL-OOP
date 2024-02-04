# Library Management System

## Overview
The Library Management System is a software application designed to automate the activities of a library. It provides functionalities for librarians to manage books, borrowers, and library resources efficiently. Additionally, it offers features for borrowers to search and borrow books, check their borrowing history, and return books.

## Key Features

1. **Book Management:**
   - Add, edit, and delete books from the library database.
   - View detailed information about each book, including title, author, ISBN, genre, and availability status.
   - Search for books by title, author, genre, or ISBN.

2. **Borrower Management:**
   - Add, edit, and delete borrower accounts.
   - View borrower details, including name, contact information, and borrowing history.
   - Manage borrower accounts, including issuing and returning books.

3. **Borrowing Operations:**
   - Borrowers can search for available books and request to borrow them.
   - Librarians can approve or reject borrowing requests.
   - Keep track of borrowing history, due dates, and overdue fines.

4. **Return Management:**
   - Borrowers can return books, and librarians can process returns, updating the availability status of books.
   - Handle overdue fines for late returns.

5. **Reporting and Analytics:**
   - Generate reports on book inventory, borrowing statistics, and overdue books.
   - Analyze library usage patterns and identify popular books or genres.

6. **Authentication and Access Control:**
   - Secure login system for librarians and borrowers with role-based access control.
   - Librarians have full access to system functionalities, while borrowers have limited access to searching and borrowing books.

## Object-Oriented Programming (OOP) Concepts Used

The Library Management System is built using Object-Oriented Programming principles, including:

- **Encapsulation:** Classes like `Book`, `Borrower`, and `Library` encapsulate related data and methods, hiding internal implementation details from the outside world.
- **Inheritance:** Inheritance is utilized to model relationships such as `Book` and `EBook` inheriting from a common `Resource` class. This promotes code reusability and enhances maintainability.
- **Polymorphism:** Polymorphism is achieved through method overriding, allowing different types of objects to be treated uniformly. For example, the `displayDetails()` method can be overridden in subclasses like `EBook` to provide specific implementations.
- **Abstraction:** Abstract classes and interfaces are used to define common behavior and contracts. For instance, an `Item` interface might define methods like `checkOut()` and `returnItem()`, which are implemented by concrete classes like `Book` and `DVD`.

## Technologies Used

- Java: For the backend logic and business operations.
- SQL: For database management and storage of library data.
- JDBC: Java Database Connectivity for connecting Java applications with the SQL database.
- Git: Version control system for managing codebase and collaboration.
- IDE: Integrated Development Environment like IntelliJ IDEA or Eclipse for Java development.

## Target Users

- Librarians and library staff responsible for managing library resources.
- Library patrons or borrowers who wish to borrow books from the library.

## Purpose

The purpose of the Library Management System is to streamline library operations, improve efficiency in book management, enhance borrower experience, and provide insights for decision-making through data analytics.

## Demo Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/5Y72sh9h_BY" frameborder="0" allowfullscreen></iframe>

