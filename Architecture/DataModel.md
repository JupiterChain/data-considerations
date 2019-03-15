![Banner](https://github.com/JupiterChain/data-considerations/blob/master/images/Github%20Header.jpg)
https://jupiterchain.tech :rocket: 

# Jupiter Data Model Architecture

The architecture will consist of data layers and managed by smart contracts. Data layers manage data that are stored on individual user addresses. We borrow the tried and true principles of relational databases for robust data management.

  # Layers
We propose 3 layers for the Jupiter Data Model Architecture.
1. Registry Layer – root layer for the data model to communicate to data set smart contracts and business smart contracts. This will also facilitate data permissions
2. Data Set Layer –smart contracts for storing and retrieving data that are grouped together
3. Data Wrapper Layer – user addresses that contains all data managed by the data model

  # Currently Supported Data Types
Supported data types are:
1. Data Attributes – metadata which describes raw data
2. Raw Data – Encrypted JSON Data on an offchain storage that can be oraclized

The data model consists of 3 layers each with distinct set of responsibilities. All business smart contracts will need to interact with the data layer contracts to store and retrieve information. The flow is shown in the following diagrams:

![Data Model Architecture Diagram](https://github.com/JupiterChain/data-considerations/blob/master/images/DataModel.png)


[![Data Layer Contracts Diagram](https://github.com/JupiterChain/data-considerations/blob/master/images/DataLayer.png)](#DataLayer)
