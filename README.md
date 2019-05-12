# Decentralized Star Notary

Decentralized Star Notary using Ethereum.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- Node.js
- NPM (This should be installed already when you install Node.js)
- Truffle(v5.0.13)
- OpenZeppelin(v2.1.2)
- Ganache (optional)



## About my token
- Name: Star Notary 123982398
- Symbol: SNT
- Address: 0x1fb6fc34d4f3bf3943d65068f0a5c22c835b7190


## Deployment
### Backend
- To run on a local Ethereum blockchain using Truffle
```
truffle develop
compile
migrate --reset
```

The server will run on port 9545

- To run on a local Ethereum blockchain using Ganache 
```
truffle console
compile
migrate --reset
```

The server will run on port 8545 (if using CLI) or 7545 (if using GUI)

- To run on Rinkeby test network
    - 1. Create a directly just under the project folder named `secrets`
    - 2. Inside that folder, store your Infura APP Secret in a file named `infura.txt`, and store your MetaMask mnemonic in a file named `mnemonic.txt`
    - 3. 
    ```
    truffle migrate --reset --network rinkeby
    ```

### Frontend
- 1. `cd app`
- 2. `npm run dev`
- 3. Go to `localhost:8080`





