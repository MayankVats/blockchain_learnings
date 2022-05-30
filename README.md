# Blockchain Learning

## Basics Of Blockchain

### Introduction

The blockchain can be seen as a type of data structure which stores data in blocks and each block is related to its next block with the help of its hash value. All of the data of blockchain is stored on multiple nodes(a computer machine or a server) instead of a single central database. Each node agrees on the data that is stored on them and be in sync with each other with the help of a consensus mechanism.

### What is a Block ?

Before starting to learn about what blockchain is let us first understand What a "block" is. A **block** is a just a bunch of data, a collection of records or a records of transactions stored in a container which we call block.

For the Bitcoin blockchain, this data is just a list of transactions saying: <br>
_X Pays Y $50_ <br>
_A Pays B $40_ <br>
_C Pays D $200_ <br>
and so on.

For the Ethereum blockchain, this data is also a list of transactions, the transactions are not only for sending currency or **value** (ETH in this case) but also for the interactions with the smart contract code which runs on Ethereum Virtual Machine (EVM). You can learn about the EVM and the smart contracts on the ethereum basics branch.

To visualize what a Block is you can check [this](https://andersbrownworth.com/blockchain/block) out. To see the bitcoin block click [here](https://www.blockchain.com/btc/block/00000000000000000003a79ab7cb64861884754adea7b5385651ba3c037f893c) and to see the ethereum block click [here](https://etherscan.io/block/14870857).

So, the blockchain can be seen as a type of data structure which stores data related to value transfers or smart contract function calls or any other data into a block. Storing a lot of data in a single block is not efficient, the blocks in the blockchain have limit over how much data they can store, because of this reason there is more than one block in a blockchain.

### Anatomy of a Block

![Block]("./assets/block.jpg")
