# FieldAndContentTypeExtensions.GetFieldByInternalName Method  
Returns the field if it exists. Null if does not exist.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetFieldByInternalName(Web web,String internalName,Boolean searchInSiteHierarchy)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web] 
&emsp;&emsp;Web to be processed  
  
*internalName*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;If true, search parent sites and root site  
  
*(optional) searchInSiteHierarchy*  
&emsp;&emsp;Type: [System.Boolean] 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Field]  


## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
