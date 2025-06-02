# 📖 Library API

## 🔎 About the Project
The **Library API** is a library management system developed in .NET 8. The API aims to enable the registration, management, and control of books, authors, categories, and loans in a simple and efficient way. The system is designed to facilitate both internal library management and public catalog access.

## 🚀 Features
- Registration and management of **books**, **authors**, and **categories**;
- Recording and control of **loans** and **returns**;
- Book availability inquiries;
- **RabbitMQ** notification system for important events, such as pending returns;
- **Structured logs** with Serilog to facilitate monitoring and diagnostics;
- Automated tests with **NUnit** to ensure code quality.

## 🚀 Technologies Used
- **.NET 8** - Main framework for API development;
- **Entity Framework Core** - ORM for object mapping and database access;
- **MySQL** - Relational database for information storage;
- **RabbitMQ** - Message broker for asynchronous communication between services;
- **Serilog** - Logging library for monitoring and debugging;
- **OpenAPI (Swagger)** - Interactive API documentation;
- **Docker** - For containerizing the application and supporting services;
- **NUnit** - Framework for creating unit and integration tests.

## 🚫 Requirements
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🚧 How to Download and Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Thyago-Oliveira-Perez/Library.git
cd Library
```

### 2. Start the Containers with Docker Compose
```bash
docker-compose up -d
```
This will start:
- The API in .NET 8;
- The MySQL database;
- RabbitMQ;
- 

### 3. Access the API
The interactive API documentation will be available at:
```
http://localhost:5000/swagger
```

### 4. Run the Tests
```bash
dotnet test
```

## 📆 Project Structure
```

```

## 📊 Contributions
Contributions are welcome! Feel free to open issues and pull requests.

## ✨ License
This project is licensed under the [MIT License](LICENSE).

---
Made with 🚀 by Thyago de Oliveira Perez.

