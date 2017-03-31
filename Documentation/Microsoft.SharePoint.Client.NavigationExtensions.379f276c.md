# NavigationExtensions.AddNavigationNode Method  
Add a node to quick launch, top navigation bar or search navigation. The node will be added as the last node in the
            collection.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddNavigationNode(Web web,String nodeTitle,Uri nodeUri,String parentNodeTitle,NavigationType navigationType,Boolean isExternal,Boolean asLastNode)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*nodeTitle*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*nodeUri*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
*parentNodeTitle*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*navigationType*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Enums.NavigationType](OfficeDevPnP.Core.Enums.NavigationType.md) 
&emsp;&emsp;  
  
*(optional) isExternal*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) asLastNode*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.NavigationNode](Microsoft.SharePoint.Client.NavigationNode.md)  
Newly added NavigationNode

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
