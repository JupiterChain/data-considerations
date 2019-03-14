<h1> Data Considerations for Jupiter Chain </h1>

This repo outlines the Jupiter Chain proposal for the storage of data in account-based blockchains for the purpose of data and consent management. Jupiter Chain use cases have three main considerations (refer to the whitepaper on https://jupiterchain.tech for more information):
1. Identity and tracking of accounts
2. Consent and permissioning of access to data
3. Computation of data assessment algorithms

<h2>Goals</h2>
As such the proposed data model has the following goals:
1.	Registration of allowed owner addresses and data permissions
2.	Definition of data schema with functional relationships between data sets
3.	Storage and retrieval of data through standard data methods
4.	Optimal deployment, upgrade and removal of data set smart contracts and registry contracts without the risk of losing associated data
5.	Definition of data through a standard set of data attributes that describes the data

<h2>Requirements</h2>
The data model will have the following characteristics:
1.	Standard functions and signatures
2.	Data schema that describes the data set properties and their relationships
3.	Facilitation of data normalization and data joins
4.	A list that records owner addresses for data permission
5.	Loosely coupled data set smart contracts and registry contracts resembling a factory pattern
6.	Isolated data set smart contract and registry contract deployment

<h2>Assumptions</h2>
1.	Data Attributes and non-personal data in Ethereum based blockchains are stored onchain 
2.	Personal data are stored in secure offchain storage
3.	Onchain data are stored on user addresses
4.	Files are stored offchain

Based on the Jupiter Chain use case enterprise architecture we propose a data model for the Jupiter Chain and suggest an implementation using smart contracts. The repo is organised as follows:
* [Enterprise Architecture](../master/Architecture/Enterprise)
* [Data Model Architecture](../master/Architecture/DataModel)
** [Data Layer Contracts](../master/Architecture/DataContracts)
* [Data Attributes](../master/DataAttributes/DataAttributes)
* [Operations](../master/Operations/Operations)
