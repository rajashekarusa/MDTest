# TaxonomyExtensions.GetTaxonomyItemByPath Method  
Returns a taxonomy item by it's path, e.g. Group|Set|Term  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetTaxonomyItemByPath(Site site,String path,String delimiter)
```
### Parameters
*site*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Site  
&emsp;&emsp;The current site  
  
*path*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The path of the item to return  
  
*(optional) delimiter*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The delimeter separating groups, sets and term in the path. Defaults to |  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Taxonomy.TaxonomyItem]  


## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)