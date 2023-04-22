# The_Ohara_Protocol
## Overview
 This repository contains the source code of the Ohara Protocol, an E-Book trading system based on the ERC-1155 standard running on the Arbitrum blockchain.

 It allows publishers to mint their E-Books as NFTs and sell them to buyers. The system utilizes the Arbitrum chain for its high throughput and low transaction fees, providing a seamless and efficient E-Book trading experience for all parties involved.
 
 This project is still under development, and we welcome any suggestions for improvement. You can help us identify issues by using the "Issues" tab above. Your feedback is valuable and we appreciate your contribution to the project's development.
## Installation
 Please clone this repository and run
 ```bash
 npm install
 ```
 under the project root directory.
 
 Now, you can use truffle to develop and test this project.

 Use

 ```bash
 truffle migrate --network goerli
 ```
 
 to upload the contract and proxy on chain.

 Finally, use

 ```bash
 cd django-on-docker && docker-compose up -d --build
 ```

 to run the server.

 If you don't have docker & docker-compose, go get them.

 Then, you can use url like "https://localhost:8000/balanceOf/?account=YOUR_ACCOUNT&id=ID" to interact with the contract.