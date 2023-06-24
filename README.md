# ATF

Aurora Token Factory (ATF) is a decentralized application (dApp) that empowers users to create personalized ERC-20 tokens with ease, even without prior programming experience. It provides a user-friendly interface and leverages the Aurora network for contract deployment and interaction. The dApp also allows users to retrieve information about existing ERC-20 tokens by providing their contract addresses.

## Inspiration

The project drew inspiration from various networks and tools, such as:

- [ERC20 Generator](https://vittominacori.github.io/erc20-generator/create-token/)
- [Create My Token](https://www.createmytoken.com/token-builder/)

## Features

- Create personalized ERC-20 tokens through an intuitive user interface.
- Retrieve information about existing ERC-20 tokens by providing contract addresses.
- Interact directly with smart contracts on the Aurora network from the dApp.

## How It Works

1. The ERC-20 token template is created using Remix and compiled to obtain the ABI, bytecode, and flattened source code.
2. The frontend of the application is built using React, enabling a seamless user experience.
3. The dApp interacts with the Aurora network to deploy ERC-20 contracts based on user-provided parameters.
4. Users can also interact with existing contracts on the blockchain by leveraging the provided functionalities.
5. The dynamic interaction form is currently created using the template ABI, supporting interaction with ERC-20 tokens exclusively.

## Challenges

During development, a particular challenge was encountered with the contract verification feature. Although a functionality was implemented to verify contracts after creation, it exhibited inconsistent behavior. It is currently unclear whether the issue stems from the API or the implementation approach. The interaction form is currently limited to the template ABI, restricting support to ERC-20 tokens.

## Accomplishments

Notable achievements include:

- Successful creation of a React application, despite prior experience primarily with Angular.
- Gaining familiarity with Solidity and deploying smart contracts from a web client.
- Developing a functional product that serves as a promising initial release.

## Future Enhancements

The roadmap for Aurora Token Factory includes the following enhancements:

- Resolving the contract verification issue to provide reliable functionality.
- Enabling interaction with various types of smart contracts beyond ERC-20.
- Expanding configuration parameters for ERC-20 token creation to enhance customization options.
- Adding support for additional standards such as ERC-721 and ERC-1155.

## Getting Started

To get started with Aurora Token Factory, follow these steps:

1. Clone the repository: `git clone https://github.com/AbhiDev3/ATF.git`
2. Install dependencies: `npm install`
3. Launch the dApp locally: `npm start`
4. Access the application in your browser at: `http://localhost:3000`
