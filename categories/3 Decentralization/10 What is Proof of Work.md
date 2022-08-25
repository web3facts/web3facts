Proof of Work refers to the ability to prove that a particular computer has
performed a certain number of computations.

In the context of cryptocurrencies, it is used to determine whether a Block of
transactions should be added to the Blockchain.

Each Block contains a set of transactions along with a unique number, called a nonce.
For a Block to be added to the Blockchain, it's hash must have a particular property.

Every miners goal is to find a nonce that gives the Block's hash the desired property.

Miners do this by continually guessing numbers and re-hashing the Block. Each time
the nonce changes, the hash changes too.

When they find a valid number, the number itself is the Proof of Work.

The process is designed to required large number of guesses to reach a hash
with the desired property.

The miners on the **Bitcoin** network generate roughly **200 Trillion hashes per second**,
producing **1 new Block every 10 minutes**.

The miners on the **Ethereum** network generate roughly **900 Trillion hashes per second**,
producing **1 new Block every 13 seconds**.

The large energy costs are due to enormous number of hashes required.

References:
-   [Ethereum - Proof of work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/)
-   [Blockchain - Hash Rate](https://www.blockchain.com/charts/hash-rate)
-   [Etherscan - Hash Rate](https://etherscan.io/chart/hashrate)
-   [Etherscan - Block Time](https://etherscan.io/chart/blocktime)
-   [BitInfoCharts - Bitcoin Block Time](https://bitinfocharts.com/comparison/bitcoin-confirmationtime.html)
