# 🛒 E-Commerce Backend API (Spring Boot)

This is a custom-built e-commerce backend developed using **Spring Boot**. It includes a custom **security system** with cookie-based authentication and persistent storage using **Hibernate** and a **relational database** (e.g., MySQL or PostgreSQL).

---

## 🚀 Features

- 🔐 Custom security logic (not Spring Security)
- 🍪 Cookie-based session store
- 🗄️ Hibernate ORM for database operations
- 📦 RESTful API endpoints for product, cart, user management
- 🧪 Ready for integration with frontend clients

---

## 🛠 Tech Stack

- Java 21
- Spring Boot 3.4.5
- Spring Security
- Spring Web
- Spring Data JPA (Hibernate)
- JWT (jjwt)
- H2 (can be replaced with any relational DB)
- Maven
- Lombok


---

---

## 💻 How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/Anuragjana432/Ecommerce_backend.git
cd Ecommerce_backend.git
Configure database

2.Update src/main/resources/application.properties:

properties
Copy
Edit
spring.application.name=ecommerce
spring.h2.console.enabled=true
spring.datasource.url=jdbc:h2:mem:test

project.image=images/

#spring.jpa.show-sql=true
#spring.jpa.properties.hibernate.format_sql=true


spring.app.jwtSecret=
spring.app.jwtExpirationMs=3000000
spring.ecom.app.jwtCookieName=springBootEcom

3. Build and run the project

Using Maven:

bash
Copy
Edit
./mvnw spring-boot:run

4.Access the API

By default, the server runs at:

arduino
Copy
Edit
http://localhost:8080
Use tools like Postman or connect your frontend to test API endpoints.

🙋‍♂️ Author
Anurag Jana
GitHub

