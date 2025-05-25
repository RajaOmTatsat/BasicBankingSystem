# BasicBankingSystem
A simple Java-based console application to manage Savings and Current bank accounts with features like deposit, withdrawal, balance inquiry, interest, and overdraft handling using OOP principles.
Basic-Banking-System/
├── src/
│   ├── BankAccount.java
│   ├── SavingsAccount.java
│   ├── CurrentAccount.java
│   └── BankSystemDemo.java
├── README.md
├── LICENSE
├── .gitignore
└── assets/
    └── screenshots/
        └── demo.png
📝 README.md Template
markdown

# 💰 Basic Banking System

A command-line based Banking System implemented in Java, applying core Object-Oriented Programming principles. It allows users to manage Savings and Current accounts with deposit, withdrawal, balance inquiry, and interest/overdraft functionalities.

---

## 🚀 Features

- Create and manage two types of accounts:
  - **Savings Account**: Interest feature
  - **Current Account**: Overdraft limit feature
- Deposit and withdraw money with validation
- Check account balance
- Encapsulation and Inheritance applied
- Designed for scalability and clarity

---

## 🛠 Technologies Used

- Java SE 8+
- OOP Concepts (Abstraction, Inheritance, Overriding)
- IDE: IntelliJ IDEA / Eclipse / NetBeans
- (Optional) MySQL/SQLite for future database support

---

## 🧱 Project Structure

src/
├── BankAccount.java
├── SavingsAccount.java
├── CurrentAccount.java
└── BankSystemDemo.java



---

## 🎮 How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Basic-Banking-System.git
cd Basic-Banking-System
Compile the code:

bash
Copy
Edit
javac src/*.java
Run the application:


java src.BankSystemDemo
🗃️ Database Design (For Future Enhancement)
Table: accounts
Column	Type	Description
account_id	VARCHAR	Unique account number
holder_name	VARCHAR	Account holder's name
account_type	ENUM	'Savings' or 'Current'
balance	DOUBLE	Current balance
interest_rate	DOUBLE (nullable)	For savings
overdraft_limit	DOUBLE (nullable)	For current

Table: transactions
Column	Type	Description
transaction_id	INT (PK)	Auto-increment
account_id	VARCHAR	FK to accounts
type	ENUM	'Deposit', 'Withdraw', 'Interest'
amount	DOUBLE	Transaction amount
timestamp	DATETIME	Auto timestamp

📸 Screenshots
Add a CLI screenshot or mock GUI:

markdown

Welcome to Basic Banking System
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
⚠️ Challenges Faced
Challenge	Solution
Avoiding code duplication	Implemented inheritance and polymorphism
Handling different account types	Created separate subclasses for logic
Providing access control	Used encapsulation and validation

✅ Key Advantages
Object-oriented and modular

Easy to extend to GUI or Web

Can be backed by a database

Ideal learning project for beginners

🔮 Future Enhancements
GUI version using JavaFX or Swing

Persistent storage with JDBC + MySQL

Admin login system

Transaction history

Web-based version using Spring Boot + React

Unit tests with JUnit

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

yaml
Copy
Edit

---

## 🧾 LICENSE (MIT Example)

```text
MIT License

Copyright (c) 2025 [RajaOmTatsat]

Permission is hereby granted, free of charge, to any person obtaining a copy...
