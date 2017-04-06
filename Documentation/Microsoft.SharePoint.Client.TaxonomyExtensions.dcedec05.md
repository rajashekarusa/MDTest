# TaxonomyExtensions.ImportTerms Method  
Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format: TermGroup|TermSet|Term E.g. "Locations|Nordics|Sweden"  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ImportTerms(Site site, String[] termLines, Int32 lcid, TermStore termStore, String delimiter, Boolean synchronizeDeletions)
```
### Parameters
*site*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Site  

*termLines*  
&emsp;&emsp;Type: System.String[]  

*lcid*  
&emsp;&emsp;Type: System.Int32  

*termStore*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Taxonomy.TermStore  
&emsp;&emsp;The termstore to import the terms into  

*(optional) delimiter*  
&emsp;&emsp;Type: System.String  

*(optional) synchronizeDeletions*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Remove tags that are not present in the import  

### Return Value
Type: void  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
