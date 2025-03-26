# ATM Management System

A robust and efficient ATM management system that facilitates seamless financial transactions, including deposits, withdrawals, balance inquiries, and administrative functions. The system ensures secure operations with role-based access for administrators and customers.

## 📌 Features

### 🏦 Admin Operations

Administrators have full control over account and ATM management:

- **Admin Login** - Secure authentication for administrators.
- **Manage Accounts** - Add, update, and remove user accounts.
- **Balance Management** - Oversee and update bank balances.
- **Denomination Handling** - Manage currency notes in the ATM.
- **View Transactions** - Monitor and track all transactions.

### 💳 Customer Operations

Users can efficiently manage their transactions:

- **User Login** - Secure authentication for account holders.
- **Balance Inquiry** - Check account balance in real-time.
- **Withdraw Funds** - Withdraw money with available denominations.
- **Deposit Money** - Add funds to their account.
- **Transaction History** - View past transaction details.

## 📂 Project Structure

### 🏛 Core Components

- **MainClass** - Entry point of the application.
- **ATMOperations** - Handles core ATM transactions.
- **AdminActions** - Manages administrative operations.
- **CustomerActions** - Manages customer functionalities.
- **Utilities** - Provides helper functions for calculations and validations.

### 📌 Data Models

- **Account** - Stores account details (ID, password, balance, transactions).
- **Transaction** - Tracks transaction type, amount, and time.
- **Denomination** - Manages available currency notes in the ATM.

## 🛠 Installation & Setup

### Prerequisites

- Java Development Kit (JDK 8+)
- Git (for cloning the repository)

### Steps to Install & Run

```sh
# Clone the Repository
git clone https://github.com/your-username/ATM-Management-System.git
cd ATM-Management-System

# Compile the Project
javac MainClass.java

# Run the Application
java MainClass
```

## 🖥 System Flow Diagram

![ATM Architecture](https://github.com/Navyamathan/ATM/blob/main/ATM/ATM.png)

## 📊 Output Preview

[Click here to view sample output](https://github.com/Navyamathan/ATM/blob/main/ATM/ATM.mp4)

## 🔄 How It Works

### 👨‍💼 Admin Workflow:

1. Admin logs in with secure credentials.
2. Manages user accounts and ATM balance.
3. Handles denomination adjustments.
4. Tracks transaction records.

### 👤 Customer Workflow:

1. Customer logs in securely.
2. Checks balance and transaction history.
3. Withdraws or deposits money.
4. Receives confirmation and updates.

## 🚀 Future Enhancements

- Integration with biometric authentication.
- Multi-language support for better accessibility.
- AI-based fraud detection for enhanced security.

## 📞 Contact & Author

**Author:** Navya M V  
**📧 Email:** navyamathan@gmail.com  
🔗 LinkedIn: [Navya M V](https://www.linkedin.com/in/navya-m-v-55515b353/)  

Happy Coding & Secure Banking! 💰

