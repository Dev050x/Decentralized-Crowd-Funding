# Web3 Crowdfunding App

This Web3 crowdfunding application allows users to create campaigns, contribute to them, track progress, and manage tier-based rewards. It leverages Solidity smart contracts for decentralized logic and is built using Remix IDE, Thirdweb, and the Thirdweb SDK to enable scalable deployment and seamless contract management.

## LINK

https://www.youtube.com/watch?v=r_kjdqbPFiM

## Features

- **Tier Management**: Campaign creators can define contribution tiers with varying rewards based on the amount contributed.
- **Campaign Tracking**: Users and creators can track the campaign’s progress, including total funds raised and remaining time.
- **Refund Mechanism**: If a campaign fails to reach its funding goal, contributors are automatically refunded.
- **Decentralized**: Powered by Solidity smart contracts on the Ethereum blockchain for transparency and security.
- **Scalable Deployment**: Utilizes Thirdweb SDK for simple contract management and scalability.

## Tech Stack

- **Solidity**: Smart contracts for crowdfunding logic, including tier management, fund collection, and refunds.
- **Remix IDE**: Development and deployment environment for writing and testing Solidity contracts.
- **Thirdweb SDK**: Interface for managing smart contract deployments and interactions.
- **Ethereum**: Blockchain for executing transactions and managing crowdfunding campaigns.

## Installation

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn
- Remix IDE (for smart contract development and deployment)
- A wallet (e.g., MetaMask) for interacting with the Ethereum network

## Installation

Install the template using [thirdweb create](https://portal.thirdweb.com/cli/create)

```bash
  npx thirdweb create app --next
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

`CLIENT_ID`

To learn how to create a client ID, refer to the [client documentation](https://portal.thirdweb.com/typescript/v5/client). 

## Run locally

Install dependencies

```bash
yarn
```

Start development server

```bash
yarn dev
```

Create a production build

```bash
yarn build
```

Preview the production build

```bash
yarn start
```

## Resources

- [Documentation](https://portal.thirdweb.com/typescript/v5)
- [Templates](https://thirdweb.com/templates)
- [YouTube](https://www.youtube.com/c/thirdweb)
- [Blog](https://blog.thirdweb.com)

## Need help?

For help or feedback, please [visit our support site](https://thirdweb.com/support)
