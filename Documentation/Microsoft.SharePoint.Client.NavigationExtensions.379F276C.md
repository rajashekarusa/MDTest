Web, String, Uri, String, NavigationType, Boolean, Boolean# NavigationExtensions.AddNavigationNode members
Add a node to quick launch, top navigation bar or search navigation. The node will be added as the last node in the
            collection.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddNavigationNode(Web, String, Uri, String, NavigationType, Boolean, Boolean)
```
### Parameters
#### web
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
#### 
#### nodeTitle
Type: [System.String](System.String.md) 
#### 
#### nodeUri
Type: [System.Uri](System.Uri.md) 
#### 
#### parentNodeTitle
Type: [System.String](System.String.md) 
#### 
#### navigationType
Type: [OfficeDevPnP.Core.Enums.NavigationType](OfficeDevPnP.Core.Enums.NavigationType.md) 
#### 
#### (optional) isExternal
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) asLastNode
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.NavigationNode](Microsoft.SharePoint.Client.NavigationNode.md)Newly added NavigationNode
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
