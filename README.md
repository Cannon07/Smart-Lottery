# Smart-Lottery

This Ethereum-based decentralized lottery smart contract allows participants to enter by depositing a specified amount of Ether. Once a sufficient number of participants have registered, the contract manager can initiate the lottery, randomly selecting a winner who will receive the entire Ether prize pool.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Deployment](#deployment)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This smart contract project aims to provide a transparent and decentralized way to run lotteries. It ensures fairness by randomly selecting a winner from the pool of registered players and automatically sending the prize Ether to the winner.

## Features

- **Decentralized**: The lottery is run on the Ethereum blockchain, eliminating the need for centralized intermediaries.

- **Fairness**: The winner is selected randomly from registered players, ensuring fairness.

- **Transparency**: All transactions and lottery results are publicly visible on the blockchain.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed (for running tests and scripts).
- An Ethereum wallet with test Ether for deploying the contract on the Sepolia test network.
- Ganache installed (for local development and testing).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Cannon07/Smart-Lottery.git

2. Change into the project directory:

   ```bash
   cd Solidity-Test-Project

3. Install project dependencies:

   ```bash
   npm install

## Usage

### Deployment

To deploy the contract on the Sepolia test network, follow these steps:

1. Update the deploy.js file with your wallet mnemonics and Sepolia network configuration.

2. Deploy the contract:
   
   ```bash
   node deploy.js

## Testing

To run the Mocha tests, use the following command:

```bash
npm run test
```

## Contributing

Contributions are welcome! If you find any issues or have improvements to suggest, please open an issue or create a pull request.
