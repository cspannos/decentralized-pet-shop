# Decentralized Pet Shop

This Pet Shop is a proof-of-concept designed for 16 pets. It is not meant for deploymnt on the mainchain. It is adapted from the [Truffle Pet Shop Tutorial](https://truffleframework.com/tutorials/pet-shop).

## Background

Pete Scandlon of Pete's Pet Shop is interested in using Ethereum as an efficient way to handle their pet adoptions. The store has space for 16 pets at a given time, and they already have a database of pets. As an initial proof of concept, Pete wants to see a dapp which associates an Ethereum address with a pet to be adopted.

## Getting Started
The environment for this implementation relies upon:
* Linux (Debian Stretch)
* Truffle v5.0.2
* Ganache GUI (v2.0.0-beta.2) / CLI (v6.2.5)
* NPM 6.8.0

## How to install:
* Truffle: ``$ npm install truffle -g``
* Ganache: download the AppImage for GUI / CLI ``$ npm install -g ganache-cli``
* NPM: ``1. $ sudo apt-get install curl software-properties-common
       2. $ curl -sL https://deb.nodesource.com/setup_11.x | sudo bash -
       3. $ sudo apt-get install nodejs``

To spin this implementation up on your own machine, follow these steps:
- clone this repository: ``$ git clone https://github.com/cspannos/decentralized-pet-shop``;
- cd into the root directory: ``$ cd decentralized-pet-shop``;
-  run Ganache (GUI or CLI (cmd: ``$ ganache-cli``);
- use the mnemonic code that Ganache provides to open MetaMask. Place the mnemonic in MetaMask’s option to ‘Import using account seed phrase’, and initialize your account.
- in another terminal, also in the root directory, run ``$ truffle develop``;
- in another terminal: ``$ cd decentralized-pet-shop`` and run ``$ npm run dev``;

This last step will initialize a local implementation of this project and load in your browser at: http://localhost:3000.

## Author
Chris Spannos  

## Credit
This Decentralized Pet Shop is adapted from the [ConsenSys' Truffle Pet Shop Tutorial](https://truffleframework.com/tutorials/pet-shop).
