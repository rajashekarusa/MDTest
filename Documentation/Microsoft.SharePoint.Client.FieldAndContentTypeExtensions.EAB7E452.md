List, String# FieldAndContentTypeExtensions.BestMatchContentTypeId members
Searches the list content types and returns the content type identifier (ID) that is the 
            nearest match to the specified content type ID.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  BestMatchContentTypeId(List, String)
```
### Parameters
#### list
Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
#### 
#### baseContentTypeId
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ContentTypeId](Microsoft.SharePoint.Client.ContentTypeId.md)The value of the Id property for the content type with the closest match to the value 
            of the specified content type ID. 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
