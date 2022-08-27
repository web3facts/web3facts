An [NFT](#WhatIsAnNFT) is stored within the memory allocated to a [Smart Contract](#WhatIsASmartContract). This
typically includes the token id, owners wallet address and website link to the metadata.

[NFT](#WhatIsAnNFT)s are not stored within the [Blockchain](#WhatIsABlockchain), but within the [global state](#globalstate)
of the each [Node](#WhatIsANode) in the network.

Transactions involving [NFT](#WhatIsAnNFT)s are stored within the [Blockchain](#WhatIsABlockchain).

The metadata associated to the website link (URI) is commonly stored using [centralized](#WhatDoesCentralizedMean)
services or [IPFS](#WhatIsIPFS).

**References**
-   [Ethereum - State Trie](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/#state-trie)
-   [OpenZeppelin - ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L19)
