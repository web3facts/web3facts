There is no simple answer to this question. There are many ways to measure efficiency,
and each cryptocurrency network works differently. The below answers focus on Energy
Consumption, Storage and Speed.

## Energy

Networks which utilize Proof of Work are significantly less energy efficient when
compared to traditional centralized financial services.

This is due to the large amounts of power consumed by the miners. The energy consumed in this case has been
compared to the energy consumption of an [entire country](https://www.bbc.com/news/technology-56012952).

Networks which utilize Proof of Stake are more comparable with traditional centralized services.
The bulk of the energy consumed by Proof of Stake network is consumed by the Nodes within network.
The energy consumption is high as all Nodes within the network must perform the same transactions
to assure the Blockchain is consistent.

Below is a rough comparison between Paypal and three popular Proof of Stake networks.
The per transaction energy consumption of the selected networks ranges from roughly
20 to 2500 times Paypal's 2020 energy consumption.

| Metric                                  | Paypal      | Avalanche | Cardano | Solana |
| --------------------------------------- | ----------- | --------- | ------- | ------ |
| Nodes                                   | -           | 1084      | 3002    | 1015   |
| Market Cap ($ Billions)                 | 220         | 5         | 53      | 12     |
| Annual Transactions ($ Millions)        | 15400       | 94        | 12      | 12000  |
| Power Consumption (MW hr)               | 264         | 489       | 599     | 1968   |
| Consumption per Transaction (W hr / Tx) | 0.02        | 4.76      | 51.59   | 0.17   |

Table: Comparison between 2020 Paypal statistics<sup>1,2</sup> and the 2021
statistics of 3 Proof of Stake networks<sup>3</sup>.

## Storage

In general, the storage space required by a an individual Node within a cryptocurrencies
network is comparable with traditional databases used in centralized services.

The amount of storage space required depends on the design of the network's Blockchain
and additional databases.

For example, networks like Ethereum keep separate copies of the information stored in the Blockchain to
improve search performance. Such a design substantially increases overall storage requirements,
but is still comparable with traditional databases.

However, cryptocurrency networks consist of thousands of Nodes, each with a
separate copy of the networks database. As a result, the storage space consumed
by the network can be thousands of times larger than a traditional centralized
service.

## Speed

The time it takes to search through an individual Blockchain for a particular transaction,
contract or account balance depends on how the Blockchain is designed.

In general, the speed of performing transactions on an individual Blockchain is
comparable with traditional databases.

In the context of cryptocurrencies, Blockchain's are decentralized.
This requires an identical copy of a Blockchain is stored and maintained across a
large network of independent computers. When a new transaction is added, or a
contract called, it must be processed separately by every computer on the network.

In contrast, a centralized service like Paypal only needs to process a transaction once.

References:
-   <sup>1</sup>[BusnessofApps - Paypal Statistics](https://www.businessofapps.com/data/paypal-statistics/)
-   <sup>2</sup>[Paypal - CDP](https://s26.q4cdn.com/519805829/files/doc_downloads/2022/04/CDP_Climate_Change_PayPal.pdf)
-   <sup>3</sup>[Carbon Ratings - Proof of Stake](https://carbon-ratings.com/pos-report-2022)
-   [AWS - Decentralization in Blockchain](https://aws.amazon.com/blockchain/decentralization-in-blockchain/)
-   [Etherscan - Chain data size](https://etherscan.io/chartsync/chainarchive)
-   [Blockchair - Cumulative Ethereum Transactions](https://blockchair.com/ethereum/charts/total-transaction-count)
-   [YCharts - Bitcoin Blockchain Size](https://ycharts.com/indicators/bitcoin_blockchain_size)
-   [Nasdaq - Cumulative Bitcoin Transactions](https://data.nasdaq.com/data/BCHAIN/NTRAT-bitcoin-total-number-of-transactions)
