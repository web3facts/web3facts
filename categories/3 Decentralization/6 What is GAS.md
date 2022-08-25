GAS refers to the fee a user must pay to add information to a Blockchain.

Miners typically compete to process the transactions which pay the largest amount
of GAS.

The calculation of GAS depends on whether a user is:
-   Adding a new transaction
-   Using a wallet for the first time
-   Creating a contract
-   Executing a contract
-   Attaching additional data

Users are typically shown the GAS amount before they choose to proceed with a transaction.
They are also able to increase the GAS amount to attract miners and speed up their
transaction time.

This means that cost of processing a transaction depends on how busy the network is.
The more pending transactions, the more GAS is required, the more a transaction costs.

Users pay for GAS using the associated cryptocurrency. For example, on the Ethereum
network, GAS is paid for using Ether.

GAS is typically described in terms of Satoshis or Wei. These represent the smallest
amount of cryptocurrency that can be transferred between wallets. The below conversions
help to illustrate their meaning:
-   There are 100 cents within 1 dollar
-   There are 100 million Satoshis within 1 Bitcoin
-   There is 1 [quintillion](https://en.wikipedia.org/wiki/Power_of_10) Wei in 1 Ether (quintillion means 10<sup>18</sup>
-   There is 1 [billion](https://en.wikipedia.org/wiki/Power_of_10) Gwei in 1 Ether (Gwei means Giga Wei, or 10<sup>9</sup> Wei

References:
-   [Github - go-ethereum/core/state_transition/IntrinsicGas](https://github.com/ethereum/go-ethereum/blob/594e32166269eed4f5cb8270bba99fa234a41606/core/state_transition.go#L118)
-   [Github - go-ethereum/params/protocol_params](https://github.com/ethereum/go-ethereum/blob/b3b8b268eb585dfd3c1c9e9bbebc55968f3bec4b/params/protocol_params.go#L87)
-   [Etherscan - Gas Tracker](https://etherscan.io/gastracker)
