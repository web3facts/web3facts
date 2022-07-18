There are several ways that a website can connect to a Blockchain:
- Using a centralized service such as [Infura](https://infura.io/)
- Directly to a Node via HTTP, HTTPS or Websocket 
  - The Node must have JSON-RPC enabled
  - The Node must be hosted or trusted by the developer
- Through an application which communicates with a Blockchain directly via [IPC](https://geth.ethereum.org/docs/getting-started)

Centralized services such as [Infura](https://infura.io/) are currently the most common approach Web 3.0 websites use to communicate with a Blockchain.
This approach is appealing to developers as they do not need host their own Nodes. 
The drawback to this approach is that their website / application will not communicate with a Blockchain directly.

References:
[Go Ethereum - Getting Started](https://geth.ethereum.org/docs/getting-started)
[Go Ethereum JSON-RPC](https://geth.ethereum.org/docs/rpc/server)
[web3.js](https://web3js.readthedocs.io/en/v1.2.11/web3.html)
[Dapp University](https://www.dappuniversity.com/articles/web3-js-intro)