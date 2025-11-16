# 📚 Student Management System (Spring Boot + Thymeleaf)

A lightweight, maintainable, and user‑friendly **Student Management System** built using Spring Boot, Spring MVC, Thymeleaf, JPA/Hibernate, and MySQL. This project includes clean architecture, modular components, reusable templates, and easily extendable design.

---

# 🚀 Features

* 👨‍🎓 **Student CRUD** — Add, update, delete, view student details
* 🎨 **Modern UI** — Clean responsive Thymeleaf templates
* 🗄️ **MySQL Database** — Persistent and scalable storage
* 🔄 **Spring MVC Architecture** — Clear and maintainable flow
* 📦 **Spring Data JPA** — Simplifies database operations
* 📱 **Responsive Layout** — Works on mobile and desktop
* 🧩 **Modular Structure** — Easy to extend with more modules

---

# 🛠️ Tech Stack

| Layer      | Technology               |
| ---------- | ------------------------ |
| Backend    | Java 11, Spring Boot 2.x |
| Frontend   | Thymeleaf, HTML5, CSS3   |
| Database   | MySQL 8.x                |
| ORM        | Hibernate / JPA          |
| Build Tool | Maven                    |
| Server     | Embedded Tomcat          |

---

# 📂 Project Structure

```
src/main/java/com/example/sms/
 ├── controller      → Web controllers (Spring MVC)
 ├── service         → Interfaces for business logic
 ├── service/impl    → Service implementations
 ├── repository      → JPA repositories
 ├── entity          → JPA Entity classes
 └── config          → Configurations (optional)

src/main/resources/
 ├── templates/      → Thymeleaf HTML templates
 ├── static/css/     → Custom CSS
 ├── static/js/      → Optional JS
 └── application.properties
```

---

# 🧪 Testing API Endpoints (If Enabled)

| Method | Endpoint         | Description          |
| ------ | ---------------- | -------------------- |
| GET    | `/students`      | View all students    |
| GET    | `/students/{id}` | View student details |
| POST   | `/students`      | Add new student      |
| PUT    | `/students/{id}` | Update student       |
| DELETE | `/students/{id}` | Delete student       |

(Works only if REST controllers are implemented in your version.)

---
It helps others discover it.
