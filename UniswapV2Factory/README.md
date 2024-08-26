```
forge create --rpc-url <rpc-url> --private-key <your-private-key> src/Contract.sol:UniswapV2Factory --verify --verifier blockscout --verifier-url <explorer-url>/api --chain-id <chain-id> --constructor-args <owner>
```

***Additional***: After deployment You should call the `setFeeTo` function to the address where the fee will be received.*
