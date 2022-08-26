An NFT is stored within the memory allocated to a Smart Contract. This
typically includes the token id, owners wallet address and website link to the metadata.

NFTs are not stored within the Blockchain, but within the [global state](#globalstate)
of the each Node in the network.

Transactions involving NFTs are stored within the Blockchain.

The metadata associated to the website link (URI) is commonly stored using centralized
services or IPFS.

References:
-   [Ethereum - State Trie](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/#state-trie)
-   [OpenZeppelin - ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L19)
