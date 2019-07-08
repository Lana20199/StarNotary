# Star Notary Dapp

This Project aim is to create dapp where user can claim a star.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Truffle: v5.0.26
OpenZeppelin: 2.1.2
truffle-hdwallet-provider: 1.0.2
Node: v10.15.2
Web3.js v1.0.0-beta.37

### Configuring your project

- Install truffle v5.0.26 
```
npm install -g truffle
```
```
truffle unbox webpack
```
- Install OpenZeppelin 
```
npm install openzeppelin-solidity
```
- Install truffle-hdwallet-provide

```
npm install --save truffle-hdwallet-provider
```

## Testing

To test code:
1: Open a command prompt or shell terminal
2: Enter the truffle develop
```
truffle develop
```
3: Compile the contract
```
comile
```
5: Migrate
```
migrate --reset
```
6: Test
```
test
```
## Run Front end

Open terminal shell in app directory 

```
npm run develop
```
Go to local host http://localhost:8080/

## Metamask
Make sure to install a Metamask extension with an imported account that have ether in order to claim a star
