![Banner](https://github.com/JupiterChain/data-considerations/blob/master/images/Github%20Header.jpg)
https://jupiterchain.tech :rocket: 

# Operational Requirements for Jupiter Chain's data model

## Deployment
Deployment of Data Set Smart Contracts and Registry Smart Contract can be done by either using truffle or Nethereum (with front-end UI). On code level, deployment will be done by remapping of the new Smart Contract Address and ABI in the Registry Contract for Data Set Smart Contracts. For deployment of new Registry Contract, deployment will be done by remapping the Registry Smart Contract new address and ABI to each registered Data Set Smart Contracts.

## Rollout Plan
Because this is a new Data Model for Ethereum Based Contracts, The development and deployment will be done first on the Data Set Layer and will observed proper OOP principles to inherit common standard functions for the Data Set layer. After the base Data Set Smart Contracts have been developed and deployed, we can proceed with the development and deployment of the Registry Contract. Testing will be done throughout the development cycle of the 2 Data Model layers.

## Rollback
Rollback of either Registry Contract or Data Set Smart Contracts is done by simply calling a function on current Registry Contract that will remap the inputted previous Smart Contract Address and its ABI.

## Data Swap between Addresses
Data Swap between addresses is handled either in the Data Set Contract level or Registry Level.

## Data Management
Data Management is done through Data Management Systems that connects to the Data layer of JupiterChain – separate development.  

## Auditing and Logging
Auditing is done through query of transactions on the blockchain level. We shall discuss further the tags and classifications of each transaction for auditing and logging. (ELK)
https://medium.com/validitylabs/how-to-interact-with-the-ethereum-blockchain-and-create-a-database-with-python-and-sql-3dcbd579b3c0
To be further researched and discussed – separate development

## Data Analytics
Data analytics is done through web3 library that connects to a Registry contract to retrieve actual user data with consent. (Jupyter Notebook). To be further researched and discussed – separate development.
