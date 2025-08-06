# Ainur Opora Dapp

A platform for private therapeutic sessions with AI on the blockchain, offering full data protection through Hardhat and fully homomorphic encryption (FHE) using the FHEVM protocol by Zama (https://zama.ai/). We turn interaction with AI into a secure space — like a blockchain-based journal, therapy, or mental coach.
Платформа для приватных терапевтических сессий с ИИ на блокчейне с полной защитой данных на базе Hardhat с использованием полностью гомоморфного шифрования (FHE) и протокола FHEVM от Zama (https://zama.ai/). Превращаем взаимодействие с ИИ в безопасное пространство: как блокчейн-дневник, терапия или ментальный тренер.

### Prerequisites

- Node.js: Version v20.19.4
- npm:     10.8.2

Cloning my GitHub repository locally.

```bash
PS <my-preferred-location> 
git clone https://github.com/aikasha849/ainur-opora-dapp.git

# Navigate to the root of my new project
PS <my-preferred-location\ainur-opora-dapp>

### Installation

1. **Install dependencies**
   ```bash
   npm install
   ```
2. **Set up environment variables**

   ```bash
   npx hardhat vars set MNEMONIC
   
   # Set my Infura API key for network access
   npx hardhat vars set INFURA_API_KEY
   
   # Optional: Set Etherscan API key for contract verification
   npx hardhat vars set ETHERSCAN_API_KEY
   ```

4. **Compile and test**
   ```bash
   npm run compile
   npm run test
   ```
5. **Deploy to local network**
   ```bash
   # (Optional) Start local Anvil instance
   anvil
   # Deploy to local network
   npx hardhat deploy
   ```
6. **Deploy to Sepolia Testnet**
   ```bash
   # Deploy to Sepolia
   npx hardhat deploy --network sepolia
   # Verify contract on Etherscan
   npx hardhat verify --network sepolia <CONTRACT_ADDRESS>
   ```

## 📁 Project Structure

```
ainur-opora-dapp/
├── contracts/           # Smart contract source files
│   └── FHECounter.sol   # Example FHE counter contract
├── deploy/              # Deployment scripts
├── tasks/               # Hardhat custom tasks
├── test/                # Test files
├── hardhat.config.ts    # Hardhat configuration
└── package.json         # Dependencies and scripts
```
## 📜 Available Scripts for local development and testing
The following npm scripts streamline local development, testing, and maintenance of the smart contracts.  
They are especially helpful for collaboration with Zama and for continued experimental evolution of the Ainur Opora Dapp.

| Script             | Description              |
| ------------------ | ------------------------ |
| `npm run compile`  | Compile all contracts    |
| `npm run test`     | Run all tests            |
| `npm run coverage` | Generate coverage report |
| `npm run lint`     | Run linting checks       |
| `npm run clean`    | Clean build artifacts    |

## 📚 Documentation ZAMA

- [FHEVM Documentation](https://docs.zama.ai/fhevm)
- [FHEVM Hardhat Setup Guide](https://docs.zama.ai/protocol/solidity-guides/getting-started/setup)
- [FHEVM Testing Guide](https://docs.zama.ai/protocol/solidity-guides/development-guide/hardhat/write_test)
- [FHEVM Hardhat Plugin](https://docs.zama.ai/protocol/solidity-guides/development-guide/hardhat)

## 📄 License ZAMA

This project is licensed under the BSD-3-Clause-Clear License. See the [LICENSE](LICENSE) file for details.

## 📞 Contacts

Author: Ainur
Telegram: @AinurSolar
X (Twitter): @InurSolar91279
Farcaster: farcaster.xyz/ainur-zk1
Email: jeneshka883@gmail.com
---

**Built with ❤️ by the Ainur$ZAMA**

