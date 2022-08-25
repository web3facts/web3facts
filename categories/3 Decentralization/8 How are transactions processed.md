There are several steps involved in adding a transaction to a Proof of Work Blockchain:
1.   A user sends a transaction request to a Node on the network
2.   The Node adds the request to a list of pending transaction stored in its memory (called the mempool)
3.   The Node broadcasts the request to the rest of the network
4.   Miners read the pending transactions from a Node's mempool
5.   Miners select a pending transaction to process (usually higher value transactions are prioritized)
6.   Miners process the transaction, involving Proof of Work
7.   Miners send the transaction along with the proof to a Node
8.   The Node verifies the transaction and accepts or declines it
9.   If accepted, the users pays the miner a fee (called GAS)
10.  If accepted, the transaction is added to the Nodes Blockchain
11.  If accepted, the balance of the associated Accounts is updated within the Node's [global state](#globalstate)
12.  If accepted, the verified transaction is broadcast to the rest of the network

In Proof of Stake networks steps 4 to 7 differ in that a miner (called a validator)
is randomly selected by the network to validate the Block.

The average time taken to add a transaction ranges from seconds to hours, depending on the cryptocurrency
network involved.

Transactions can also involve Smart Contracts, in which the transaction will store
additional information that will be processed by the Smart Contract. This will typically
require more GAS than a standard transaction.

-   [Bitcoin - How Transactions Work](https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/)
-   [Ethereum - Transactions](https://ethereum.org/en/developers/docs/transactions/)
-   [Coinmarketcap - How Long Does a Bitcoin Transaction Take](https://coinmarketcap.com/alexandria/article/how-long-does-a-bitcoin-transaction-take)
-   [Coindesk - How to Check your Ethereum Transaction](https://www.coindesk.com/learn/how-to-check-your-ethereum-transaction/#:~:text=On%20average%2C%20it%20usually%20takes,network%20congestion%20at%20the%20time.)
