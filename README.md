<img src="Blockchain1.png" align="right" width="250px" height="300px"/>

# Blockchain Project       &nbsp; ![Static Badge](https://img.shields.io/badge/BLOCKCHAIN-B-%23F8C517)

> This is a readme file for the Blockchain project implemented in JavaScript. The project aims to create a basic blockchain and a cryptocurrency using JavaScript.


## Prerequisites
To run and test the Blockchain project, you need to have the following software installed:
- Node.js and npm (Node Package Manager)
## Project Structure
The project's file structure is as follows:

- block.js
- blockchain.js
- genesis.js
- crypto-hash.js
- blockchainapp.js
- package.json
- README.md

block.js: Contains the implementation of the Block class representing a block in the blockchain.

blockchain.js: Contains the implementation of the Blockchain class representing the blockchain.

genesis.js: Contains the code to create the genesis block, the first block in the blockchain.

crypto-hash.js: Contains the implementation of a cryptographic hash function to hash block data.

blockchainapp.js: Contains the application code to create and interact with the blockchain.

package.json: Node.js package file.
## Getting Started
Clone the repository:
- git clone <repository-url>
Install dependencies:
- npm install
Run the application:
- node blockchainapp.js

![Screenshot 2023-07-23 211505](https://github.com/Sachin001s/Blockchain/assets/128379424/046e7621-dda0-4a05-aa02-d353a0ad25d7)


![Screenshot 2023-07-23 211543](https://github.com/Sachin001s/Blockchain/assets/128379424/7b354eb3-3504-4be6-bbf4-ca08c3c55fec)

## Usage
The Blockchain project provides a basic implementation of a blockchain and a cryptocurrency. The block.js file contains the Block class with properties like index, timestamp, data, previous hash, and hash. The blockchain.js file contains the Blockchain class with methods for adding blocks to the chain, validating the chain, and replacing the chain. The crypto-hash.js file implements a simple cryptographic hash function.

You can use the blockchainapp.js file to create and interact with the blockchain. It contains example code to create a new blockchain, add blocks, and validate the chain.

The crypto-hash.js file contains the implementation for calculating the cryptographic hash of blocks using the SHA-256 algorithm.
## Contributing
Contributions to the Blockchain project are welcome! If you find any issues or have suggestions for improvement, please feel free to create a pull request.
## License
The Blockchain project is open-source and distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. Feel free to use, modify, and distribute the code for personal or commercial purposes.



