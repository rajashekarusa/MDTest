# TaxonomyExtensions.ImportTerms Method  
Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format:
             TermGroup|TermSet|Term
             
             E.g. "Locations|Nordics|Sweden"  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ImportTerms(Site site,String[] termLines,Int32 lcid,String delimiter,Boolean synchronizeDeletions)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site] 
&emsp;&emsp;  
  
*termLines*  
&emsp;&emsp;Type: [System.String[]] 
&emsp;&emsp;  
  
*lcid*  
&emsp;&emsp;Type: [System.Int32] 
&emsp;&emsp;  
  
*(optional) delimiter*  
&emsp;&emsp;Type: [System.String] 
&emsp;&emsp;  
  
*(optional) synchronizeDeletions*  
&emsp;&emsp;Type: [System.Boolean] 
&emsp;&emsp;Remove tags that are not present in the import  
  
### Return Value
Type: [System.Void]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
