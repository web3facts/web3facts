Transactions represent requests which are made by the users of a cryptocurrency
and are actioned by the [Node](#WhatIsANode)s within the network. When actioned they cause the
[Blockchain](#WhatIsABlockchain) to grow and the global state to be updated.

Transactions can be used to:
-   Transfer cryptocurrency between wallets
-   Create [Smart Contracts](#WhatIsASmartContract)
-   Execute [Smart Contracts](#WhatIsASmartContract)

On the Ethereum network, a transaction will include:
-   "to" :
    -   a wallet address when transferring cryptocurrency
    -   Empty when creating a [Smart Contract](#WhatIsASmartContract)
    -   a [Smart Contract](#WhatIsASmartContract) address when executing a [Smart Contract](#WhatIsASmartContract)
-   "value" - the amount of Ether to send to the recipient
-   "gasLimit" - the maximum amount of [GAS](#WhatIsGAS) set by the sender
-   "maxPriorityFeePerGas" - the maximum tip amount to the [miner](#WhatIsMining) set by the sender
-   "maxFeePerGas" - the sum of a base fee (set by the network) and the maxPriorityFeePerGas
-   "data" :
    -   Optional when transferring cryptocurrency
    -   Contains code to initialize the [Smart Contract](#WhatIsASmartContract) when creating a [Smart Contract](#WhatIsASmartContract)
    -   Contains the requested method to execute when executing a [Smart Contract](#WhatIsASmartContract)

**References**
-   [Ethereum - Transactions](https://ethereum.org/en/developers/docs/transactions/)
