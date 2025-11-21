# 🏦 Bank Management System
 Bank Managemant System (Java | JFrames | IntelliJ IDE | MySQL DB | Swing Technologies | Classes and
Frames ) - Bank Management System 🏦 (Java Swing + MySQL)

A complete **GUI-Based Bank Management System** built using **Java Swing (JFrames), AWT, MySQL, JDBC**, and follows a structured multi-frame architecture similar to real ATM applications.

This project simulates essential banking operations such as **cash withdrawal, deposits, balance inquiry, PIN change, fast cash**, and full **user onboarding** with an ATM-style interface.

---

## 🚀 Features

### 🔐 Authentication

* Login using **Card Number + PIN**
* Secure PIN validation
* Change PIN functionality

### 🧾 Account Operations

* Deposit Money
* Withdraw Money
* Fast Cash
* Check Balance
* Mini Statement (Transaction History)

### 📝 User Registration

* Multi-step registration:

  * Signup One
  * Signup Two
  * Signup Three
* Stores customer details, account details, and card information

### 🖥️ Interactive GUI

* Fully built using **Java Swing + AWT**
* Modern ATM layout
* Custom icons, images, styled components
* Smooth frame navigation

### 🗄️ Database (MySQL)

* Tracks users, accounts, transactions
* Fully functional SQL-backed operations
* Database-driven mini statements

---

## 📁 Project Folder Structure

```
BankManagementSystem/
│
├── src/
│   ├── bank/management/system/
│   │   ├── Login.java
│   │   ├── SignupOne.java
│   │   ├── SignupTwo.java
│   │   ├── SignupThree.java
│   │   ├── Deposit.java
│   │   ├── Withdraw.java
│   │   ├── FastCash.java
│   │   ├── BalanceEnquiry.java
│   │   ├── MiniStatement.java
│   │   ├── PinChange.java
│   │   └── Con.java        <-- MySQL Connection Class
│
├── icons/                 <-- All images & ATM UI assets
│
├── database.sql           <-- SQL Schema for all tables
│
└── README.md
```

---

## 🛠️ Tech Stack

### **Frontend / Desktop Application**

* Java Swing
* Java AWT

### **Backend**

* Java JDBC
* MySQL Database

### **Tools**

* IntelliJ IDEA / Eclipse / NetBeans
* MySQL Workbench / XAMPP

---

## ▶️ How to Run the Project

### **Step 1 — Clone the Repository**

```sh
git clone https://github.com/Sairam3210/BankManagementSystem.git
```

### **Step 2 — Open the Project in an IDE**

Use **IntelliJ**, **Eclipse**, or **NetBeans**.

### **Step 3 — Add MySQL JDBC Driver**

Download `mysql-connector-java.jar` and add it to:

```
Project → Libraries → Add JAR
```

### **Step 4 — Configure Database Connection**

Open **Con.java** and update your credentials:

```java
String url = "jdbc:mysql:///bankmanagementsystem";
String username = "root";
String password = "your_password";
```

### **Step 5 — Import database.sql**

Run `database.sql` in MySQL Workbench to create the required tables.

### **Step 6 — Run Login.java**

This opens the ATM-style banking interface.

---

## 🧠 Key Concepts Implemented

* Java Swing Components
* Event Handling (ActionListener)
* Multi-frame navigation
* JDBC Connectivity
* MySQL Query Execution
* Object-Oriented Programming
* ATM Simulation Logic

---



## 🤝 Contributions

Pull requests are welcome. Feel free to improve UI/UX or add extra banking features.

---

