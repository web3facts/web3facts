Transactions can fail for a variety of reasons, some of which charge [GAS](#WhatIsGAS).

The most common reason for a transaction to fail and charge a user [GAS](#WhatIsGAS) is
when the transaction requires more [GAS](#WhatIsGAS) than the user was willing to pay. This is
referred to as an "Out of Gas" failure.

Another common cause of transaction failures is when a [Smart Contract](#WhatIsASmartContract) is faulty.
In this case a user interacting with a faulty [Smart Contract](#WhatIsASmartContract) will be charged [GAS](#WhatIsGAS),
despite the failure.

**References**
-   [Etherscan - Reasons for Transaction Failure](https://info.etherscan.com/reason-for-failed-transaction/)
