# TaxonomyExtensions.ExportTermSet Method  
Exports the full list of terms from all termsets in all termstores.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<system.string> ExportTermSet(Site site,Guid termSetId,Boolean includeId,TermStore termStore,String delimiter)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
&emsp;&emsp;  
  
*termSetId*  
&emsp;&emsp;Type: [System.Guid](System.Guid.md) 
&emsp;&emsp;  
  
*includeId*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*termStore*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Taxonomy.TermStore](Microsoft.SharePoint.Client.Taxonomy.TermStore.md) 
&emsp;&emsp;  
  
*(optional) delimiter*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.List`1<System.String>](System.Collections.Generic.List`1<System.String>.md 
)

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
