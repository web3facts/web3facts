An NFT is a piece of information which is stored and managed by a [Smart Contract](#WhatIsASmartContract).

Each NFT refers to a different Token ID that is used to link the NFT to additional
information within the [Smart Contract](#WhatIsASmartContract).

NFT [Smart Contracts](#WhatIsASmartContract) typically link a Token ID to:
-   A website link (URI) to metadata
-   The Wallet Address of the owner
-   The Address of a contract which is granted permission to control the NFT

The website link (URI) is how an NFT is associated to an image. When the website
is visited further information is provided in JSON format. This information is
called the NFT's metadata and is commonly stored using [centralized](#WhatDoesCentralizedMean) services or
[IPFS](#WhatIsIPFS).

Below is a simple example of NFT metadata.
```
{
  "image":"example.com/image.jpg",
  "name":"Example"
}
```

In summary, an NFT is a token stored in a [Smart Contract](#WhatIsASmartContract) which refers to a website link
(URI) which refers to an image link.

**References**
-   [OpenZeppelin - ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L19)
