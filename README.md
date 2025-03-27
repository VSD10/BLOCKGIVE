# BLOCKGIVE
Project Idea: Blockchain-Based Crypto Donation Platform
Project Overview
This project is a crypto donation platform that enables users to donate cryptocurrency to charities securely and transparently using blockchain technology. The platform integrates MetaMask for wallet connectivity, allowing users to donate directly from their crypto wallets. Each transaction is logged on the blockchain for full transparency, ensuring that donations reach their intended recipients.

Key Features
1. User Dashboard
Users can select charities from a predefined list or enter a custom charity name.

A real-time donation calculator dynamically updates the total amount, including estimated gas fees.

The interface includes a gradient-styled “Connect Wallet” button for users to link their MetaMask wallet.

2. Secure Donations with MetaMask
Users can connect their MetaMask wallet and donate directly.

Transactions are executed on the blockchain, ensuring security and transparency.

After submitting a transaction, users can track its progress in real-time.

3. Real-Time Transaction Tracking
A dedicated Transaction Progress page allows users to monitor the status of their donations.

Successful transactions trigger a confetti or flower animation before redirecting users to their donation history.

4. Donation History & Transparency
A Donation History page displays all past donations, categorized into:

Completed Donations (successful transactions)

In Progress Donations (pending transactions)

Refunds & Failed Transactions (if applicable)

Each transaction includes a timestamp, amount, transaction ID, and recipient details.

5. Live On-Chain Audit & Impact Tracking
A public audit page showcases all transactions in real-time.

Users can verify donations on a blockchain explorer using transaction IDs.

A fund allocation graph visually represents how funds are distributed among charities.

Tech Stack
Frontend (User Interface)
HTML, CSS (Tailwind), JavaScript (React.js/Next.js)

Web3.js or ethers.js for blockchain interaction

Backend & Blockchain Integration
Node.js + Express.js for handling API requests

Smart Contracts (Solidity on Ethereum or Binance Smart Chain) for processing donations

MongoDB / Firebase for storing non-blockchain data

Additional Enhancements
QR Code Payment Support for mobile donations.

Leaderboard & Badges for top donors to encourage contributions.

Subscription-Based Recurring Donations for continuous support to charities.
