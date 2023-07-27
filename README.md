# PyChain Ledger

## **Overview of the Developed Ledger**
This blockchain-based ledger system has been developed to serve the purpose of a user-friendly web interface decentralized financial system enabling the five largest banks in the world to conduct financial transactions and to verify the integrity of the data in the ledger.
****

## **Web Interface Navigation**
The developed web interface tool allows the user to perform, review and validate transactions using the interactive buttons, inputs and sliders using *Streamline*. The following inputs are available to facilitate the financial operations:
* The `sender` input block is used to insert the sender's address.
* The `receiver` input block is used to insert the receiver's address.
* The  `amount` input block is used to insert the amount of the transaction.
* The `Block Difficulty` slider gives the user the option to select difficulty level [1-5] for the hashing process.
* The `Add Block` button will update the block chain with the last transaction performed.
* The `Block Inspecter` drop-down menu allows the user to view information of any transaction on the blockchain.

## **Application Outcome**
Here is an example of multiple transactions processed on the web interface, showing how the blockchain is updated with the relevant information from each transaction.


<center><img src="[Images/Pychain_Main.png](https://github.com/WasseemN/Homework_week_18/blob/main/Images/PyChain_BlockInspector.PNG)"/></center>

##### <center>Figure 1 - Snapshot of the ledger


The below snapshot shows the slider control for difficulty level controller and the `Block Inspector` which provides the user with detailed information of any transaction selected. As shown the previous hash, timestamp and nonce can be reviewd using this function.


<center><img src="Images/Pychain_BlockInspector.png"/></center>


##### <center>Figure 2 - Hashing Difficulty Level Controller

## **Testing the PyChain Ledger**

In order to validate the hashing process of the transactions, the `Validate Chain` button is provided to validate each transaction.


<center><img src="Images/Pychain_LedgerValidation.png"/></center>

##### <center>Figure 3 - Transaction Validation
