```
forge create --rpc-url <rpc-url> --private-key <your-private-key> src/Contract.sol:UniswapV2Router02 --verify --verifier blockscout --verifier-url <explorer-url>/api --chain-id <chain-id> --constructor-args <factory> <weth>
```
