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
## Result
Deploying contracts with the account: 0xeaeFFE33Abb09e4fc65F927625957b5F2d0e7332
Account balance: 1.19987100499922603
Token address: 0x59a48107889E8F49a86e318dCe1f29Ef7E538Ad7

Check at [polygon scan here](https://mumbai.polygonscan.com/address/0x59a48107889E8F49a86e318dCe1f29Ef7E538Ad7)