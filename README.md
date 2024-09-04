# To Do List using NextJS

This project is a full-stack To-Do List application that leverages Blockchain technology to provide a secure and Decentralized way of managing tasks. The front-end of the application is built using NextJS, a popular React framework, while the smart contract is deployed and managed using Remix. EthersJS, a JavaScript library for interacting with Ethereum networks, is used to communicate with the deployed smart contract. By integrating blockchain technology, this application offers benefits such as immutability, transparency, and tamper-proof task management.

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Go to https://remix.ethereum.org/, and deploy the smart contract on your choice of blockchain. Copy and paste the abi and contract address along with rpc-url of the blockchain network in /Utils/config.js. Also get the private key from your metamask account. 


Once you have done everthing above, simply run the following command to make the server running

```shell
npm run dev
```
