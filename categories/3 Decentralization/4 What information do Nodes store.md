The information stored within the Nodes of a cryptocurrencies network depends
on how the network is designed.

All cryptocurrencies require that the Nodes within its network store a Blockchain.
The Blockchain is what is responsible for storing the transactions which are processed
on the network.

Networks similar to Ethereum are designed such that the Nodes store additional information,
separate from the Blockchain to help improve performance.
The Nodes within the Ethereum network store what is referred to as the [world state](https://docs.polygon.technology/docs/edge/concepts/ethereum-state/)
or [global state](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/#state-trie).

## Global State {#globalstate}
The global state contains information about all wallets and contracts (referred to as Accounts) which exist on the network
at a given time. It is constantly updated in accordance with the transactions
processed by the network.

Each Account stored within the global state contains:
-   nonce - the number of transactions sent by the account
-   balance - the amount of Ether owned by the account
-   storageRoot - a reference to the location where additional information is stored for the account, such as contract data
-   codeHash - the hash of a Smart Contract's code (empty for wallets)

References:
-   [Ethereum - State Trie](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/#state-trie)
-   [Polygon - Ethereum State](https://docs.polygon.technology/docs/edge/concepts/ethereum-state/)
-   [Github - go-ethereum/core/blockchain.go](https://github.com/ethereum/go-ethereum/blob/594e32166269eed4f5cb8270bba99fa234a41606/core/blockchain.go)
-   [Github - go-ethereum/core/statedb.go](https://github.com/ethereum/go-ethereum/blob/594e32166269eed4f5cb8270bba99fa234a41606/core/state/statedb.go)
