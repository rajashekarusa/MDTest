# FieldAndContentTypeExtensions.BestMatch Method  
Searches for the content type with the closest match to the value of the specified content type ID. 
            If the search finds two matches, the shorter ID is returned.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  BestMatch(ContentTypeCollection contentTypes,String contentTypeId)
```
### Parameters
*contentTypes*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ContentTypeCollection](Microsoft.SharePoint.Client.ContentTypeCollection.md) 
&emsp;&emsp;  
  
*contentTypeId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ContentTypeId](Microsoft.SharePoint.Client.ContentTypeId.md 
)Content type Id object or null if was not found

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
