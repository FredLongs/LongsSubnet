# Creating an EVM-Subnet on Avalanche

## Overview
This project establishes an EVM Subnet on the Avalanche network named **"JamesSubnet,"** featuring its native token, **GamersTokens (JAM).** The network seamlessly integrates with MetaMask, enabling the deployment and interaction with smart contracts through the injected provider on Remix.

## Project Features
This project interacts with two smart contracts: an ERC20 token and a vault contract. These contracts provide the following functionalities:

- **Token Creation**: Deploy your own ERC-20 token with customizable details such as name, symbol, and decimals.
- **Token Transfers**: Users can transfer tokens to other addresses, following the widely adopted ERC-20 standard.
- **Token Minting**: The contract owner can mint new tokens, expanding the total token supply.
- **Token Burning**: Users can burn their own tokens, reducing the overall token supply.

## Getting Started
Follow these steps to get the project up and running on your local machine.

### Prerequisites
- **Node.js** and **npm** installed on your machine.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/projectname.git
   ```
2.  Navigate into your project directory:

```bash
cd projectname
```

3. Install all dependencies:

```bash
npm install
```

4. Compile the contract using Hardhat:

```bash
npx hardhat compile
```

5. Run the deployment script:

```bash
npx hardhat run scripts/deploy.js
```
Tools Used

Unix Computer (MacOS or Linux)

Solidity

Remix/Hardhat

MetaMask

Web Browser

Author
Alfeed Longdaap

License
This project is licensed under the [Longs License]. See the LICENSE.md file for details.
