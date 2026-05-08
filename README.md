# LibroFly

Modern online bookstore platform developed as a distributed web application using Java and C#, deployed on Amazon Web Services (AWS). The system was designed to digitalize bookstore operations, automate sales processes, and provide customers with a secure and intuitive online shopping experience.

---

## Overview

LibroFly is an ecommerce web system focused on book sales and inventory management. The platform allows customers to browse a digital catalog, manage shopping carts, purchase books securely, and review their order history, while administrators can manage products, stock, and sales information.

The project follows a distributed architecture where:

- The backend was developed in Java using NetBeans.
- The frontend was developed in C#.
- Communication between both layers is handled through Jakarta Web Services.
- The database layer uses Oracle SQL.
- The application is deployed using Amazon Web Services.

---

## Technologies Used

### Backend

- Java
- NetBeans IDE
- Jakarta Web Services
- Oracle SQL
- JDBC
- Distributed programming concepts

### Frontend

- C#
- .NET Framework
- HTML
- CSS

### Cloud and Deployment

- Amazon Web Services

### Design and Documentation Tools

- Lucidchart
- Figma
- SQL scripts

---

## System Features

### Customer Features

- User registration and authentication.
- Digital book catalog exploration.
- Book search by title, author, or genre.
- Book filtering by genre, price, and availability.
- Book detail visualization.
- Shopping cart management.
- Payment method selection.
- Virtual receipt generation.
- Purchase history visualization.
- User profile management.

### Administrator Features

- Register new books.
- Edit existing book information.
- Delete books from the catalog.
- Manage book stock and availability.
- Monitor sales and purchase activity.

---

## System Architecture

LibroFly follows a layered and distributed architecture:


Frontend (C# / .NET)
        |
        | Jakarta Web Services
        v
Backend Services (Java / NetBeans)
        |
        v
Oracle SQL Database


The frontend communicates with the backend through Jakarta Web Services, allowing the application to separate presentation logic from business logic while supporting scalability and modularity.

## Functional Requirements
Code	Requirement
RF01	The software system allows registered users to log in using their username and password.
RF02	The software system allows users to view a catalog of books available for sale, showing only the cover, book title, and price.
RF03	The software system allows users to view the details of a book. When clicking on a book cover, a tab opens showing the title, author or authors, price, publisher, genres, and available stock. From this tab, the user can select the quantity to purchase.
RF04	The software system allows the administrator user to register, modify, or delete a book and its information from the catalog.
RF05	The software system automatically updates the availability status of a book according to its stock, marking it as “Sold Out” or “Available for Sale”.
RF06	The software system allows customers to register using their name, surname, document number, address, phone number, email, and password.
RF07	The software system allows users to search for books by title, author, or genre. It also allows search filters such as genre, price, and availability.
RF08	The software system allows users to select a payment method, such as Visa card or in-store payment.
RF09	The software system generates a virtual purchase receipt after each purchase, including receipt ID, document type, date, customer name, book, total price, and payment method.
RF10	The software system allows users to edit their personal profile, including address, phone number, and email.
RF11	The software system allows users to view their purchase history, including a detailed list of all orders made, the books purchased, and the total amount spent on each order.
RF12	The software system allows customers to add multiple books to the shopping cart.


## Non-Functional Requirements
Code	Requirement
RNF01	The system must validate access credentials in less than 3 seconds.
RNF02	The system must be accessible and work correctly in Google Chrome version 90 or higher.
RNF03	The system must process a book search by title, author, or genre in a maximum time of 3 seconds.
RNF04	The customer interface must allow access to the catalog, shopping cart, order history, and receipts within a maximum of 3 clicks from the homepage.


## Database Design

The relational database was designed using Oracle SQL to support transactional ecommerce operations.

The main entities include:

User
Book
Order
Payment Method
Receipt
Genre

These entities allow the system to manage users, products, purchases, receipts, and book classification.

## Development Process

The project was developed incrementally throughout the academic semester with weekly team meetings, progressive deliverables, and continuous architecture validation.

The development lifecycle included:

Requirements analysis.
UML and BPMN modeling.
Physical database design.
SQL script implementation.
Java backend implementation.
C# frontend implementation.
Integration through Jakarta Web Services.
Distributed communication testing.
Final deployment on Amazon Web Services.
Project Objectives

The primary goal of LibroFly was to create a transactional web application capable of supporting real business processes while applying enterprise software development practices.

The project focused on:

Object-oriented programming.
Distributed programming.
Database integration.
Business process modeling.
Software architecture design.
Web application deployment.
User-centered interface design.
Business Context

LibroFly was designed for a bookstore that originally operated through a traditional physical store model. The web platform acts as a complementary digital sales channel, allowing customers to explore books, filter options, create an account, and make online purchases securely.

After completing a purchase, customers may choose between home delivery through an external delivery service or in-store pickup. The bookstore staff manages orders, inventory, and sales through the digital system.

This hybrid model improves customer experience, increases commercial visibility, and supports more efficient business administration.

Software Product Description

LibroFly is an ecommerce web system that supports the digital transformation of a bookstore. It automates the process from book registration to final sale.

The system allows customers to:

Create an account securely.
Browse the available book catalog.
Filter books according to preferences.
Select books for purchase.
Complete secure purchases.
View receipts and purchase history.

The system allows administrators to:

Register available books.
Manage book information.
Control stock availability.
Review sales activity.
Team

## Developed by the Ecommerce Team:

Jose Luis Alejandro Martinez León
Luis Enrique Espinoza Correa
Jean Paul Pasache Guzman
Ramirez Barrantes Oliver
Academic Context

This project was developed as part of the Programming 3 course at the Pontificia Universidad Católica del Perú.

The project focused on applying programming, database, distributed systems, and software engineering concepts to a real-world ecommerce scenario.

Project Status

Academic prototype completed as part of the Programming 3 course.

## License

This project was developed for academic purposes.
