# University Management System using JAVA

## 📌 Project Overview
The **University Management System** is a Java-based desktop application designed to manage various university operations efficiently.  
It helps administrators to manage student details, teacher information, examination records, fee structure, and leave management in a simple and organized way.

---

## 🚀 Features

- Add Student Details  
- Add Teacher Details  
- Manage Examination Results  
- View and Update Student Information  
- Leave Management for Students and Teachers  
- Fee Structure Management  
- User-Friendly Graphical Interface  

---

## 🛠 Technologies Used

- **Programming Language:** Java  
- **IDE:** Apache NetBeans  
- **Database:** MySQL  
- **GUI Framework:** Java Swing  
- **JDBC:** For Database Connectivity  

---

## 📂 Project Modules

1. **Login Module** – Secure authentication for admin  
2. **Student Module** – Add, view, and update student data  
3. **Teacher Module** – Manage teacher information  
4. **Examination Module** – Manage student marks  
5. **Fee Module** – View and update fee structure  
6. **Leave Module** – Track leave details  

---

## ⚙ How to Run the Project

1. Install **Apache NetBeans IDE**  
2. Install **MySQL Database**  
3. Import the project into NetBeans  
4. Create the required database in MySQL  
5. Configure database connection in the code  
6. Run the project from the Login.java file  

---

## 🗄 Database Setup

Create a MySQL database and required tables before running the project.

```sql
CREATE DATABASE university;
### 1. fee  
Stores semester-wise fee details for different courses.

**Columns:**
- course  
- semester1  
- semester2  
- semester3  
- semester4  
- semester5  
- semester6  
- semester7  
- semester8  

---

### 2. marks  
Stores student marks information.

**Columns:**
- rollno  
- semester  
- marks1  
- marks2  
- marks3  
- marks4  
- marks5  

---

### 3. student  
Stores student personal and academic details.

**Columns:**
- name  
- fname  
- rollno  
- dob  
- address  
- phone  
- email  
- class_x  
- class_xii  
- aadhar  
- course  
- branch  

---

### 4. teacher  
Stores teacher information.

**Columns:**
- name  
- fname  
- empId  
- dob  
- address  
- phone  
- email  
- class_x  
- class_xii  
- aadhar  
- education  
- department  

---

### 5. subject  
Stores subject details for each student semester.

**Columns:**
- rollno  
- semester  
- subject1  
- subject2  
- subject3  
- subject4  
- subject5  

---

### 6. studentleave  
Stores student leave information.

**Columns:**
- rollno  
- date  
- duration  

---

### 7. teacherleave  
Stores teacher leave information.

**Columns:**
- empId  
- date  
- duration  

