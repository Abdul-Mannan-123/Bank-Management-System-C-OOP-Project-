
# 💳 Bank Management System (C++ | OOP Project)

## 📝 Overview
The **Bank Management System** is a console-based C++ application developed as part of a **Semester 2 Object-Oriented Programming (OOP)** project.  
It simulates essential banking operations while demonstrating core OOP concepts such as **abstraction**, **inheritance**, **encapsulation**, and **polymorphism**.

---

## 🚀 Features
- 👤 Create and manage bank accounts (Current or Savings)  
- 💰 Deposit and withdraw funds securely  
- 💸 Send money to other account numbers  
- 📄 Save account details to a text file  
- 💾 File handling for data storage  
- 🧩 Demonstrates pure virtual functions and dynamic binding  

---

## 🏗️ OOP Concepts Used
| Concept | Implementation |
|----------|----------------|
| **Abstraction** | Abstract class `BankAccount` with pure virtual methods |
| **Inheritance** | `CurrentAccount` and `SavingsAccount` derived from `BankAccount` |
| **Polymorphism** | Base class pointer used for dynamic function calls |
| **Encapsulation** | Account details and balance handled through class methods |
| **File Handling** | Account information saved to text files |

---

## 📂 File Structure
Bank-Management-System/
│
├── main.cpp # Main program file
├── accountNumber.txt # Auto-generated account details file
└── README.md # Project documentation

---

## ⚙️ How to Run
1. Clone or download the repository:
   ```bash
   git clone https://github.com/<your-username>/Bank-Management-System.git
cd Bank-Management-System
g++ main.cpp -o bank
./bank

Enter name: John Doe
Enter account number: 12345
Enter age: 25
Choose Account Type:
1. Current Account
2. Savings Account
Enter your choice: 1
Account details saved to file.
1. Deposit
2. Withdraw
3. Display Balance
4. Send Money
5. Exit

## 👨‍💻 Author

**Abdul Mannan**
🎓 BS Computer Science — National University of Computer and Emerging Sciences
📅 Year 1, Semester 2


---
