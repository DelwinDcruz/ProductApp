# **ProductApp**

A simple **Spring Boot-based Product Management System** with CRUD operations using Hibernate (JPA) and MySQL/PostgreSQL.

---

## **Table of Contents**  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation & Setup](#installation--setup)  
- [API Endpoints](#api-endpoints)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  

---

## **Features**  
- ✅ Create, Read, Update, and Delete (CRUD) operations  
- ✅ Uses **Spring Boot & Hibernate (JPA)** for database interactions  
- ✅ Implements **MVC architecture** for better code organization  
- ✅ Supports **JSP (inside `WEB-INF/view/`)**  
- ✅ Utilizes **EntityManager (JPA)** for database transactions  

---

## **Tech Stack**  
- **Programming Language:** Java  
- **Backend Framework:** Spring Boot  
- **Database:** MySQL / PostgreSQL  
- **ORM Framework:** Hibernate (JPA)  
- **Frontend:** JSP  
- **Build Tool:** Maven  

---

## **Installation & Setup**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/VIVEK-P-V/ProductApp.git
cd ProductApp
```

### **2. Configure Database**  
Modify `src/main/resources/persistence.xml` or `application.properties` with your database details.

### **3. Build the Project**  
```bash
mvn clean install
```

### **4. Run the Application**  
```bash
mvn spring-boot:run
```
The application will be available at **http://localhost:8080**.

---

## **API Endpoints**  
| Method  | Endpoint       | Description              |
|---------|---------------|--------------------------|
| **GET** | `/`           | Home page (List products) |
| **GET** | `/addproduct` | Show add product form    |
| **POST**| `/handle`     | Add a new product        |
| **GET** | `/update/{id}` | Show update form        |
| **POST**| `/form`       | Update product details   |
| **GET** | `/delete/{id}` | Delete a product        |

---

## **Project Structure**  
```
ProductApp/
│-- src/main/java/productapp/
│   ├── controller/ProductController.java
│   ├── dao/ProductDao.java
│   ├── model/Product.java
│-- src/main/webapp/WEB-INF/view/
│   ├── index.jsp
│   ├── addproduct.jsp
│   ├── update.jsp
│-- src/main/resources/
│   ├── application.properties
│-- pom.xml
│-- README.md
```

---

## **Contributing**  
Contributions are welcome! Follow these steps:  

1. **Fork the repository**  
2. **Create a feature branch (`git checkout -b feature-name`)**  
3. **Commit your changes (`git commit -m "Added new feature"`)**  
4. **Push to the branch (`git push origin feature-name`)**  
5. **Open a Pull Request**  

---
