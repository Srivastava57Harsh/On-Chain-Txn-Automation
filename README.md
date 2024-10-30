# On-Chain Transaction Automation Using Intents

This project aims to streamline on-chain transaction processes by enabling users to interact with decentralized applications (dApps) through natural language intents. By leveraging UserOp.js and large language models (LLMs), users can perform blockchain transactions using straightforward commands, reducing the complexity associated with traditional dApp interactions.

## Overview

Traditional blockchain transactions require users to interact with complex dApp interfaces, manage wallets, input details, and sign transactions manually, often causing friction for both technical and non-technical users. This project enables users to bypass such intricate steps by automating on-chain transactions via intent-based inputs. Users can specify commands like "send 1 ETH to address X," which are then processed and executed on-chain, enhancing accessibility and usability.

## Key Components

- **Frontend (Next.js)**: Provides a user interface for intent-based input and transaction status display.
- **Backend (UserOp.js)**: Processes user intents, converts them to transaction objects, and handles blockchain commands.
- **Intent Handling with LLMs**: Natural language commands are parsed into structured transaction data for automated execution.

## Features

- **Natural Language Interface**: Users can express transaction intents using simple, everyday language.
- **Automated Transaction Workflow**: The system automates user interactions such as wallet connection and transaction signing.
- **Error Reduction**: Automated input validation reduces user errors, such as incorrect addresses or gas limit settings.
- **Cross-dApp Automation**: Enables multi-step dApp interactions through a single intent, facilitating complex workflows.

## Project Structure

- `frontend/` - Built with Next.js, manages user interface and intent input.
- `backend/` - Processes intents using UserOp.js and connects with the blockchain.
- `intentProcessor.js` - Handles natural language parsing, converts commands into executable transaction objects.
- `userop.js` - Integrates with wallets and manages the execution of transactions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Srivastava57Harsh/On-Chain-Txn-Automation.git
   ```

## Install dependencies:
  ```
  cd On-Chain-Txn-Automation
  npm install
```

## Configure environment variables for blockchain network, wallet, and API keys.

## Start the frontend and backend:
  ```
  npm run start
  ```

## Usage:
- Connect your wallet using MetaMask.
- Enter a transaction intent (e.g., "send 0.5 ETH to 0xABC123...").
- Review the generated transaction details.
- Confirm to execute the transaction on-chain.

## License
This project is licensed under the MIT License.

