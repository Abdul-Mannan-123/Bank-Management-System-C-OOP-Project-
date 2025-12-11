![bank-banner](https://dummyimage.com/1200x280/0d4b28/ffffff&text=Bank+Management+System+%7C+C%2B%2B+OOP+Project)

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue)
![OOP](https://img.shields.io/badge/Paradigm-OOP-orange)
![Semester Project](https://img.shields.io/badge/Project-Semester%202-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# 💳 Bank Management System (C++ | OOP Project)

A console-based **Bank Management System** developed in **C++** as part of a **Semester 2 Object-Oriented Programming (OOP)** project.  
It simulates core banking operations while demonstrating essential OOP principles such as **abstraction, inheritance, encapsulation, and polymorphism**.

---

## ⭐ Features

### 👤 Account Management  
- Create and manage **Current** or **Savings** accounts  
- Auto-generated account numbers  

### 💰 Banking Operations  
- Deposit money  
- Withdraw money  
- Send money to another account  
- Display account balance  

### 📄 File Handling  
- Save account details to text files  
- Persistent storage using `.txt` files  

### 🧩 OOP Concepts Demonstrated  
| Concept        | Implementation Example |
|----------------|------------------------|
| **Abstraction** | Abstract class `BankAccount` with pure virtual methods |
| **Inheritance** | `CurrentAccount` and `SavingsAccount` derived from `BankAccount` |
| **Polymorphism** | Base class pointer enabling runtime dynamic binding |
| **Encapsulation** | Private account details accessed through public methods |
| **File Handling** | Account details saved and loaded from `.txt` files |

---

## 📂 Project Structure

Bank-Management-System/
│── main.cpp # Main program file
│── accountNumber.txt # Auto-generated account details
└── README.md # Documentation


---

## 🚀 How to Run

### **1. Clone the repository**
```sh
git clone https://github.com/<your-username>/Bank-Management-System.git
cd Bank-Management-System

---

### **2. Compile**

g++ main.cpp -o bank

3. Run
./bank


