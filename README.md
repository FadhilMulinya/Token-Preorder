# XYL Token Pre-Order Registration

A web application for registering interest in the upcoming XYL token launch on the Polygon network.

---

## Setup

### Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- A wallet like [MetaMask](https://metamask.io/) configured for the Polygon network

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/xyl-token-registration.git
cd xyl-token-registration
```

### 2. Environment Setup
Create a `.env.local` file in the root directory with:
```env
NEXT_PUBLIC_PROJECT_ID=your_walletconnect_project_id
```
- Get your WalletConnect Project ID from [WalletConnect Cloud](https://cloud.walletconnect.com/)

### 3. Install Dependencies
```bash
npm install
# or
yarn install
```

### 4. Start the Development Server
```bash
npm run dev
# or
yarn dev
```
The app will be available at [http://localhost:3000](http://localhost:3000)

---

## Features

- Secure registration form for XYL token pre-orders
- Web3Modal wallet connection integration
- Automatic wallet address detection
- Mobile-responsive design
- Investment amount specification
- User information collection (name, email)

---

## Usage

1. **Access the Registration Form**
   - Visit the registration page
   - Fill in your personal details:
     - Full Name
     - Email Address
     - Investment Amount

2. **Connect Your Wallet**
   - Click the "Connect Wallet" button
   - Select your preferred wallet (MetaMask, WalletConnect, etc.)
   - Your wallet address will be automatically populated

3. **Submit Registration**
   - Review your information
   - Click "Submit" to register your interest
   - Receive confirmation of your registration

---

## Technical Stack

- Next.js 14 (App Router)
- TypeScript
- Ethers.js
- Web3Modal
- Tailwind CSS

---

## Security & Privacy

- All form submissions are securely processed
- Wallet connections are handled through Web3Modal's secure infrastructure
- Personal information is handled according to privacy best practices

---

## Development Status

🚧 **Under Construction** 🚧

The XYL token registration system is currently in development. Features and functionality may be added or modified.

---
