🌐 CryptoFund — Decentralized Crowdfunding Platform

A blockchain-powered crowdfunding platform that enables users to create fundraising campaigns and contribute using cryptocurrency. Built with React, TypeScript, and Ethereum Web3 integration for transparent, secure, and borderless funding.
⸻
🚀 Live Demo

👉 Click here to try the live app
⸻
📌 Problem Statement

Traditional crowdfunding platforms rely on centralized systems — leading to lack of transparency, delayed fund transfers, and high platform fees. CryptoFund leverages blockchain technology to create a transparent and trustless crowdfunding ecosystem where every transaction is publicly verifiable on the Ethereum network.
⸻
✨ Features

- 🔗 Web3 Wallet Integration — Connect MetaMask wallet with one click; auto-detects existing connections
- 💸 Create Campaigns — Launch fundraising campaigns with title, description, ETH target, and duration (1–90 days)
- 🪙 Donate with ETH — Contribute cryptocurrency directly to campaigns
- 📊 Live Progress Tracking — Real-time fundraising progress bars and days remaining
- 📱 Responsive UI — Clean, modern interface optimized for all screen sizes
- ⚡ Fast Performance — Built with Vite for lightning-fast development and production builds
- 🔐 Form Validation — Zod schema validation ensures clean, error-free campaign creation
⸻
🛠️ Tech Stack
Category	Technology
Frontend	React 18 + TypeScript
Styling	Tailwind CSS + shadcn/ui
Routing	React Router DOM v6
Forms	React Hook Form + Zod
Blockchain	Ethereum + MetaMask (Web3)
Build Tool	Vite
Deployment	Vercel
⸻
📂 Project Structure

crowdfunding-platform/
├── src/
│   ├── components/
│   │   ├── ui/                  # shadcn/ui component library
│   │   ├── CampaignCard.tsx     # Campaign display card
│   │   └── WalletConnect.tsx    # MetaMask wallet connection
│   ├── pages/
│   │   ├── Index.tsx            # Home — browse all campaigns
│   │   ├── Create.tsx           # Create new campaign form
│   │   └── CampaignDetails.tsx  # Individual campaign view
│   ├── hooks/
│   │   └── use-toast.ts         # Toast notification hook
│   ├── lib/
│   │   └── utils.ts             # Utility functions
│   └── App.tsx                  # Root component with routing
├── public/
├── index.html
├── vite.config.ts
├── tailwind.config.ts
└── package.json

⸻
⚙️ Installation & Setup

Prerequisites
- Node.js v18+
- MetaMask browser extension
- Git

Clone & Run Locally

# Clone the repository
git clone https://github.com/krishanchauhan29/crowdfunding-platform.git

# Navigate to project directory
cd crowdfunding-platform

# Install dependencies
npm install

# Start development server
npm run dev


App will run at http://localhost:5173
⸻
🔐 Environment Variables

Create a .env file in the root directory:

NEXT_PUBLIC_RPC_URL=your_rpc_url
NEXT_PUBLIC_CONTRACT_ADDRESS=your_contract_address

⸻
🖥️ Pages Overview
Page	Route	Description
Home	/	Browse all active campaigns with progress
Create	/create	Launch a new fundraising campaign
Campaign Details	/campaign/:id	View individual campaign and donate
⸻
🎯 Future Improvements

- [ ] Multi-chain support (Polygon, BSC, Arbitrum)
- [ ] NFT-based rewards for top donors
- [ ] DAO governance for platform decisions
- [ ] AI-powered campaign recommendations
- [ ] User analytics dashboard
- [ ] IPFS-based image storage for campaigns
⸻
👨‍💻 Authors
Name	GitHub	Role
Krishan Kumar Chauhan	@krishanchauhan29	Co-Developer
Aman Chaudhary	@amn-00	Co-Developer
⸻
🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

1. Fork the repo
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
⸻
📄 License

This project is open source and available under the MIT License.
⸻
⭐ If you found this project useful, consider giving it a star!


## 👨‍💻 Authors

| Name | GitHub | Role |
|------|--------|------|
| Krishan Kumar Chauhan | [@krishanchauhan29](https://github.com/krishanchauhan29) | Co-Developer |
| Aman Chaudhary | [@shivam_nagar](https://github.com/amn-00) | Co-Developer |
| Shivam Nagar | [@shivam_nagar](https://github.com/shivam_nagar) | Co-Developer |
