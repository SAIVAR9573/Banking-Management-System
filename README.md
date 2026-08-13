# 🏦 Banking Management System

A desktop-based banking application developed using **Java Swing, MySQL, and JDBC** that simulates basic banking and ATM operations.

## 🚀 Features

- 👤 Multi-step customer registration
- 🔐 Card number & PIN authentication
- 💰 Cash deposit
- 💸 Cash withdrawal
- ⚡ Fast cash
- 💳 Balance enquiry
- 📄 Mini statement
- 🔑 PIN change
- 🗄️ MySQL database integration
- ✅ Input validation
- 📊 Transaction history

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Application logic |
| **Java Swing** | Graphical User Interface |
| **MySQL** | Database |
| **JDBC** | Database connectivity |
| **JCalendar** | Date selection |
| **Eclipse IDE** | Development |

## 🏗️ Architecture

```text
┌───────────────────────────────┐
│             👤 USER           │
│      Banking Operations       │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│       🖥️ JAVA SWING GUI       │
│   Login • Signup • ATM Menu   │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│      ⚙️ JAVA APPLICATION      │
│ Authentication • Validation   │
│ Transactions • Balance Logic  │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│          🔌 JDBC              │
│     Database Connectivity     │
└───────────────┬───────────────┘
                │
                ▼
┌───────────────────────────────┐
│          🗄️ MySQL             │
│ Customer • Login • Accounts   │
│        • Transactions         │
└───────────────────────────────┘
```

## 🗄️ Database

The project uses **MySQL** with the following main tables:

```text
signup
signup2
signup3
login
bank
```

The `bank` table stores transaction information:

```text
PIN | Date | Type | Amount
```

The current balance is calculated using:

```text
Total Deposits - Total Withdrawals
```

## 💡 Key Highlights

- ATM-style graphical interface
- Customer registration and authentication
- Deposit and withdrawal processing
- Fast cash functionality
- Dynamic balance calculation
- Transaction history and mini statements
- PIN management
- Java–MySQL database integration
- Input validation

## 🔮 Future Improvements

- 🔐 PIN/password hashing
- 🔑 Two-factor authentication
- 👨‍💼 Admin dashboard
- 🔔 Transaction notifications
- 🌐 Web-based version
- 📱 Mobile application
- ☁️ Cloud database

## 👨‍💻 Author

**Parepally Saivarshith**  
B.Tech – Computer Science & Engineering

> This project was developed for educational purposes.
