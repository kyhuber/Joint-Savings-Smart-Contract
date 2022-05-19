# Joint-Savings-Smart-Contract

A Solidity smart contract that governs usage of a joint savings account. The contract accepts multiple user addresses and supports Ether transactions.

There are three functions in the contract with differing inputs.
Deposit: Takes a value in wei, gwei, finney, or ether and credits the amount to the contract balance.
Set Accounts: Takes two account addresses to be used for withdrawal.
Withdraw: Takesan amount in Wei and a recipient address.

![Deposit setAccounts withdraw](https://user-images.githubusercontent.com/69730757/169377160-5321fb7d-e91f-4c0e-ad8a-c9c73650740a.png)

The contract allows the user to check the contract balance, view the last address to withdraw, and the last withdrawal amount.

![contractBalance lastToWithdraw lastWithdrawalAmount](https://user-images.githubusercontent.com/69730757/169377179-f487eee8-e710-4a38-b3bf-9cba51ef7fae.png)

The Joint Savings Smart Contract includes requirements to ensure the recipient address matches one of the accounts provided. There is a requirement to ensure there are sufficient funds in the contract to support the withdraw transaction, along with a fallback function.

Screenshots from successful transactions are contained within the Image folder of this repository.

---

## Technologies

The Joint-Savings-Smart-Contract app is written in Solidity and uses the web3 library.
The web interface is rendered using the Remix IDE.
JavaScript VM supports deployment of the smart contract.
Ganache provides the Ethereum blockchain, including transactions and hashing.
https://vanity-eth.tk/ was used to generate ETH addresses for testing.

---

## Installation Guide

This app can be run in any browser using Remix IDE.

---

## Contributors

The Joint-Savings-Smart-Contract app was written by Kyle Huber in May 2022.

---

# Joint-Savings-Smart-Contract
