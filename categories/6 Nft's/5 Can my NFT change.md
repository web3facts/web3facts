There are two ways that the image associated to an [NFT](#WhatIsAnNFT) can change:
-   When the [Smart Contract](#WhatIsASmartContract) which manages the [NFT](#WhatIsAnNFT) allows for URI changes
-   When the metadata associated with the URI changes

## URI Changes
The information related to an [NFT](#WhatIsAnNFT), such as the token id and a metadata URI,
is stored within the memory allocated to an [NFT](#WhatIsAnNFT) [Smart Contract](#WhatIsASmartContract).

Typically, [Smart Contracts](#WhatIsASmartContract) which manage [NFT](#WhatIsAnNFT)s do not allow [NFT](#WhatIsAnNFT) owners to change
the metadata URI stored within the contract.
Though, it is possible to design [Smart Contracts](#WhatIsASmartContract) which allow for the metadata URI to be changed.

## Metadata Changes
The metadata URI is typically a website link which when visited displays information
such as the [NFT](#WhatIsAnNFT)'s name and associated image.

It is possible to alter this metadata so that the image associated with an [NFT](#WhatIsAnNFT) changes.

It is also possible that the website which stores the metadata is taken offline,
which would mean the [NFT](#WhatIsAnNFT) is no longer associated to an image.

Metadata can be store more permanently using a distributed file storage system
such as [IPFS](#WhatIsIPFS).

**References**
-   [Open Zeppelin - ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L93)
-   [Opensea - Metadata standards](https://docs.opensea.io/docs/metadata-standards)
