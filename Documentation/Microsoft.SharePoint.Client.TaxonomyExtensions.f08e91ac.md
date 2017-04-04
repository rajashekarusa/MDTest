# TaxonomyExtensions.GetTermGroupByName Method  
Gets the named term group, if it exists in the term store.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Microsoft.SharePoint.Client.Taxonomy.TermGroup GetTermGroupByName(TermStore termStore, String groupName)
```
### Parameters
*termStore*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Taxonomy.TermStore  
&emsp;&emsp;The term store to use  
  
*groupName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the term group  
  
### Return Value
Type: Microsoft.SharePoint.Client.Taxonomy.TermGroup  
The requested term group, or null if it does not exist

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
