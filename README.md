# ERC20 Smart Contract Testing

## Project Description
This project involves creating and testing an ERC20 smart contract using Hardhat. As part of the assignment, both the original and modified versions of the contract were developed and tested.

## Team Members

- **Daniarbek Madiyar**
- **Zholdybayev Didar**
- **Zhumabayev Alibek**

## Features

The project includes:

- Creation of an ERC20 token named `AITU_SE-2316-17_Token`.
- Deployment of an ERC20 token with an initial supply of 2000 tokens.
- Implementation of additional functions to retrieve transaction details:
  - Retrieve and display transaction information.
  - Get the block timestamp of the latest transaction in a human-readable format.
  - Retrieve the sender and receiver addresses of the last transaction.
- Bonus: Deployment of the custom ERC20 token on a testnet blockchain using MetaMask (optional).

## Installation and Execution

### Install Dependencies
```sh
npm install
npx hardhat
```

### Compile the Smart Contract
```sh
npx hardhat compile
```
![part1](https://github.com/user-attachments/assets/e8f8b38f-fe92-479f-bdd3-8dbecfcce502)

### Deploy Smart Contract to Ganache
```sh
npx hardhat run scripts/deploy.js --network ganache
```
![part11](https://github.com/user-attachments/assets/68f7cf0a-3e33-4e14-857a-a40d80ecc5b5)

### Check Transaction Details
```sh
npx hardhat run checkTransaction.js --network ganache
```
![part111](https://github.com/user-attachments/assets/d4f6ba9d-ab75-483f-843c-8fef0861a14e)

## Deployment & Transaction Example

**Contract Deployment:**
```
Token deployed to: 0x83218065d73FC6108CECBccA510340B52442cB95
```

**Transaction Example:**
```
Owner balance: 1990.0 tokens
Recipient balance: 10.0 tokens
Transferred 10.0 tokens to 0x7D439659b195515C5E5D9B95c037F7dA327670A7
Owner balance after transfer: 1980.0 tokens
Recipient balance after transfer: 20.0 tokens
Last transaction sender: 0x20AC9092433CFcc33bc242fF9f1580a3ed651fA7
Last transaction receiver: 0x7D439659b195515C5E5D9B95c037F7dA327670A7
Last transaction timestamp: 1738506587
```

## Useful Links

- [Hardhat Documentation](https://hardhat.org/tutorial)
- [Hardhat Testing Guide](https://hardhat.org/tutorial/testing-contracts)
- [Hardhat Contract Deployment](https://hardhat.org/hardhat-runner/docs/guides/test-contracts)
- [ERC20 Contract Example](https://solidity-by-example.org/app/erc20/)

## License

This project is licensed under the terms specified in the LICENSE file.

---

*Project completed as part of the Blockchain Technologies 1 course.*





