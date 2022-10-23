PROJECT DETAILS-
We have build a system that helps the user to buy and sell property.The system has the following features-

 -It allows the user to register in the system with previously owned property.

 -User can buy and sell any property in the system.

 -User can see the transaction history of any property.

 -We incorporated the Proof of Work(PoW) algorithm to improve the security of the blockchain.

 -For calculating the hash of all transactions in a block we implemented the Merkle Tree.
 
 Function Details-
 -User Registration:It creates a list containing the information(Owner Name,Property Owned by him or not,Property Name) of the user. Without registration, one cannot buy or sell property.

 -Add Transaction:This function takes transaction details(transaction id,Amount,Buyer Name,Property Name) from the user and check whether the details are valid or not.After the verification it adds the transaction to the block.3 transactions make up a block.

 -View Blockchain:It prints the entire blockchain.

 -View Verified Transactions:It shows the user all the verified transactions containing information(Transaction ID,Buyer Name,Seller Name,Amount,Property Name,Timestamp).

 -View Unverified Transactions:It shows the user all the unverified transactions containing information(Transaction ID,Buyer Name,Seller Name,Amount,Property Name,Timestamp).

 -Print Property Transaction History:It shows all the transactions information(buyer's name,seller's name) related to the property entered by the user. 

 -Print Users:It prints all the users information registered in the system.

 -View Transaction:It allows the user to view a specific transaction done.

 -View Block:It allows the user to see any block contained in the blockchain.

 -View Timestamp:It shows the time when the transaction happened in the system.

 -Exit Program:It helps the user to exit the system.
