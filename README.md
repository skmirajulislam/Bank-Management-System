# Bank Management System

A Java-based desktop application simulating core functionalities of a bank, such as ATM transactions, account management, and balance enquiry, built using Swing for the GUI.

## Features

- **User Authentication**: Login using Card Number and PIN.
- **Deposit**: Deposit money into your account.
- **Withdraw**: Withdraw cash with a custom amount.
- **Fast Cash**: Quick withdrawal of predefined amounts (e.g., Rs. 100, Rs. 500, etc.).
- **Mini Statement**: View a mini statement with recent transactions and masked card number.
- **Balance Enquiry**: Check current account balance.
- **PIN Change**: Update your account PIN.
- **Exit**: Securely exit the application.
- **Account Creation**: Create new bank accounts with options for account type and services (ATM card, Internet Banking, Mobile Banking, Email Alerts, Cheque Book, E-Statement).

## Technologies Used

- **Java** (Swing): For building the GUI.
- **JDBC**: For database operations (assumes backend database connectivity).
- **OOP Principles**: Modular classes for each major operation (`Deposit`, `Withdrawl`, `FastCash`, `BalanceEnquriy`, `mini`, etc.).

## Directory Structure

```
src/bank/management/system/
    |- main_Class.java           // Main dashboard with transaction options
    |- Login.java                // Login screen for users
    |- Deposit.java              // Deposit money functionality
    |- Withdrawl.java            // Cash withdrawal functionality
    |- FastCash.java             // Fast cash withdrawal
    |- mini.java                 // Mini statement generation
    |- BalanceEnquriy.java       // Balance enquiry window
    |- Signup3.java              // Account creation (step 3: account/services selection)
    |- ... (other supporting classes)
```

## Getting Started

### Prerequisites

- **Java JDK** (8 or above)
- **Database** (such as MySQL) configured with the required schema for user and transaction data
- **IDE** (Eclipse, IntelliJ IDEA, NetBeans, etc.)

### Running the Application

1. **Clone the repository:**
   ```bash
   git clone https://github.com/skmirajulislam/Bank-Management-System.git
   cd Bank-Management-System
   ```

2. **Set up the database:**
   - Create a database and configure the JDBC connection in the `Connn` class (not shown above).
   - Ensure tables for users, accounts, and transactions exist.

3. **Compile and run:**
   - Open the project in your IDE.
   - Run `main_Class.java` or `Login.java` to start the application.
   - `cd D:\devlopment\Bank-Management-System-\out\production\Bank_Management_System`
   - `java bank.management.system.main_Class`


## Screenshots

> _Add screenshots of the login screen, dashboard, and transaction windows here for better understanding._

## License

_This project currently does not have a license specified. Please add one if you intend to share or reuse._

## Author

- [Mirajul Islam](https://github.com/skmirajulislam)

---
**Note:** This is a learning project for educational purposes and does not implement real banking security protocols. Do not use with real financial data.
