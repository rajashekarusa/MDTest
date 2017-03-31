# TaxonomyExtensions.EnsureTermGroup Method  
Ensures the named group exists, returning a reference to the group, and creating or updating as necessary.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  EnsureTermGroup(Site site,String groupName,Guid groupId,String groupDescription)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
&emsp;&emsp;  
  
*groupName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) groupId*  
&emsp;&emsp;Type: [System.Guid](System.Guid.md) 
&emsp;&emsp;  
  
*(optional) groupDescription*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Taxonomy.TermGroup](Microsoft.SharePoint.Client.Taxonomy.TermGroup.md)  
The required term group

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
