# Cryptocurrency Platform

Welcome to the Cryptocurrency Platform! This platform provides a comprehensive set of features for cryptocurrency enthusiasts and traders. Below you'll find an overview of the key features, advanced wallet functionality, transaction history, robust authentication and security, and the cutting-edge technology stack used to build this platform.

## Table of Contents
1. [Comprehensive Feature Set](#comprehensive-feature-set)
    - [AI Chat Bot](#ai-chat-bot)
    - [Buy & Sell Crypto](#buy--sell-crypto)
    - [Portfolio Management](#portfolio-management)
2. [Advanced Wallet Functionality](#advanced-wallet-functionality)
    - [Wallet to Wallet Transfer](#wallet-to-wallet-transfer)
    - [Withdrawal to Bank Account](#withdrawal-to-bank-account)
    - [Add Balance to Wallet](#add-balance-to-wallet)
3. [Transaction History](#transaction-history)
    - [Withdrawal History](#withdrawal-history)
    - [Wallet History](#wallet-history)
    - [Search Coin](#search-coin)
4. [Robust Authentication and Security](#robust-authentication-and-security)
    - [Login & Register](#login--register)
    - [Two-Factor Authentication](#two-factor-authentication)
    - [Forgot Password](#forgot-password)
5. [Cutting-Edge Technology Stack](#cutting-edge-technology-stack)
    - [Backend](#backend)
    - [Frontend](#frontend)
    - [Payment Gateways](#payment-gateways)
    - [APIs](#apis)

## Comprehensive Feature Set

![Screenshot 2024-11-13 224007](https://github.com/user-attachments/assets/2f5a7079-a507-4024-9ba0-034f26f0dfbf)

### AI Chat Bot
Our AI Chat Bot is designed to handle a wide range of crypto-related queries. It leverages the Gemini API and CoinGecko API to provide real-time data on cryptocurrency values and market trends.
![Screenshot 2024-11-13 225306](https://github.com/user-attachments/assets/ea08a67a-d022-4b64-9f7b-4e02f24daa4

### Buy & Sell Crypto

![Screenshot 2024-11-13 225335](https://github.com/user-attachments/assets/7758fccb-f0c5-4f18-acec-af2d146b980a)

Facilitate smooth and user-friendly cryptocurrency transactions using payment gateways Stripe. Our platform supports a wide array of cryptocurrencies, making it easy for users to buy and sell their preferred digital assets.

### Portfolio Management
Equip your users with robust tools to monitor their investments and track performance. Our portfolio management features help users keep a close eye on their cryptocurrency assets.

## Advanced Wallet Functionality

![Screenshot 2024-11-13 224119](https://github.com/user-attachments/assets/0b443e9c-7e29-4a38-9268-4e0786922825)

### Wallet to Wallet Transfer
Securely transfer funds between wallets with our advanced wallet-to-wallet transfer feature. Ensure your transactions are safe and reliable.

### Withdrawal to Bank Account
Directly withdraw funds to bank accounts with ease. Our platform supports seamless integration with banking services to make withdrawals straightforward and quick.


### Add Balance to Wallet
Easily top up wallet balances to continue trading and investing without interruption. Our platform makes it simple to add funds to your digital wallet.

## Transaction History

### Withdrawal History
View and track past withdrawals to keep a record of all transactions. Our comprehensive history features ensure transparency and accountability.

### Wallet History
Access detailed logs of all wallet transactions to monitor and review all activity within your wallet.

### Search Coin
Effortlessly search for any cryptocurrency and provide users with essential information for informed trading decisions. Our search functionality ensures users have the data they need at their fingertips.

## Robust Authentication and Security

### Login & Register
Simple and secure user authentication processes ensure that users can easily and safely access their accounts. 

### Two-Factor Authentication
Add an extra layer of security to user accounts with two-factor authentication by sending OTP to mail using java mail sender. This feature helps protect user information and funds from unauthorized access.

### Forgot Password
Offer an OTP verification process to help users regain access to their accounts if they forget their credentials.

## Cutting-Edge Technology Stack

### Backend
- **Spring Boot**: For building scalable and robust backend services.
- **MySQL DB**: For reliable and secure data storage.
- **Spring Security**: For managing authentication and authorization.
- **Java Mail Sender**: For sending email notifications and updates.

### Frontend
- **React**: For building a dynamic and responsive user interface.
- **Tailwind CSS**: For modern, sleek, and customizable UI design.
- **Redux**: For managing application state.
- **Axios**: For handling HTTP requests.
- **React-Router-Dom**: For handling client-side routing.
- **Shadcn UI**: For providing advanced UI components.

### Payment Gateways
- **Razorpay**: For handling payments securely and efficiently.
- **Stripe**: For processing payments and managing subscriptions.

### APIs
- **Gemini API**: For real-time cryptocurrency data and trading.
- **CoinGecko API**: For comprehensive market data and crypto statistics.

## Getting Started

Follow these steps to set up and run the Cryptocurrency Platform on your local machine:

### Prerequisites
- Java 11 or higher
- Node.js 14 or higher
- MySQL Database

### Backend Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd backend
   
2. Configure application.properties
   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/yourDatabase
      spring.datasource.username=yourUsername
      spring.datasource.password=yourPassword



### Frontend Setup
1. Do npm install to install all the related dependencies
2. Do npm run dev to run the project in development environment 
