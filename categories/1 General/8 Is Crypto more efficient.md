There is no simple answer to this question. There are many ways to measure efficiency,
and each cryptocurrency network works differently. The below answers focus on Energy
Consumption, Storage and Speed.

## Energy

Networks which utilize [Proof of Work](#WhatIsProofOfWork) are significantly less energy efficient when
compared to traditional [centralized](#WhatDoesCentralizedMean) financial services.

This is due to the large amounts of power consumed by the [miners](#WhatIsMining). The energy consumed in this case has been
compared to the energy consumption of an [entire country](https://www.bbc.com/news/technology-56012952).

Networks which utilize Proof of Stake are more comparable with traditional [centralized](#WhatDoesCentralizedMean) services.
The bulk of the energy consumed by Proof of Stake network is consumed by the [Node](#WhatIsANode)s within network.
The energy consumption is high as all [Node](#WhatIsANode)s within the network must perform the same transactions
to assure the [Blockchain](#WhatIsABlockchain) is consistent.

Below is a rough comparison between Paypal and three popular Proof of Stake networks.
The per transaction energy consumption of the selected networks ranges from roughly
20 to 2500 times Paypal's 2020 energy consumption.

| Metric                                  | Paypal      | Avalanche | Cardano | Solana |
| --------------------------------------- | ----------- | --------- | ------- | ------ |
| [Node](#WhatIsANode)s                   | -           | 1084      |  3002   | 1015   |
| Market Cap (Billions)                   | $220        | $5        | $53     | $12    |
| Annual Transactions (Millions)          | $15400      | $94       | $12     | $12000 |
| Power Consumption (MW hr)               | 264         | 489       | 599     | 1968   |
| Consumption per Transaction (W hr / Tx) | 0.02        | 4.76      | 51.59   | 0.17   |

Table: Comparison between 2020 Paypal statistics<sup>1,2</sup> and the 2021
statistics of 3 Proof of Stake networks<sup>3</sup> (USD).

## Storage

In general, the storage space required by a an individual [Node](#WhatIsANode) within a cryptocurrencies
network is comparable with traditional databases used in [centralized](#WhatDoesCentralizedMean) services.

The amount of storage space required depends on the design of the network's [Blockchain](#WhatIsABlockchain)
and additional databases.

For example, networks like Ethereum keep separate copies of the information stored in the [Blockchain](#WhatIsABlockchain) to
improve search performance. Such a design substantially increases overall storage requirements,
but is still comparable with traditional databases.

However, cryptocurrency networks consist of thousands of [Node](#WhatIsANode)s, each with a
separate copy of the networks database. As a result, the storage space consumed
by the network can be thousands of times larger than a traditional [centralized](#WhatDoesCentralizedMean)
service.

## Speed

The time it takes to search through an individual [Blockchain](#WhatIsABlockchain) for a particular transaction,
contract or account balance depends on how the [Blockchain](#WhatIsABlockchain) is designed.

In general, the speed of performing transactions on an individual [Blockchain](#WhatIsABlockchain) is
comparable with traditional databases.

In the context of cryptocurrencies, [Blockchain](#WhatIsABlockchain)'s are [decentralized](#WhatDoesDecentralizedMean).
This requires an identical copy of a [Blockchain](#WhatIsABlockchain) is stored and maintained across a
large network of independent computers. When a new transaction is added, or a
contract called, it must be processed separately by every computer on the network.

In contrast, a [centralized](#WhatDoesCentralizedMean) service like Paypal only needs to process a transaction once.

**References**
1.   [BusnessofApps - Paypal Statistics](https://www.businessofapps.com/data/paypal-statistics/)
2.   [Paypal - CDP](https://s26.q4cdn.com/519805829/files/doc_downloads/2022/04/CDP_Climate_Change_PayPal.pdf)
3.   [Carbon Ratings - Proof of Stake](https://carbon-ratings.com/pos-report-2022)
4.   [AWS - Decentralization in Blockchain](https://aws.amazon.com/blockchain/decentralization-in-blockchain/)
5.   [Etherscan - Chain data size](https://etherscan.io/chartsync/chainarchive)
6.   [Blockchair - Cumulative Ethereum Transactions](https://blockchair.com/ethereum/charts/total-transaction-count)
7.   [YCharts - Bitcoin Blockchain Size](https://ycharts.com/indicators/bitcoin_blockchain_size)
8.   [Nasdaq - Cumulative Bitcoin Transactions](https://data.nasdaq.com/data/BCHAIN/NTRAT-bitcoin-total-number-of-transactions)
