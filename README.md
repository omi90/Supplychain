# Ethereum DApp for Tracking Items Through the Supply Chain using Solidity

## UML Architecture Diagrams

- **[Activity Diagram](./UML/UML-Diagrams-Activity-Diagram.png):** 

- **[Sequence Diagram](./UML/UML-Diagrams-Sequence-Diagram.png):** 
- **[State Diagram](./UML/UML-Diagrams-State-Diagram.png):** 

- **[Class Diagram](./UML/UML-Diagrams-Class-(Data-Modeling).png):** 

## Project Write-up - Libraries

### Programming Libraries Used:
- **Truffle v5.8.1 (core: 5.8.1):** used to deploy and test smart contracts.
- **Solidity v0.5.16 (solc-js):** high-level langauge for writing smart contracts.
- **Node v18.15.0:** used for building web applications quickly
- **Web3.js v1.8.2:** used to allow the smart contracts to interact with a local/remote Ethereum node with an HTTP, HTTPS, or IPC connection.

### Technologies used:
- **Ganache:** used to deploy and test the DApp in environment before deploying.
- **Visual Studio Code:** IDE

## General Write Up

### Contracts Address:**
1. **Deploying 'Migrations'**
[0x8d5267dAffACf7d750109e326A58c80359088fbD](https://etherscan.io/address/0x8d5267dAffACf7d750109e326A58c80359088fbD)

2. **Deploying Contracts:**
FarmerRole:
[0xeCd3626D8e4b6f81fE48DCbb7ffC929d81875C46](https://etherscan.io/address/0xeCd3626D8e4b6f81fE48DCbb7ffC929d81875C46)

DistributorRole:
[0x1Af256C6b6538c26C9BA469E1E7512543C6797D1](https://etherscan.io/address/0x1Af256C6b6538c26C9BA469E1E7512543C6797D1)

RetailerRole:
[0x31FC740144FF2A692329eD9d1dEB0CD062d9FED9](https://etherscan.io/address/0x31FC740144FF2A692329eD9d1dEB0CD062d9FED9)

ConsumerRole:
[0x7ca1BdCb83c8fF41Ee6FE1F03a0Ffb83cd2a7C51](https://etherscan.io/address/0x7ca1BdCb83c8fF41Ee6FE1F03a0Ffb83cd2a7C51)

SupplyChain:
[0xc58Fdd175E542E5e062dA6451E2D29FABEA3FC58](https://etherscan.io/address/0xc58Fdd175E542E5e062dA6451E2D29FABEA3FC58)


### Deploying Contracts Terminal Window:**
1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0xd2d1dbea4d80d22da775bc615dde1980dfbeeb84a584760424f85fe7d01d8dbf
   > Blocks: 1            Seconds: 13
   > contract address:    0x8d5267dAffACf7d750109e326A58c80359088fbD
   > block number:        3233085
   > block timestamp:     1680718920
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.44714092
   > gas used:            238256 (0x3a2b0)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00476512 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00476512 ETH


2_deploy_contracts.js
=====================

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x1e429e55262894f1e3acf9fd695f9a509d0efae3605d6b12ce3585dd93616650
   > Blocks: 2            Seconds: 17
   > contract address:    0xeCd3626D8e4b6f81fE48DCbb7ffC929d81875C46
   > block number:        3233088
   > block timestamp:     1680718956
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.44009
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x6fee62d8780ef7796cee5a9fbd7ae27e38102cafb6479a47d4d105b42397ac57
   > Blocks: 1            Seconds: 13
   > contract address:    0x1Af256C6b6538c26C9BA469E1E7512543C6797D1
   > block number:        3233090
   > block timestamp:     1680718980
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.43395468
   > gas used:            306766 (0x4ae4e)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613532 ETH


   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x0f69022d9b309cfe283561bd38aea6e5117e3bed2f5358c0b37f1dc9022e025b
   > Blocks: 0            Seconds: 13
   > contract address:    0x31FC740144FF2A692329eD9d1dEB0CD062d9FED9
   > block number:        3233091
   > block timestamp:     1680719004
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.42781912
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x1990f9e8d657442e8229a68c37d89bed4e872e891d1e4d5d6ab8ed31e1819685
   > Blocks: 2            Seconds: 13
   > contract address:    0x7ca1BdCb83c8fF41Ee6FE1F03a0Ffb83cd2a7C51
   > block number:        3233093
   > block timestamp:     1680719028
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.42168356
   > gas used:            306778 (0x4ae5a)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.00613556 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0xfb52b978edca343752521cedfc2a54e1e6dfdbde34f90ae036c5dd4a4345b788
   > Blocks: 2            Seconds: 17
   > contract address:    0xc58Fdd175E542E5e062dA6451E2D29FABEA3FC58
   > block number:        3233095
   > block timestamp:     1680719052
   > account:             0x1aD17bDC4D69eA5f6439322a56E76AaD2f9F8a52
   > balance:             0.38457662
   > gas used:            1855347 (0x1c4f73)
   > gas price:           20 gwei
   > value sent:          0 ETH
   > total cost:          0.03710694 ETH

   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.06164894 ETH

Summary
=======
> Total deployments:   6
> Final cost:          0.06641406 ETH