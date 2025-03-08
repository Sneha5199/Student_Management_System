# 🎓 Student Management System  

Simple CRUD API using **Spring Boot**, **Spring Data JPA**, and **MySQL**.  

## 🛠 Technologies Used  
- ⚡ Spring Boot  
- 📦 Spring Data JPA  
- 🗄️ MySQL  
- 📡 Postman  

## 🔗 API Endpoints  
| 🔹 Method | 🔹 Endpoint | 🔹 Description |
|-----------|-----------|----------------|
| **🟢 GET** | `/students` | Get all students |
| **🟢 GET** | `/students/{id}` | Get student by ID |
| **🟠 POST** | `/student/add` | Create a new student |
| **🔵 PUT** | `/student/update/{id}` | Update student details |
| **🔴 DELETE** | `/student/delete/{id}` | Delete a student |

## ⚙️ Setup Instructions  
### 📥 Clone the repository:  
```bash
git clone https://github.com/your-repo-url.git
cd your-project-folder
```  

### 🛠 Configure `application.properties`:  
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```  

### 🚀 Run the application:  
```bash
mvn spring-boot:run
```  

✅ Test the API using **Postman** or any API testing tool.  

💡 This project serves as a basic template for building **RESTful APIs** with **Spring Boot**.
