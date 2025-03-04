# GameXchange

## Overview
**GameXchange** is a secure and user-friendly platform designed for buying, selling, and auctioning game accounts. With built-in cryptocurrency payments, direct messaging, and seller verification, users can trade gaming assets with confidence.

## Features
- **Secure Crypto Transactions** – Trade game accounts using blockchain-powered payments.
- **Account Auctions** – Bid on premium accounts and secure the best deals.
- **Buyer & Seller Messaging** – Chat directly with sellers for negotiations.
- **Verified Sellers** – Ensuring authenticity and reducing fraud.
- **Super Admin Panel** – Manage users, transactions, and platform settings.
- **CMS for Sellers** – Sellers can add, update, and delete listings easily.

## Tech Stack
- **Frontend:** React.js (Next.js), Tailwind CSS, Three.js (for 3D elements)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** OAuth, JWT
- **Payments:** Crypto-based transactions (integrated via Web3 APIs)
- **Messaging System:** WebSockets (for real-time chat)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Clone the Repository
```bash
git clone https://github.com/yourusername/GameXchange.git
cd GameXchange
```

### Install Dependencies
```bash
npm install
```

### Environment Variables
Create a `.env` file in the root directory and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CRYPTO_API_KEY=your_crypto_payment_api_key
```

### Run the Application
```bash
npm run dev
```

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push to your fork and submit a Pull Request.

## License
This project is open-source under the MIT License.

