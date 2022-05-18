# Joint-Savings-Smart-Contract

A Solidity smart contract that governs usage of a joint savings account. The contract accepts multiple user addresses and supports Ether transactions.

First, the contract creates variables for two Ethereum accounts and a balance for the contract. Next, the contract defines functions for withdrawals and deposits. Within the contract, the user must select an amount and a recipient for each withdrawal transaction.

The contract includes requirements to ensure the recipients are valid Ethereum addresses, that there are sufficient funds in the contract to support the transaction, along with a fallback function.

Features also exist within the Remix UI to check the contract balance, last account to withdraw, and last withdrawal amount.

---

## Technologies

The Joint-Savings-Smart-Contract app is written in Solidity and uses the web3 library.
The web interface is rendered using the Remix IDE.
JavaScript VM supports deployment of the smart contract.
Ganache provides the Ethereum blockchain, including transactions and hashing.

---

## Installation Guide

This app can be run in any browser using Remix and Ganache.

---

## Contributors

The Joint-Savings-Smart-Contract app was written by Kyle Huber in May 2022.

---

# Joint-Savings-Smart-Contract
