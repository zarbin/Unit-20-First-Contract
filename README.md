# Unit-20-First-Contract
Unit 20 Homework


### Use and Purpose of Contracts

##### The AssociateProfitSplitter Contract
    This contract will accept Ether into the contract and divide it evenly among the associate 
    level employees.  This allows the Human Resources department to pay employees quickly and efficiently.

##### The TieredProfitSplitter Contract
    This contract will distribute different percentages of incoming Ether to employees 
    at different tiers or levels.

##### The DeferredEquityPlan Contract
    This contract models traditional company stock plans. This contract will automatically manage 1000 shares 
    with an annual distribution of 250 over 4 years for a single employee.
    

### Screenshots to illustrate the functionality
Splitting transactions locally

![Screenshot](/images/AssociateSplitter.gif)

##### How you send transactions
1) Open MetaMask
2) Send a transaction to the contract at address: 0xf620f82d284698c8d04d20572db4720c440f2a82
3) Confirm the transaction in MetaMask
4) Verify the transaction on Etherscan: https://ropsten.etherscan.io/tx/0x9f8a45173e7db153342077681dc097d71b9a11f6eb5770128f3efdd9c8997948
 
![Screenshot](/images/mm1.jpg)

![Screenshot](/images/mm2.jpg)

##### How the transferred amount is then distributed by each of the contracts
AssociateProfitSplitter
![Screenshot](/images/etherscan.jpg)

TieredProfitSplitter
![Screenshot](/images/etherscan2.jpg)

### Testnet address for others to interact with the contract
    AssociateProfitSplitter Testnet contract address:  0xf620f82d284698c8d04d20572db4720c440f2a82
    TieredProfitSplitter Testnet contract address:  0xf9d113fdd362500b0af1820055ac71e0b3b3264f
    DeferredEquityPlan Testnet contract address:  0xa24fadba077d349a41efcd231e54b63cc8fa1a99