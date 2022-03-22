<h1 align="center">Smart Contract</h1> 

Smart contracts were built with the ease of transfering money between accounts using Ethereum-compatible blockchain. Smart contracts also help automate the transfering process for financial institutions. The advantages of using smart contracts are that the sender and receiver can track the mutual transactions, the audit trail is public and cannot be manipulated, and the ability to send transactions instantaneously without any delay.

This smart contract was build for two users to transact to a joint savings account. Both users can control the account by depositing and withdrawing from the account. 

## Usage

To use this smart contract, copy the code in the 'joint_savings.sol' file and paste the code in [Remix-Ethereum IDE](http://remix.ethereum.org). Compile the the file on the "Solidity Compiler" tab.

![image](https://user-images.githubusercontent.com/84649228/141707451-4e7b992a-d822-427b-869d-9a6a775dfbbd.png)

Next, you will deploy the contract on the "Deploy & Run Transactions" tab.

![image](https://user-images.githubusercontent.com/84649228/141707545-ea8e0bd5-ec82-4bd8-aba8-2c450e85272a.png)

Once the contract has been deployed, the contract can be funded. To fund the joint account, add an amount in the "Value" section and click on "deposit".

![image](https://user-images.githubusercontent.com/84649228/141707765-205a9da8-ff4f-4f7e-b2a2-f7e097ec48de.png)

To withdraw money from the joint savings account, we can list an account in the "withdraw" section and input an amount we want, then click "transact". This will conduct the transaction. You can verify that the transaction went through by clicking "lastToWithdraw" and "lastToWithdrawAmount" to see who withdrew and how much.

![AccountOne Transaction](https://user-images.githubusercontent.com/84649228/141708204-6cfead9b-632a-4283-b519-630f9151c9b0.PNG)


