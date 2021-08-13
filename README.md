# Assignment_20_SmartContracts

## Overview

A potential new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

The objective of this assignment was to create three different smart contracts representing various ways to distribute profit amongst the startup's employees. These contracts will:

* Level 1: Pay the Associate-level employees equally by dividing the profits into three.

* Level 2: Distribute profits to different tiers of employees (CEO, CTO & CFO).

* Level 3: Distribute company shares for employees in a "deferred equity incentive plan" automatically.


### Files and Getting Started

Navigate to the [Remix IDE](https://remix.ethereum.org) and create new solidity files for each contract.

Attached are links to the code for each smart contract.  

* [`AssociateProfitSplitter.sol`](Starter-Code/AssociateProfitSplitter.sol) -- Level 1 Code.

* [`TieredProfitSplitter.sol`](Starter-Code/TieredProfitSplitter.sol) -- Level 2 Code.

* [`DeferredEquityPlan.sol`](Starter-Code/DeferredEquityPlan.sol) -- Level 3 Code.

While developing and testing the contract, use the [Ganache](https://www.trufflesuite.com/ganache) development chain and point MetaMask to `localhost:8545`, or replace the port with what you have set in your workspace.

Additional README files have been included in the REPO that outline how to deploy and execute each contract. Various screenshots of successful transactions have also been included in these README files. 

* [Associate Profit Splitter](Level1_AssociateContract.md)

* [Tiered Profit Splitter](Level2_TieredContract.md)

* [Deferred Equity Plan](Level3_DeferredEquityContract.md)
