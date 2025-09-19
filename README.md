# 🛍️ E-Commerce App (Spring Boot)

This is a **learning project** I built while practicing **Java Spring Boot**.  
It’s a **basic E-commerce application** with separate **User** and **Admin** controllers, demonstrating how role-based endpoints can be structured.

---

## 🚀 Features
### User Side
- Browse available products
- View product details
- Add items to cart
- Place an order  

### Admin Side
- Add new products
- Update product details
- Delete products
- View all orders  

---

## 🛠️ Tech Stack
- **Java 17+**  
- **Spring Boot** (Spring Web, Spring Data JPA)  
- **Hibernate**  
- **H2 Database / MySQL** (based on config)  
- **Maven** (build tool)  

## 📂 Project Structure
src/main/java/com/example/ecommerce
│
├── controller
│ ├── UserController.java # Endpoints for users
│ └── AdminController.java # Endpoints for admins
│
├── entity # Entities like Product, Order, User
├── repository # Spring Data JPA repositories
├── service # Business logic
└── EcommerceApplication.java # Main Spring Boot application

**🎯 Learning Goals **

Through this project, I learned:

Structuring controllers for different roles (User & Admin)

Implementing CRUD operations with Spring Data JPA

Designing simple REST APIs

Understanding layered architecture in Spring Boot

## 📂 Project Structure
