## Boilderplate template
- Here is the link: https://trufflesuite.com/docs/truffle/quickstart/
```
truffle unbox metacoin
```
- Change the version to `pragma solidity ^0.8.0;`
- Remove contructor public
- All the contracts need to specify the license


## Test
```
truffle test
truffle test ./test/TestMetaCoin.sol
truffle test ./test/metacoin.js
```

## Compile
```
truffle compile
```

## Deploy to ropsten 
- Here is the link: https://medium.com/coinmonks/5-minute-guide-to-deploying-smart-contracts-with-truffle-and-ropsten-b3e30d5ee1e
- `npm install --save truffle-hdwallet-provider`
- `truffle-config.js` https://gist.githubusercontent.com/nczhu/1cdbfc73cb6a61ed2a74ea1fdae1b05a/raw/6920eb0f88ec746c16566281b8a141468c436b8c/truffle.js
- Need to create new project on infura to get key, and get private key from metamask wallet.
- `truffle deploy --network ropsten`