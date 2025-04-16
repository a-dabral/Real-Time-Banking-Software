# 🏦 Real-Time-Banking-Software

## 📘 Overview

The **Real-Time Banking Software** is a robust application designed to simulate core banking operations with an intuitive interface and secure backend implementation. It offers essential banking features like account creation, deposits, withdrawals, and balance inquiries—providing a practical learning experience for both developers and users.

---

## ✨ Features

### 👤 User Account Management
- Signup and login functionality with secure authentication

### 💰 Core Banking Features
- Deposit and withdrawal of funds  
- Real-time balance checks

### 📊 Transaction Management
- Keeps records of all transactions for traceability

### 🖥️ User-Friendly Interface
- Developed with a responsive UI using modern design principles

---

## 📌 Use Cases

- Learning and practicing banking operations in a software environment  
- Demonstrating CRUD operations and secure authentication workflows  
- Academic projects showcasing real-world financial system simulations  

---

## 🛠️ Installation

### 📋 Prerequisites
- PHP installed on your system  
- MySQL database for backend storage  
- A web server such as Apache or Nginx (XAMPP/WAMP/LAMP)

### ⚙️ Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/a-dabral/Real-Time-Banking-Software.git
   cd Real-Time-Banking-Software
   ```

2. Set up the database:
   - Import the `banking.sql` file into your MySQL database.
   - Update database credentials in `config.php`.

3. Deploy the application on your local server (e.g., XAMPP, WAMP, or LAMP).

4. Open the application in your browser:
   ```
   http://localhost/Real-Time-Banking-Software
   ```

---

## 🚀 Usage

### 🔐 Signup and Login
- Users can create accounts and log in securely.

### 💳 Deposit and Withdraw
- Add or remove funds from the account.

### 📈 View Balance
- Check the current account balance in real time.

### ❌ Account Deletion
- Securely delete user accounts.

---

## 🔄 Example Workflow

1. **Signup**: Create a new user account  
2. **Deposit Funds**: Add an initial amount to your account  
3. **Withdraw Funds**: Perform a withdrawal transaction  
4. **Check Balance**: View the updated balance after transactions

---

## 🗂️ File Structure

- `index.php` – Main landing page  
- `signup.php` – User signup functionality  
- `login.php` – Secure login implementation  
- `dashboard.php` – User dashboard with transaction options  
- `config.php` – Database configuration  
- `banking.sql` – SQL schema for setting up the database  

---

## 📚 Documentation

The source code is thoroughly commented to explain the logic behind each function. Key implementations include:

- 🔐 Authentication mechanisms with **hashed passwords**  
- 🔍 Transaction validation to prevent overdrafts  
- 💾 Database operations using **prepared statements** for enhanced security

---

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository  
2. Create a new feature branch:  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push the branch:  
   ```bash
   git push origin feature/your-feature
   ```
5. Open a **pull request** for review

---

## 🙏 Acknowledgments

Project developed and maintained by **Abhishek Dabral**  
Originally conceptualized for academic learning and practical exposure to real-world software development practices.

---

📎 *If you're viewing this project via my resume or portfolio, feel free to explore the code and share feedback!*
