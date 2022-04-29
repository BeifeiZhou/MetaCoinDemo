## Boilder template
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