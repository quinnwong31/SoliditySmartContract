# SoliditySmartContract

## Description

In this sample application, we create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. The smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

We will be performing the following steps for this Challenge:

- Create a Joint Savings Account Contract in Solidity

- Compile and Deploy Your Contract in the JavaScript VM

- Interact with Your Deployed Smart Contract

## Technologies

This example uses the following technologies:

- **Ethereum** - Ethereum is a decentralized, open-source blockchain with smart contract functionality.
- **Solidity** - Solidity is a statically-typed curly-braces programming language designed for developing smart contracts that run on Ethereum.
- **Remix IDE** - Remix IDE is an open-source, browser based tool that allows developers to create and test smart contracts using Solidity.

## Screenshots

### 1. The `setAccounts` function.

In this section, we use the `setAccounts` function to define the authorized Ethereum address that will be able to withdraw funds from your contract. The two addresses that we use are:

```
Dummy account1 address: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
Dummy account2 address: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0
```

![setAccount](/Execution_Results/setAccounts.jpg)

### 2. The `deposit` function.

In this section, we test the `deposit` functionality of the smart contract by sending the 1, 10 and 5 ether to the contract. After each transaction, use the contractBalance function to verify that the funds were added to the contract:

Transaction 1: Send 1 ether as wei.

![Send 1 ether as wei](/Execution_Results/deposit_1_ether.jpg)

Transaction 2: Send 10 ether as wei.

![Send 10 ether as wei](/Execution_Results/deposit_10_ether.jpg)

Transaction 3: Send 5 ether.

![Send 5 ether as wei](/Execution_Results/deposit_5_ether.jpg)

### 3. The `withdraw` function.

In this section, we test the contract’s `withdraw` functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the `contractBalance` function to verify that the funds were withdrawn from your contract. Also, use the `lastToWithdraw` and `lastWithdrawAmount` functions to verify that the address and amount were correct.

Transaction 1: Withdraw 5 ether

![Withdraw 5 ether](/Execution_Results/withdraw_5_ether.jpg)

Transaction 2: Withdraw 10 ether
![Withdraw 10 ether](/Execution_Results/withdraw_10_ether.jpg)

## Contributors

This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/

## License

The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
