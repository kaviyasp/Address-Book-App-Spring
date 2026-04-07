# Address Book Application (Spring Boot)

This is a simple Address Book REST API built using Spring Boot.  
It allows users to manage contact details like name, address, and other basic information.

> **Note:**  
> The complete source code for this project is available in the `dev` branch.  
> The `main` branch contains only project overview and documentation.

---

## Features

- Add new contact  
- View all contacts  
- Update existing contact  
- Delete contact  
- Layered architecture (Controller → Service → Model)  
- DTO usage for clean data handling  

---

## Tech Stack

- Java  
- Spring Boot  
- Maven  
- REST APIs  
- H2 Database (in-memory)  

---

## Project Structure
```

com.bridgelabz.addressbook
│
├── controller → Handles API requests
├── service → Business logic
├── model → Entity class
├── dto → Data Transfer Object
└── resources → application.properties

```

---

## API Endpoints (Sample)

| Method | Endpoint           | Description        |
|--------|--------------------|--------------------|
| GET    | /addressbook       | Get all contacts   |
| POST   | /addressbook       | Add new contact    |
| PUT    | /addressbook/{id}  | Update contact     |
| DELETE | /addressbook/{id}  | Delete contact     |

---

## How to Run (from `dev` branch)

1. Switch to dev branch:
   ```bash
   git checkout dev

2. Build and run:
   ```bash
   mvn spring-boot:run

3. Access APIs using:
- Postman / Browser
- Default URL: http://localhost:8080

## Notes
- This project is created for learning Spring Boot CRUD operations
- Demonstrates clean architecture and basic REST API design
- Easy to extend with database integration and validation
