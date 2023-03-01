# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

# Step to deply this contract
```shell
npx hardhat compile
npx hardhat run scripts/deploy.js --network mumbai
```

# Step to flatten this contract
```shell
npx hardhat flatten contracts/CryptoCatapult.sol >Flattened.sol
```
!Note: When flat the solidity file in mumbai poly scan might got many license error so leave only one license in the flattened file
## Result
Deploying contracts with the account: 0xeaeFFE33Abb09e4fc65F927625957b5F2d0e7332
Account balance: 1.198147782479696175
Token address: 0x76d7d4a62dE48579C103ff3a6dec0cb73a1C67Be

Check at [polygon scan here](https://mumbai.polygonscan.com/address/0x76d7d4a62dE48579C103ff3a6dec0cb73a1C67Be)