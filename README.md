
# 🛍️ Java E-Commerce Project

A simple e-commerce web application built using **Java Spring Boot** and **Maven**.

---

## 🚀 Getting Started

Follow the steps below to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/Nakkkkkul0130/java-project/JtProject
```

### 2. Open in Your IDE
- **Recommended**: Use **IntelliJ IDEA** or **Eclipse**
- If you're using **IntelliJ IDEA**:
  - Open the project as a **Maven Project**
  - Ensure the project is recognized as a **Spring Boot** project
  - Set the correct **working directory** so that Spring Boot can locate the `views/` folder correctly  
    *(Check: File > Project Structure > Modules > Paths > Working Directory)*

### 3. Navigate to the Project Directory
```bash
cd JtProject
```

### 4. Configure the Database
Update the `application.properties` file located in:
```
src/main/resources/application.properties
```
Example:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 5. Run the Application
Open and run the main class:

```
src/main/java/com/jtspringproject/JtSpringProject/JtSpringProjectApplication.java
```

### 6. Access the Application
Open your browser and visit:
```
http://localhost:8080/
```

---

## 🔐 Login Credentials

### Admin User
> *(Only available if you ran `basedata.sql` on your MySQL database)*  
- **Username**: `admin`  
- **Password**: `123`

### Normal User
- **Username**: `lisa`  
- **Password**: `765`

---

---

## 🛠 Tech Stack
- Java 8+
- Spring Boot
- Maven
- MySQL
- HTML/CSS/JS

---

## 📌 Notes
- Ensure MySQL is running before launching the app.
- If you're using a custom database, you must create an admin user manually unless `basedata.sql` is executed.
