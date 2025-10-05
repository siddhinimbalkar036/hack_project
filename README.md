# Decentralized CrowdFunding DApp

## Team Name: 
 * Blockchain Crafters
## Team members Name: 
* Sakshi Chavan
* Siddhi Nimbalkar

               



## Project Name:
* Decentralized Crowdfunding DApp 



## Project Abstract
This project is blockchain-powered crowdfunding platform built on the Polygon Amoy Testnet. 
It allows user to create fundraising campaigns, donate using MATIC, and earn NFT rewards based on their contribution level.

key features:
* Campaign creation with goal, category, and deadline.
* Secure crypto donation via Metamask/ WalletConnect.
* Automatic refunds if the Campaign goal is not met by the deadline.
* NFT reward badges(Bronze, Silver, Gold) for donors.
* Real-time updates on Campaign progress, donor lists, and NFTS earned.



## Tech Stack
* **Blockchain & Smart Contract**: Solidity, Hardhat, OpenZeppelin(ERC721).
* **Network**: Polygon Amoy Testnet
* **Backend**:  Node.js,  MongoDB, Ethers.js, Express.js
* **Frontend**:  React.js, TailwindCSS, Web3.js/Ethers.js
* **Wallet Integration**: MetaMask, WalletConnnect
* **Deployment**: Hardhat, Render, Vercel(Next.js), MongoDB Atlas
* 
 ## Dataset Used
* Campaign and donation data are stored in the backend database like MongoDB.
* Blockchain Events are fetched directly from the Polygon Amoy Smart Contract
* 

## Quick Start
# Install dependencies
npm install          # for hardhat root
cd backend && npm install
cd ../frontend && npm install
# Compile contracts
npx hardhat compile
# Deploy to Amoy
npx hardhat run scripts/deploy.js --network mumbai
# Start backend server
cd ../backend
node server.js
# Start frontend
cd ../frontend
npm start



