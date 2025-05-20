# Online-Book-Store
A complete full-stack Java application to manage books using Spring Boot, Thymeleaf, and MySQL. It allows users to register, view, add to personal list, and delete books. 
Designed with clean UI and modular backend.
**Features**
1.Register new books
2.Display available books in tabular form
3.Add selected books to "My Books" list
4.Delete books from the list
5.Responsive Bootstrap-styled UI

**Tech Stack**
Backend: Java, Spring Boot (Maven)
Frontend: HTML, CSS, Bootstrap 5, Thymeleaf
Database: MySQL
IDE Used: Spring Tool

**Database Schema**
Table: book
id (Primary Key, Auto Increment)
name (VARCHAR)
author (VARCHAR)
price (VARCHAR)

Table: my_book_list
id (Primary Key)
name (VARCHAR)
author (VARCHAR)
price (VARCHAR)

**Key Concepts Used**

MVC Architecture
Spring Data JPA (CRUDRepository)
Thymeleaf for dynamic HTML views
Bootstrap 5 for responsive UI
Form handling and routing
Static resource mapping
