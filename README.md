# Hospital Management System

A **GUI-based Java application** designed to manage core hospital operations such as patient registration, employee management, room allocation, and patient discharge. The project uses **Java Swing/AWT** for the user interface and **MySQL** for database management.

---

## 📌 Features

* Patient admission and discharge management
* Employee and department records management
* Room search and allocation
* Reception and ambulance modules
* Secure login system with basic validation
* Update patient details
* MySQL database integration using JDBC

---

## 🛠️ Tech Stack

* **Programming Language:** Java
* **GUI:** Java Swing / AWT
* **Database:** MySQL
* **Database Connectivity:** JDBC
* **IDE:** IntelliJ IDEA / Eclipse

---

## 📂 Project Structure

```
HospitalManagementSystem/
│
├── .idea/
├── out/
├── src/
│   └── hospital/management/system/
│       ├── ALL_Patient_Info.java
│       ├── Ambulance.java
│       ├── conn.java
│       ├── Department.java
│       ├── Employee_info.java
│       ├── Login.java
│       ├── NEW_PATIENT.java
│       ├── patient_discharge.java
│       ├── Reception.java
│       ├── Room.java
│       ├── SearchRoom.java
│       └── update_patient_details.java
│
├── icon/
│   ├── amb.png
│   ├── dr.png
│   └── login.png
│
├── database/
│   └── hospital_schema.sql
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mp9756714-jpg/Hospital-Management-System-.git
```

### 2️⃣ Open Project

* Open the project in **IntelliJ IDEA** or **Eclipse**
* Ensure JDK is properly configured

### 3️⃣ Database Setup

* Install **MySQL Server**
* Create a database using the provided SQL file:

```sql
source database/hospital_schema.sql;
```

### 4️⃣ Configure Database Connection

Edit `conn.java` and update your database credentials:

```java
String url = "jdbc:mysql://localhost:3306/hospital";
String user = "root";
String password = "your_password";
```

### 5️⃣ Run the Application

* Run `Login.java` to start the application

---

## 🔐 Default Login

> Credentials depend on the database records. Please check the `login` table in MySQL.

---

## 📝 Notes

* All icons must be placed inside the `icon/` folder
* Ensure MySQL service is running before launching the application
* JDBC connector must be added to the project libraries

---

## 📸 Screenshots

*Add screenshots here (optional)*

---

## 🚀 Future Enhancements

* Role-based authentication (Admin, Doctor, Receptionist)
* Billing and payment module
* Appointment scheduling
* Improved UI/UX

---

## 👨‍💻 Author

**Manoj Pal**

---

## 📄 License

This project is for educational purposes only.
