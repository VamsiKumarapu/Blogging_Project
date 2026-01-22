# Blogging Application – Spring Boot

A **Blogging Web Application** developed using **Spring Boot**, **Thymeleaf**, **Spring Data JPA**, and **MySQL**.  
This project allows users to create, view, update, and delete blog posts through a simple web interface.

---

## 🛠️ Tech Stack

- Java 17+
- Spring Boot 3.4.5
- Spring MVC
- Spring Data JPA
- Thymeleaf
- MySQL
- Maven
- Lombok
- Docker

---

## 📂 Project Structure

- src/main/java/... → controllers, models, services
- src/main/resources/templates → Thymeleaf pages
- src/main/resources/static → CSS/JS
- application.properties
- pom.xml 

---

## ✨ Features

- Create new blog posts
- View all blog posts
- Update existing blog posts
- Delete blog posts
- Server-side rendering using Thymeleaf
- Data persistence using Spring Data JPA & MySQL

---

## ⚙️ Configuration

### Database Configuration

Update the **`application.properties`** file with your database details:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/blog_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
```
---

## ▶️ Running the Application

### Prerequisites
- Java 17 or higher
- Maven installed
- MySQL running

### Steps to Run

```bash
mvn clean install
mvn spring-boot:run
```


### Application URL
http://localhost:8080


---

## 🧪 Testing

```bash
mvn test
```




     


    
