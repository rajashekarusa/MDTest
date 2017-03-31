# FieldAndContentTypeExtensions.BestMatchContentTypeId Method  
Searches the list content types and returns the content type identifier (ID) that is the 
            nearest match to the specified content type ID.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  BestMatchContentTypeId(List list,String baseContentTypeId)
```
### Parameters
*list*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
&emsp;&emsp;  
  
*baseContentTypeId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ContentTypeId](Microsoft.SharePoint.Client.ContentTypeId.md  
)The value of the Id property for the content type with the closest match to the value 
            of the specified content type ID. 

## Remarks 

            If the search finds multiple matches, the shorter ID is returned. For example, if 0x0101 is the 
            argument, and the collection contains both 0x010109 and 0x01010901, the method returns 0x010109.
            
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
