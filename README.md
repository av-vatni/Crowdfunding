# 🚀 Web3 Crowdfunding Platform  

Welcome to the **Web3 Crowdfunding Platform** – a fully decentralized, blockchain-powered crowdfunding app! Whether you're an innovator seeking funds or a supporter looking to back great ideas, this platform makes fundraising **transparent, secure, and easy**.  

---

## 🎯 Why This Project?  

💡 **No Middlemen** – 100% of contributions go directly to the campaign owner.  
🔐 **Secure & Transparent** – Smart contracts ensure fair and automatic transactions.  
⚡ **Super Easy to Use** – Connect your crypto wallet and start in seconds!  

---

## 🚀 Features  

✔ **Create Campaigns** – Set up a crowdfunding campaign with ease.  
✔ **Seamless Wallet Connection** – Log in using your crypto wallet (MetaMask, WalletConnect).  
✔ **Live Funding Updates** – Track donations in real-time on the blockchain.  
✔ **Secure Contributions** – Funds are locked in a smart contract until the goal is met.  
✔ **Responsive UI** – Works perfectly on all devices!  

---

## 🛠 Tech Stack  

**Frontend:** Next.js, TypeScript, Tailwind CSS  
**Backend:** Solidity Smart Contracts (deployed via thirdweb)  
**Blockchain:** Ethereum (via thirdweb SDK)  

---

## 📂 Project Structure  

```
web3-crowdfunding-app/
├── components/         # UI components (buttons, forms, etc.)
├── context/            # Global state management
├── pages/              # Next.js routes
├── public/             # Static assets (logos, images)
├── smart-contract/     # Solidity contract for crowdfunding logic
├── styles/             # CSS & Tailwind styling
├── utils/              # Helper functions
├── .env                # Environment variables
├── next.config.js      # Next.js configuration
└── package.json        # Dependencies & scripts
```

---

## 🔧 Getting Started  

### 1️⃣ Clone This Repository  
```sh
git clone https://github.com/thirdweb-example/web3-crowdfunding-app-youtube.git
cd web3-crowdfunding-app-youtube
```

### 2️⃣ Install Dependencies  
```sh
yarn install
```

### 3️⃣ Set Up Your Environment  
Create a `.env` file in the root directory and add:  
```sh
NEXT_PUBLIC_CONTRACT_ADDRESS=<Your_Smart_Contract_Address>
NEXT_PUBLIC_ALCHEMY_API_KEY=<Your_Alchemy_API_Key>
NEXT_PUBLIC_WALLET_CONNECT_PROJECT_ID=<Your_Wallet_Connect_Project_ID>
```

### 4️⃣ Start the Development Server  
```sh
yarn dev
```
🔹 Open [http://localhost:3000](http://localhost:3000) in your browser.  

---

## 📜 Deploying the Smart Contract  

The crowdfunding smart contract is in `smart-contract/`. If you need to deploy it:  
```sh
npx thirdweb deploy
```
Then update the **contract address** in `.env` and `constants.ts`.  

---

## 🏗 Building for Production  

Optimize your project for deployment:  
```sh
yarn build
```

---
