# CryptoMine - Cryptocurrency Exchange & Mining Platform

A full-stack cryptocurrency exchange and mining platform built with Next.js, Node.js, and MongoDB.

## Features

- **Buy & Sell Cryptocurrencies**: Trade multiple crypto assets
- **Mining Operations**: Mine various cryptocurrencies
- **Wallet Management**: Store and manage crypto assets
- **Trading Pairs & Order Books**: Real-time trading interface
- **User Authentication**: Secure KYC/AML compliance
- **Dashboard**: Monitor portfolio and mining operations

## Project Structure

```
cryptomine/
├── frontend/          # Next.js application
├── backend/           # Node.js/Express API
├── shared/            # Shared utilities and types
└── docs/              # Documentation
```

## Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn
- MongoDB 4.4+

### Installation

1. Clone the repository
```bash
git clone https://github.com/sntseason-lgtm/cryptomine.git
cd cryptomine
```

2. Install dependencies
```bash
npm install
cd frontend && npm install
cd ../backend && npm install
```

3. Set up environment variables
```bash
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env.local
```

4. Start MongoDB
```bash
mongod
```

5. Run the development servers
```bash
# Terminal 1: Backend
cd backend && npm run dev

# Terminal 2: Frontend
cd frontend && npm run dev
```

Visit `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend API.

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Blockchain**: Web3.js / Ethers.js
- **Authentication**: JWT

## License

MIT
