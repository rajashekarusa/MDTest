# TaxonomyExtensions.ImportTerms Method  
Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format:
             TermGroup|TermSet|Term
             
             E.g. "Locations|Nordics|Sweden"  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ImportTerms(Site site,String[] termLines,Int32 lcid,TermStore termStore,String delimiter,Boolean synchronizeDeletions)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
&emsp;&emsp;  
  
*termLines*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*lcid*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*termStore*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Taxonomy.TermStore](Microsoft.SharePoint.Client.Taxonomy.TermStore.md) 
&emsp;&emsp;  
  
*(optional) delimiter*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) synchronizeDeletions*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
