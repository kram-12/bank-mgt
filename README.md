# 💰 Banking Management System

A console-based **Banking Management System** built using **C++**, incorporating the core concepts of **Object-Oriented Programming (OOP)** and **Data Structures** such as **Linked Lists** and **Queues**. This project simulates essential banking operations for users, ATM functionalities, and admin-level access for managing internal processes.

## 🛠️ Features

The system offers 4 major modules:

1. **🏦 Enter Bank**

   * Pay Bills
   * Withdraw/Deposit Cash
   * Open New Account
   * View Account (Username & Password authentication)

2. **🏧 Enter ATM**

   * Withdraw Cash
   * Change PIN (with current PIN verification)
   * Balance Enquiry

3. **🔐 Administrator (Restricted Area)**

   * Requires valid Username & Password
   * View Bill Payment Queue
   * View and Process Account Opening Queue

4. **🚪 Exit**

   * Exit the program with a farewell message

## 🧰 Tech Stack

* **Language:** C++
* **Concepts Used:**

  * Classes & Objects
  * Constant Functions & Variables
  * Linked List
  * Queues
  * Conditional Statements
  * Iterative Loops

## 📂 File Structure

```bash
├── bank_mgt_system.cpp  # Main source file with complete implementation
└── README.md            # Project documentation
```

## 🧑‍💻 How to Run

1. **Clone the Repository**

   ```bash
   git clone <your-repo-link>
   cd Banking-Management-System
   ```

2. **Compile and Run**

   ```bash
   g++ bank_mgt_system.cpp -o bank
   ./bank
   ```

> 💡 Make sure you have a C++ compiler (like `g++`) installed on your system.

## 🎯 Learning Objectives

This project helps reinforce:

* Real-world implementation of OOP concepts
* Working with queues and linked lists
* User authentication and menu-driven interfaces
* Understanding basic banking workflows in code
