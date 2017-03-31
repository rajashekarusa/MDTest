ContentTypeCollection, String# FieldAndContentTypeExtensions.BestMatch members
Searches for the content type with the closest match to the value of the specified content type ID. 
            If the search finds two matches, the shorter ID is returned.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  BestMatch(ContentTypeCollection, String)
```
### Parameters
#### contentTypes
Type: [Microsoft.SharePoint.Client.ContentTypeCollection](Microsoft.SharePoint.Client.ContentTypeCollection.md) 
#### 
#### contentTypeId
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.ContentTypeId](Microsoft.SharePoint.Client.ContentTypeId.md)Content type Id object or null if was not found
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
