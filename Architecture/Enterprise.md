![Banner](https://github.com/JupiterChain/data-considerations/blob/master/images/Github%20Header.jpg)
https://jupiterchain.tech :rocket: 

# Jupiter Enterprise Architecture

The enterprise architecture for Jupiter Chain use cases are described in the diagram below:

![Enterprise Architecture Diagram](https://github.com/JupiterChain/data-considerations/blob/master/images/Enterprise.png)

JupiterChain will support 5 primary user roles: data subject, data analyst, data provider, data admin and data consumer. These roles have a distinct way of interacting with JupiterChain according to their specific needs. Contributing to the JupiterChain’s data ecosystem, they will be interacting via different applications and management systems. 

Below is a description of their responsibilities:

|User Role	|Description	|System|
| ------------- |-------------| --------:|
|Data Subject	|Individiuals or entities that own data and uses their data to subscribe for services offered by data consumers.	|Consumer Apps|
|Data Analyst	|Entities that perform studies and analysis of data. Consent from data subjects is required before data access. Data consumers use the analysis results to offer services to data subjects.|Jupyter Notebook or any analytics platform|
|Data Provider	|Entities that store data of data subjects on JupiterChain.	|Various Management Systems|
|Data Admin	|Entities that manage and maintain the data layer of JupiterChain. They also manage and maintain the entire JupiterChain blockchain.	|JupiterChain Management Systems and Tools|
|Data Consumer	|Entities that process data of data subjects in order to offer services. Consent from data subjects is required before they can access their data. |App connected to their own business smart contracts|

User roles are non-exclusive, For example, a data analyst can also be a data consumer.
Using the enterprise architecture as a guide, we formulate a [data architecture.](../Architecture/DataModel.md)

[Back to main page](../README.md)
