# P2P Lending Protocol

A decentralized peer-to-peer lending marketplace built on Ethereum that enables direct lending between users without intermediaries.

## 🌟 Features

### For Borrowers
- **Create Loan Requests**: Set your desired amount, interest rate, and duration
- **Get Instant Funding**: Receive ETH immediately when a lender funds your loan
- **Flexible Terms**: Choose your own loan parameters
- **Track Progress**: Monitor all your loans in the Portfolio dashboard

### For Lenders
- **Browse Marketplace**: View all available loan requests with filters
- **Fund Loans**: Choose loans that match your risk/return preferences
- **Earn Interest**: Receive principal + interest when loans are repaid
- **Portfolio Tracking**: Monitor all funded loans and returns

### Smart Contract Features
- **No Platform Fees**: 100% of interest goes to lenders
- **Automated Execution**: Smart contracts handle all transactions
- **Transparent**: All loan terms and transactions on-chain
- **Secure**: Built with ReentrancyGuard and proper access controls

## 🚀 Live Demo

**Contract Address (Sepolia):** `0x4dcfb9a7029a1611468Ab8BeA3Fc49f5F8d751C5`

**Requirements:**
- MetaMask wallet
- Sepolia testnet ETH
- Switch to Sepolia network

## 💻 How to Use

1. **Connect Wallet**: Click "Connect MetaMask" and switch to Sepolia network
2. **Get Test ETH**: Visit [Sepolia Faucet](https://sepoliafaucet.com/) for free test ETH
3. **Explore Marketplace**: Browse available loans or create your own
4. **Start Lending/Borrowing**: Fund loans or create loan requests

## 🎯 Interface Overview

### Marketplace Tab
- **Live Statistics**: Total loans, available loans, volume, average interest
- **Advanced Filters**: Filter by status, amount, interest rate, duration
- **Search Function**: Find specific loans by ID
- **Clear Indicators**: Visual distinction between your loans and others

### Borrow Tab
- **Loan Calculator**: Preview total repayment before creating
- **Instant ID Assignment**: Get unique loan ID immediately
- **Status Tracking**: Monitor loan from creation to repayment

### Portfolio Tab
- **Complete Overview**: All your loans as borrower and lender
- **Summary Statistics**: Total borrowed, lent, owed amounts
- **Action Buttons**: Repay loans with one click
- **Performance Tracking**: Monitor returns and repayments

## 🔧 Technical Details

- **Blockchain**: Ethereum (Sepolia Testnet)
- **Smart Contract**: Solidity 0.8.20
- **Frontend**: Vanilla JavaScript with Ethers.js
- **Wallet**: MetaMask integration
- **Interest Calculation**: Basis points (1000 = 10%)

## 🛡️ Security

- **ReentrancyGuard**: Prevents reentrancy attacks
- **Access Controls**: Only authorized users can perform actions
- **Input Validation**: Prevents invalid loan parameters
- **Overflow Protection**: Built into Solidity 0.8+

## 📱 Mobile Friendly

The interface is fully responsive and works on:
- Desktop browsers
- Mobile browsers with MetaMask
- Tablet devices

## 🌐 Deployment

This DApp is deployed on GitHub Pages and can be accessed by anyone with:
- A modern web browser
- MetaMask wallet extension
- Access to Sepolia testnet

Perfect for testing P2P lending functionality without using real money!