# Speedrun Ethereum Challenge: Simple NFT

## Overview

This repository contains my work for the Speedrun Ethereum challenge, specifically "Challenge 0: Simple NFT." The goal of this challenge was to learn the basics of 🏗 Scaffold-ETH 2, compile and deploy smart contracts using 👷‍♀️ HardHat, and integrate with a React application full of essential Ethereum components and hooks. The final task was to deploy an NFT to a public network, showcasing the ability to purchase and transfer NFTs.

## Key Features

- **Smart Contract Development**: Utilized HardHat for compiling and deploying the smart contracts essential for NFT creation and handling.
- **NFT Minting and Transfer**: Implemented functionality within the React app to mint NFTs and transfer them between accounts, enhancing my understanding of Ethereum transaction flows.
- **Public Network Deployment**: Deployed the contracts to a testnet and integrated with a public web server, making the app accessible to others and demonstrating real-world blockchain application deployment.

## Development Process

### Environment Setup

- Installed Node, Yarn, and Git as prerequisites.
- Cloned the challenge repository and installed dependencies.
- Started a local blockchain emulator using `yarn chain`.

### Contract Deployment and Frontend Setup

- Deployed the smart contract locally with `yarn deploy`.
- Launched the React frontend application and interacted with the contract in a development environment.

### Gas, Wallets, and Minting

- Explored gas usage and the functionality of burner wallets for local development.
- Minted NFTs and tested the transfer functionality between different addresses.

### Deployment to Public Testnet

- Configured HardHat for deployment to the Sepolia testnet.
- Generated a deployer address and deployed the NFT smart contract to the public testnet.

### Frontend Deployment

- Edited the frontend configuration to target the Sepolia network.
- Deployed the NextJS app to Vercel, making the NFT application accessible online.

## Challenges and Learning Outcomes

- Gained practical experience in Ethereum development tools and processes, including smart contract development, testing, and deployment.
- Learned to integrate smart contracts with a React frontend, utilizing Ethereum components and hooks for a seamless user experience.
- Understood the importance of network selection and configuration for deploying Ethereum applications to public testnets.

## Next Steps

This project served as a foundational step into Ethereum development. The next challenges will involve more complex smart contract interactions, advanced frontend integrations, and exploring the broader Ethereum ecosystem's tools and services.

## Contribution

Feel free to explore the code, and suggestions or contributions are welcome. Join the discussion on the Challenge 0 Telegram for further insights and support from the Ethereum developer community.
