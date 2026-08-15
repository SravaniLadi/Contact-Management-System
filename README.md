# Contact Management System

A **Contact Management System** developed using **Java, Spring Boot, Spring Data JPA, and MySQL**. The application allows users to efficiently manage contact information through CRUD operations and search functionality.

## 🚀 Features

- ➕ Add new contacts
- 📋 View all contacts
- 🔍 Search contacts by name
- 👤 View contact details using ID
- ✏️ Update existing contact information
- 🗑️ Delete contacts
- 💾 Store contact data in MySQL database
- 🔗 RESTful API implementation

## 🛠️ Technologies Used

- Java 21
- Spring Boot 3.3.5
- Spring Web
- Spring Data JPA
- MySQL
- Maven
- HTML, CSS, JavaScript
- Lombok

## 🔗 REST API Endpoints

| Method | Endpoint                     | Description                |
| ------ | ---------------------------- | -------------------------- |
| GET    | `/contacts`                  | Get all contacts           |
| GET    | `/contacts/{id}`             | Get contact by ID          |
| GET    | `/contacts/search?name=John` | Search contacts by name    |
| POST   | `/contacts`                  | Add a new contact          |
| PUT    | `/contacts/{id}`             | Update an existing contact |
| DELETE | `/contacts/{id}`             | Delete a contact           |

## 🧠 DSA Concepts Used

This project applies fundamental **Data Structures and Algorithms concepts** in a practical Java application:

* **ArrayList / Lists** – Managing and storing contact records
* **Searching** – Finding contacts by name or ID
* **Iteration** – Traversing contact collections
* **CRUD Operations** – Efficient data insertion, retrieval, updating, and deletion
* **Object-Oriented Programming** – Using classes, objects, encapsulation, and methods
* **Database Querying** – Retrieving and manipulating contact data using JPA
* **Data Manipulation** – Processing and managing contact information efficiently


## 📂 Project Structure

```text
ContactManagementSystem
│
├── src/main/java
│   └── com/example/ContactManagementSystem
│       ├── controller
│       │   └── ContactController.java
│       ├── model
│       │   └── Contact.java
│       ├── repository
│       │   └── ContactRepository.java
│       ├── service
│       │   └── ContactService.java
│       └── ContactManagementSystemApplication.java
│
├── src/main/resources
│   ├── static
│   │   ├── css
│   │   ├── js
│   │   └── index.html
│   └── application.properties
│
└── pom.xml

