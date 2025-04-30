# Spring Boot MVC CRUD Demo

This repository contains a simple **Spring Boot MVC** application demonstrating basic **CRUD (Create, Read, Update, Delete)** operations on an `Employee` entity. It uses **Spring Boot**, **Spring MVC**, **Spring Data JPA**, and **Thymeleaf** for the front-end rendering.

## 🚀 Technologies Used

- Java 17+
- Spring Boot
- Spring MVC
- Spring Data JPA (Hibernate)
- Thymeleaf (Template Engine)
- H2 Database (In-Memory)

## 📌 Project Structure

```
src/
└── main/
    ├── java/
    │   └── com.example.crud/
    │       ├── controller/     # Web layer (MVC Controllers)
    │       ├── entity/         # Employee entity
    │       ├── repository/     # Spring Data JPA interface
    │       ├── service/        # Business logic
    │       └── DemoApplication.java
    └── resources/
        ├── templates/          # Thymeleaf HTML pages
        ├── application.properties
        └── static/
```

## 🎯 Features

- List all employees
- Add a new employee
- Update existing employee information
- Delete an employee
- Form validation
- Simple HTML front-end with Thymeleaf

## ✅ How to Run

```bash
# Clone the repository
git clone https://github.com/eminyavuz/Spring-boot-mcv-demo.git

# Navigate into the project directory
cd Spring-boot-mcv-demo

# Run the application
./mvnw spring-boot:run
```

Then open your browser and go to:  
👉 `http://localhost:8080/employees`

## 📚 Example Use Case

This project is useful as a starter template for:
- Building admin dashboards
- HR systems
- Any Java-based web application needing CRUD logic with a database and UI

## 🧑‍💻 Author

Developed by **[Emin Yavuz](https://github.com/eminyavuz)** as part of a Spring Boot MVC learning project.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
