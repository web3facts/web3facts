In general minting refers to making the first purchase of a token which is managed
by an [NFT](#WhatIsAnNFT) Smart contract.

When an [NFT](#WhatIsAnNFT) is minted the [Smart Contract](#WhatIsASmartContract) will typically:
-   Create a transaction on the [Blockchain](#WhatIsABlockchain)
-   Add a reference between the owner and the token id within the [Smart Contract](#WhatIsASmartContract)'s storage

Depending on how the [Smart Contract](#WhatIsASmartContract) is designed minting may also involve storing
a website link to metadata within the [Smart Contract](#WhatIsASmartContract). This is referred to as Lazy Minting
and will require more [GAS](#WhatIsGAS).

-   [Open Zeppelin - ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L279)
-   [Ethereum EIP - EIP-721](https://eips.ethereum.org/EIPS/eip-721)
-   [Opensea - Collection Manager](https://opensea.io/blog/announcements/introducing-the-collection-manager/)
