# Bankist App

Bankist is a **fully functional front-end banking application** that simulates the behavior of a modern digital bank.

The application allows users to manage their accounts, transfer money, request loans, and track transactions in a simple and intuitive interface.

---

# Features

## Secure Login System

Users can log into their account using:

- Username
- PIN

After login, the dashboard displays:

- account balance
- transaction history
- account summary

---

# Money Transfers

Users can instantly transfer money to another Bankist account.

Features:

- real-time balance update
- transaction history tracking
- movement display for both sender and receiver

---

# Loan Request System

Users can request a loan.

Loan approval logic:

- A loan is approved if the user has a deposit of **at least 10% of the requested loan amount**.

When approved:

- The amount is added to the account in few seconds
- A new transaction is recorded

---

# Transaction Sorting

Users can sort their transactions.

The sort button allows users to:

- Sort deposits and withdrawals
- Toggle between default order and sorted order

---

# Account Summary

The dashboard displays a summary including:

- Total deposits
- Total withdrawals
- Total interest earned

Interest is calculated automatically based on account data.

---

# Internationalization (Locale Support)

Dates and currencies are formatted according to **different country locales**.

Examples include:

- US
- Germany
- India
- Nigeria
- and other international formats

This demonstrates the use of the **Intl API** in JavaScript.

---

# Automatic Logout Timer

For security purposes, the app automatically logs the user out after **5 minutes of inactivity**.

The timer resets whenever the user performs actions such as:

- transferring money
- requesting a loan
- sorting transactions

---

# Close Account Feature

Users can permanently close their account by providing:

- username
- PIN

When confirmed:

- The account is removed
- The user is logged out

---

# Project Structure

Bankist-App
│
├── index.html
├── style.css
├── script.js

The project uses **JavaScript arrays and objects** to simulate banking data.

---

# Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)

Concepts demonstrated:

- Arrays & Objects
- DOM manipulation
- Date formatting
- Currency formatting
- Timers
- Sorting algorithms
- Application state management

---

# Purpose of the Project

This project demonstrates how a **modern banking interface works** using JavaScript.

It was built to practice:

- advanced **JavaScript logic**
- **state management**
- building **interactive web applications**

---

# License

This project is intended for **educational and learning purposes**.
