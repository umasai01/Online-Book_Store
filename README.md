
# 📚 Online Book Store

A **Spring Boot-based Online Book Store** application that allows users to register, browse, and purchase books. The system provides **role-based access control** with separate features for users and admins.  

- **Users**: Browse books, add to cart, place orders, make secure payments.  
- **Admins**: Manage inventory, add/edit books, track and update orders.  

---

## 🚀 Features
- User registration & authentication  
- Role-based access (Admin/User)  
- Inventory management for books  
- Order placement and tracking  
- Email notifications using **SMTP Mail API**  
- Secure payments via **Razorpay API**  
- RESTful API endpoints for books and orders  

---

## 🛠️ Tech Stack
- **Backend**: Spring Boot  
- **Database**: MySQL  
- **Frontend**: HTML, CSS, JavaScript  
- **Payment Gateway**: Razorpay  
- **Email Service**: SMTP Mail API  

---

## 📂 Project Structure
```

Online-Book-Store/
│-- src/
│   ├── main/
│   │   ├── java/          # Java source code
│   │   ├── resources/     # Configuration files
│   └── test/              # Unit tests
│-- pom.xml                # Maven dependencies
│-- README.md              # Project documentation

````

---

## ⚡ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/username/online-bookstore.git
cd online-bookstore
````

### 2️⃣ Configure Database

* Create a MySQL database (e.g., `bookstore_db`)
* Update `application.properties` with your DB credentials

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/bookstore_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### 3️⃣ Run the application

```bash
mvn spring-boot:run
```

The app will start at: **[http://localhost:8080](http://localhost:8080)**

---

## 📬 API Endpoints

* `POST /api/auth/register` → Register user
* `POST /api/auth/login` → User login
* `GET /api/books` → Fetch all books
* `POST /api/books` → Add a new book (Admin only)
* `POST /api/orders` → Place an order

---

## 🖼️ Screenshots

(Add UI screenshots or Postman API testing images here)




