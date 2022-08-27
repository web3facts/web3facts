[Smart Contracts](#WhatIsASmartContract) can be created by any individual or entity by writing computer
code in accordance with the specification of a cryptocurrencies network. The specifics around
this process depends on the network, here the Ethereum network will be considered.

The Ethereum network allows contracts to be written in several languages, the
most common is called [Solidity](https://docs.soliditylang.org/en/v0.8.15/introduction-to-smart-contracts.html). Ethereum also provides [standards](https://eips.ethereum.org/erc)
for contracts depending on the intended use. For example [Smart Contracts](#WhatIsASmartContract) which
manage [NFT](#WhatIsAnNFT)s follow the [EIP-721](https://eips.ethereum.org/EIPS/eip-721) standard.

Once a [Smart Contract](#WhatIsASmartContract) is designed and underlying code written it then must be
stored within all the [Node](#WhatIsANode)s of the network. To do this a transaction must be
generated which includes instructions on how the [Smart Contract](#WhatIsASmartContract) should be initialized.

The initialization process allocates memory for the [Smart Contract](#WhatIsASmartContract) within the
[global state](#globalstate) of the Ethereum [Node](#WhatIsANode)s. This is the memory that is used
to store the compiled [Smart Contract](#WhatIsASmartContract) along with any information declared within the
[Smart Contract](#WhatIsASmartContract). This process requires more [GAS](#WhatIsGAS) than a standard transaction,
see [here](https://github.com/ethereum/go-ethereum/blob/594e32166269eed4f5cb8270bba99fa234a41606/core/state_transition.go#L121-L123).

The transaction generated to create the [Smart Contract](#WhatIsASmartContract) will exist indefinitely
within the [Blockchain](#WhatIsABlockchain), however, the [Smart Contract](#WhatIsASmartContract) itself exists within the [global state](#globalstate)
of the [Node](#WhatIsANode)s until the contract is destroyed.

**References**
-   [Solidity - Storage](https://docs.soliditylang.org/en/v0.8.15/internals/layout_in_storage.html)
-   [Ethereum - State Trie](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/#state-trie)
-   [Polygon - Ethereum State](https://docs.polygon.technology/docs/edge/concepts/ethereum-state/)
-   [Github - go-ethereum/core/state_transition/IntrinsicGas](https://github.com/ethereum/go-ethereum/blob/594e32166269eed4f5cb8270bba99fa234a41606/core/state_transition.go#L121-L123)
-   [Github - go-ethereum/core/state/state_object](https://github.com/ethereum/go-ethereum/blob/5fb463dddc928eec38de80f63ebdd9d7820d1a72/core/state/state_object.go#L66-L81)
-   [Github - go-ethereum/core/state/statedb](https://github.com/ethereum/go-ethereum/blob/5fb463dddc928eec38de80f63ebdd9d7820d1a72/core/state/statedb.go#L64)
