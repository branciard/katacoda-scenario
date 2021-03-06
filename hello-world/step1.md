



Pre-requisite: You need to have [node.js](https://nodejs.org/en/) installed on your machine.

`npm -g install iexec`{{execute}}

Check iexec help:

`iexec --help`{{execute}}

Check iexec version:

`iexec --version`{{execute}}



# Install and run your first application with iexec


 For this tutorial, we'll work with the factorial function.
 Factorial is compute-intensive and thus  better executed off-chain.
 The following command initializes a basic iexec Dapp template for you.

`iexec init factorial`{{execute}}


Your iexec Dapp is composed at the minimum of two parts:

* an offchain app, which can be any kind of legacy application. The offchain app will be executed by the iexec decentralized cloud.
* a smart contract that interfaces your iExec Dapp from Ethereum to the offchain app.


You will deploy those 2 parts in this tutorial, the Factorial off-chain app in the iExec network and the dapp smart contract in ethereum testnet.


Go into the created directory:

`cd iexec-factorial`{{execute}}
