# DigiWallet – Secure Digital Wallet Management System

A modern and secure Digital Wallet Management System built using PHP, MySQL, HTML5, CSS3, Bootstrap, JavaScript, and integrated with Google Authentication and Razorpay Payment Gateway. DigiWallet enables users to securely manage digital funds, perform wallet-to-wallet transfers, add money online, and track their transaction history through a responsive and intuitive interface.

---

# Project Overview

DigiWallet is a web-based financial application designed to simulate the core functionality of a real-world digital wallet. It offers a secure authentication system, digital payment integration, wallet balance management, fund transfers, and comprehensive transaction tracking. The application prioritizes security, usability, and responsive design to provide a seamless user experience across devices.

---

# Key Features

# Authentication
- User Registration & Login
- Secure Password Hashing
- Google OAuth Sign-In
- Session Management
- Logout Functionality

# User Profile
- View Profile Information
- Edit Profile Details
- Upload Profile Picture *(Optional)*
- Change Password *(Optional)*

# Wallet Management
- Automatic Wallet Creation
- Real-Time Wallet Balance
- Add Money to Wallet
- Razorpay Payment Integration
- Secure Wallet Updates

# Money Transfer
- Wallet-to-Wallet Transfers
- Balance Validation
- Recipient Verification
- Prevent Self Transfers
- Transaction Recording

# Transaction History
- Complete Transaction Logs
- Transaction Status
- Payment Method Details
- Date & Time Tracking

# User Interface
- Responsive Design
- Modern FinTech Dashboard
- Bootstrap 5 Components
- Interactive UI Elements
- Mobile Friendly Layout

---

# Technology Stack

# Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Bootstrap Icons
- Google Fonts

# Backend
- PHP

# Database
- MySQL

# Third-Party Integrations
- Google OAuth Authentication
- Razorpay Payment Gateway

---

# Project Structure

```
digital_wallet/
│
├── actions/
│   ├── login_actions.php
│   └── register_actions.php
│
├── config/
│   ├── config.php
│   ├── razorpay_config.php
│   └── google_config.php
│
├── google/
│   ├── google_login.php
│   ├── google_callback.php
│   └── logout.php
│
├── wallet/
│   ├── add_money.php
│   ├── transfer.php
│   ├── transfer_action.php
│   ├── transaction_history.php
│   └── verify_payment.php
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── dashboard.php
├── login.php
├── register.php
├── profile.php
└── logout.php
```

---

# Installation

# Clone the Repository

```bash
git clone https://github.com/your-username/digital-wallet.git
```

# Navigate to the Project

```bash
cd digital-wallet
```

# Install Dependencies

```bash
composer install
```

# Import Database

- Open **phpMyAdmin**
- Create a new database
- Import the provided SQL file

# Configure Database

Update your database credentials inside:

```
config/config.php
```

# Configure Google Authentication

Update:

```
google/google_config.php
```

with your:

- Client ID
- Client Secret
- Redirect URI

# Configure Razorpay

Update:

```
config/razorpay_config.php
```

with your:

- Razorpay Key ID
- Razorpay Secret Key

# Run the Project

```
http://localhost/PHP/digital_wallet/
```

---

# Screenshots

> Add screenshots of your application here.

- Login Page
- Register Page
- Dashboard
- Wallet Overview
- Add Money
- Transfer Money
- Transaction History
- User Profile

---

# Security Features

- Password Hashing
- SQL Injection Protection
- Session-Based Authentication
- Secure Payment Verification
- Google OAuth Authentication
- Server-Side Validation

---

# Future Enhancements

- OTP Verification
- Email Notifications
- QR Code Payments
- UPI Integration
- Wallet ID Transfers
- Admin Dashboard
- Analytics Dashboard
- Dark/Light Theme
- Two-Factor Authentication
- AI-Based Fraud Detection

---

# Learning Outcomes

This project demonstrates practical implementation of:

- PHP & MySQL Development
- Authentication Systems
- Payment Gateway Integration
- Google OAuth
- CRUD Operations
- Session Management
- Responsive Web Design
- Database Design
- Secure Web Development
- FinTech Application Development

---

# Developer

Deeshanu Kundu

MCA Student | Full Stack Web Developer

---

# License

This project is developed for educational and learning purposes. Feel free to explore, learn, and modify the code for personal or academic use.

---

# If you found this project helpful, consider giving it a star on GitHub!
