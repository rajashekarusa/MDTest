# TaxonomyExtensions.AddTermToTermset Method  
Adds a term to a given termset  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddTermToTermset(Site site,Guid termSetId,String term,Guid termId)
```
### Parameters
*site*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Site  
&emsp;&emsp;The current site  
  
*termSetId*  
&emsp;&emsp;Type: System.Guid  
&emsp;&emsp;The ID of the termset  
  
*term*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The label of the new term to create  
  
*termId*  
&emsp;&emsp;Type: System.Guid  
&emsp;&emsp;The ID of the term to create  
  
### Return Value
Type: Microsoft.SharePoint.Client.Taxonomy.Term  


## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
