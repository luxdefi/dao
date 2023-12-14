# LUX DAO Governance Suite

## Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Quickstart](#quickstart)
- [Governance Dashboard](#governance-dashboard)
- [Release](#release)
- [Contribute](#contribute)
- [Community](#community)
- [Thank You](#thank-you)
- [License](#license)

## Overview

Lux DAO is a cutting-edge governance suite designed for on-chain governance of Lux Network's native L0, L1, and L2 layers. This suite incorporates elements from renowned platforms like Compound and MakerDAO, aiming to offer a seamless and intuitive experience in managing decentralized autonomous organizations.

## Features

- **CLI Tools**: Command Line Interface tools for streamlined interaction with the DAO's functionalities, making it accessible for both technical and non-technical users.
- **Easy-to-Use Banking**: A robust banking system integrated into the DAO for efficient management of funds, inspired by the financial models of leading DeFi platforms.
- **Proposal System**: An intuitive proposal interface that allows members to easily submit, discuss, and track proposals.
- **Voting Mechanism**: A transparent and secure voting system, enabling members to participate in the governance process effectively.
- **Governance Dashboard**: A user-friendly dashboard that provides a comprehensive overview of the DAO's governance activities, inspired by the best practices of Compound and MakerDAO.

## Architecture

Lux DAO is built on a modular architecture, consisting of Core Contracts, Adapters, Extensions, and a Governance Dashboard, each serving specific functions and collectively enhancing the DAO's capabilities.

### Core Contracts

Core contracts form the backbone of the DAO, handling state changes and serving as a registry. They include the DaoRegistry, CloneFactory, and DaoFactory.

### Adapters and Extensions

Adapters and Extensions allow for the modular assembly of DAO functionalities, ranging from governance processes to financial management. They include various specific-purpose contracts such as Configuration, Distribute, Financing, GuildKick, and others.

## Quickstart

Follow these steps for initial setup, deployment, and DApp configuration.

### Install Dependencies

```sh
yarn install
```

### Environment Setup

Create a `.env` file at the root directory and set up necessary configurations.

### Compile Contracts

```sh
yarn compile
```

### Deploy Contracts

Deploy to various networks using the provided npm scripts.

### Verify Contracts

```sh
yarn verify [network]
```

## Governance Dashboard

The Governance Dashboard is a central feature of Lux DAO, providing a clear and intuitive interface for managing governance activities. Drawing inspiration from Compound and MakerDAO, the dashboard offers:

- Real-time tracking of proposals and votes
- Detailed insights into DAO's financial status
- Easy proposal submission and voting process
- Comprehensive analytics and reporting tools

## Release

Step-by-step instructions for releasing new versions, including version bumping, tagging, and publishing.

## Contribute

Guidelines for contributing to the project, including bug reporting and suggesting enhancements.

## Community

Join the community discussion on [Discord](https://discord.gg/xXMA2DYqNf).

## Thank You

Acknowledgments to all contributors and supporters of the project.

## License

Lux DAO is released under the [MIT License](LICENSE).
