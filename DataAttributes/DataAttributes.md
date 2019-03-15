# Data Attributes
The Jupiter data architecture is intended to encompass general uses cases. We recommend the following base attributes for the Asset Metadata:


Attribute| Type| Required
 -------|-----|-----
Name|	String|	Yes
dateCreated|	String|	Yes
createdBy|	String|	Yes
dateModified|	String|	No
modifiedBy|	String|	No
contentType|	String|	Yes
File|	String|	No
Type|	String|	No
Description|	String|	No
Encoding|	String|	No
Value|	String|	No

Below is an example of an Asset Metadata object following the above-described schema:

```
{
    "base": {
        "name": "UK Weather information 2011",
        "type": "dataset",
        "description": "Weather information of UK including temperature and humidity",
        "dateCreated": "2012-02-01T10:55:11+00:00",
        "createdBy": "[ownerid/owneraddress]",
        "encoding": "UTF-8",
        "contentType": "text/csv",
        "file":
            {
                "url": "234ab87234acbd09543085340abffh21983ddhiiee982143827423421"
            }, 
    }, 
}
```
