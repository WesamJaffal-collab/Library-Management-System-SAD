# Library Management System - System Analysis & Design (SAD)

## 📌 Overview
This repository contains the comprehensive System Analysis and Design (SAD) documentation and UML models for a **Library Management System**. The project defines the architectural layout, core operational workflows, functional requirements, and class structures necessary to build a modern library management solution.

---

## 🎯 Core Features
- **Member Management:** Registration, authentication, and loan tracking.
- **Book Catalog & Search:** Search books by title, author, or ISBN, along with real-time availability checks.
- **Borrowing & Reservations:** Workflow handling for book issues, returns, and reservations.
- **Fine Calculation:** Automated penalty calculations for overdue book returns.

---

## 📐 UML Diagrams & System Architecture

### 1. Use Case Diagram
Illustrates the primary interactions between key actors (`Member`, `Librarian`) and the system functionalities.

![Use Case Diagram](./path-to-your-image/use_case_diagram.png)

---

### 2. Activity Diagram
Maps out the step-by-step logic and operational flow for a member requesting to borrow a book, including fine validations and availability checks.

![Activity Diagram](./path-to-your-image/activity_diagram.png)

---

### 3. Class Diagram
Defines the static structural design of the system, detailing domain entities (`Librarian`, `Member`, `Book`, `LibraryCatalog`, `Loan`, `Reservation`), their attributes, methods, and relationship cardinalities.

![Class Diagram](./path-to-your-image/class_diagram.png)

---

### 4. Sequence Diagram
Highlights the runtime object interaction and message passing sequence between the `UI`, `BookController`, and `FineCalculator` when returning a book.

![Sequence Diagram](./path-to-your-image/sequence_diagram.png)

---

## 🛠️ Tools Used
- **Modeling Standards:** UML 2.0
- **Focus Areas:** Systems Analysis & Design (SAD), Object-Oriented Analysis & Design (OOAD), Software Engineering Process.
