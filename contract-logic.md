# Content

*   [Contracts](#Contractlogic-Contracts)
    *   [Vote](#Contractlogic-Vote)
    *   [Donate](#Contractlogic-Donate)
    *   [AddProject](#Contractlogic-AddProject)
*   [Methods used from the web3.js library for Ethereum](#Contractlogic-Methodsusedfromtheweb3.jslibraryforEthereum)

* * *
Back to [README](./README.md)
* * *
## Contracts
* * *

All contracts are written in solidity (.sol).

#### Vote

With this contract, you can vote for the project you want to donate money for.

*   voting is only allowed when the current user has made a donation during the current donation period.
    

#### Donate

With this contract, you donate money to SeaLevelRaise.

*   transfers balance from donater (user) to the adress of this contract. Donations are mapped:
    

```
userHasDonated[msg.sender] = 1;
```

The miminum amount of the donation has to be 1 gwei.

At the end of an donation period the balance of the donate contract will be transferred to a project which is mapped to a project owner.

#### AddProject

With this contract, you can add new projects in small states to SeaLevelRaise or get all the projects already added.

The new project is mapped to the wallet of the person which added the project. The number of projects a person already added is also mapped, so that no one can add more than one project.

## Methods used from the web3.js library for Ethereum
* * *

connectWallet - this uses a “call” method, which does not wirte to the blockchian. No gas is required.

[https://web3js.readthedocs.io/en/v1.2.9/web3-eth-contract.html#methods-mymethod-call](https://web3js.readthedocs.io/en/v1.2.9/web3-eth-contract.html#methods-mymethod-call)

AddnewProject - this uses the “send” method, which “writes” something onto the blockchain. Therefore gas is required in Ethereum

[https://web3js.readthedocs.io/en/v1.2.9/web3-eth-contract.html#methods-mymethod-send](https://web3js.readthedocs.io/en/v1.2.9/web3-eth-contract.html#methods-mymethod-send)