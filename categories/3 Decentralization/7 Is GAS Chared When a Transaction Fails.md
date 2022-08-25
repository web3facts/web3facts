Transactions can fail for a variety of reasons, some of which charge GAS.

The most common reason for a transaction to fail and charge a user GAS is
when the transaction requires more GAS than the user was willing to pay. This is
referred to as an "Out of Gas" failure.

Another common cause of transaction failures is when a Smart Contract is faulty.
In this case a user interacting with a faulty Smart Contract will be charged GAS,
despite the failure.

References:
-   [Etherscan - Reasons for Transaction Failure](https://info.etherscan.com/reason-for-failed-transaction/)
