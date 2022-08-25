Smart Contracts can be called by generating a transaction where the "to" address
is the address of a Smart Contract, rather than a wallet.

When transacting with a Smart Contract additional information must be provide to
specify which method is to be executed and any associated parameter data.
The additional information is typically encoded in accordance with the Smart Contract's
[Application Binary Interface](https://docs.soliditylang.org/en/v0.8.15/abi-spec.html)
(ABI). In short, the ABI specifies the structure of all methods that can be executed within the
Smart Contract.

For example an NFT owner can transfer their ownership to another individual by
calling the [transfer](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L331) method from the corresponding NFT Smart Contract. To do this, the
NFT owner will need to generate a transaction with:
-   the "to" address set to address of the NFT Smart Contract
-   the "data" field set to ABI encoded information which includes:
    -   a call to the `transfer` method
    -   the three parameters required by the `transfer` method
        -   the "from" address (the current owner of the NFT)
        -   the "to" address (the recipient of the NFT)
        -   the token ID

Transactions involving Smart Contracts are processed in the same way as
transactions between wallets but additionally require all Nodes within the network to
independently execute the requested method.

References:
-   [Bitcoin - How Transactions Work](https://www.bitcoin.com/get-started/how-bitcoin-transactions-work/)
-   [Ethereum - Transactions](https://ethereum.org/en/developers/docs/transactions/)
-   [Solidity - ABI](https://docs.soliditylang.org/en/v0.8.15/abi-spec.html)
-   [Github - OpenZeppelin ERC-721](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC721/ERC721.sol#L331)
