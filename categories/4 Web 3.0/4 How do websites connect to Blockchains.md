There are several ways that a website can connect to a [Blockchain](#WhatIsABlockchain):
-   Using a [centralized](#WhatDoesCentralizedMean) service such as [Infura](https://infura.io/)
-   Directly to a [Node](#WhatIsANode) via HTTP, HTTPS or Websocket
    -   The [Node](#WhatIsANode) must have JSON-RPC enabled
    -   The [Node](#WhatIsANode) must be hosted or trusted by the developer
-   Through an application which communicates with a [Blockchain](#WhatIsABlockchain) directly via [IPC](https://geth.ethereum.org/docs/getting-started)

[Centralized](#WhatDoesCentralizedMean) services such as [Infura](https://infura.io/) are currently the most common option used by Web 3.0 websites use to communicate with a [Blockchain](#WhatIsABlockchain).
This approach is appealing to developers as they do not need host their own [Node](#WhatIsANode)s.
The drawback to this approach is that their website / application will not communicate with a [Blockchain](#WhatIsABlockchain) directly so
they must trust the [centralized](#WhatDoesCentralizedMean) service.

**References**
-   [Go Ethereum - Getting Started](https://geth.ethereum.org/docs/getting-started)
-   [Go Ethereum JSON-RPC](https://geth.ethereum.org/docs/rpc/server)
-   [web3.js](https://web3js.readthedocs.io/en/v1.2.11/web3.html)
-   [Dapp University](https://www.dappuniversity.com/articles/web3-js-intro)
