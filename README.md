# Timelock
Lock any ERC20 Tokens for free.

also works with tokens which have tokenomics such as fee on transfer

In order to lock tokens you need to allow the smart contract to use your tokens by approving first.

Unpreventable Vulnerability:
as we are checking if the block.timestamp is smaller than the actual time when someone tries to withdraw, the risk is on the block.timestamp as the timestamp can be manipulated by miners. This is unpreventable but not a drama at all so therefore it's a low vulnerability.
