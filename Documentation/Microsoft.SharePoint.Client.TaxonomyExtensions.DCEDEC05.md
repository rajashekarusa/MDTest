Site, String[], Int32, TermStore, String, Boolean# TaxonomyExtensions.ImportTerms members
Imports an array of | delimited strings into the deafult site collection termstore. Specify strings in this format:
             TermGroup|TermSet|Term
             
             E.g. "Locations|Nordics|Sweden"  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ImportTerms(Site, String[], Int32, TermStore, String, Boolean)
```
### Parameters
#### site
Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
#### 
#### termLines
Type: [System.String[]](System.String[].md) 
#### 
#### lcid
Type: [System.Int32](System.Int32.md) 
#### 
#### termStore
Type: [Microsoft.SharePoint.Client.Taxonomy.TermStore](Microsoft.SharePoint.Client.Taxonomy.TermStore.md) 
#### 
#### (optional) delimiter
Type: [System.String](System.String.md) 
#### 
#### (optional) synchronizeDeletions
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
