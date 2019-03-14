# Jupiter Enterprise Architecture

The enterprise architecture for Jupiter Chain use cases are described in the diagram below:

![Enterprise Architecture Diagram](https://github.com/JupiterChain/data-considerations/blob/master/images/Enterprise.png)

JupiterChain will support 5 primary user roles: data subject, data analyst, data provider, data admin and data consumer. These roles have a distinct way of interacting with JupiterChain according to their specific needs. Contributing to the JupiterChain’s data ecosystem, they will be interacting via different applications and management systems. 

Below is a description of their responsibilities:

|User Role	|Description	|System|
| ------------- |-------------| --------:|
|Data Subject	|The people that own data and uses their data to subscribe for services offered by data consumers.	|Consumer Apps|
|Data Analyst	|The people that perform studies and analysis of data that are used by data consumers for their services which are being sold to data subjects. They need consent from data subjects before they can access data.	|Jupyter Notebook or any analytics platform|
|Data Provider	|The people that store data of data subjects to JupiterChain.	|Various Management Systems|
|Data Admin	|The people that manage and maintain the data layer of JupiterChain. They also manage and maintain the entire JupiterChain blockchain.	|JupiterChain Management Systems and Tools|
|Data Consumer	|The people that process data of data subjects as services. They need consent from data subjects before they can access their data. |App connected to their own business smart contracts|

[Back to main page](../master/Readme.md)
