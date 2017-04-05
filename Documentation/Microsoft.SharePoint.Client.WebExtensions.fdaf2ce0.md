# WebExtensions.SiteSearch Method  
Returns the site collections that comply with the passed keyword query  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static list<siteentity> SiteSearch(Web web, String keywordQueryValue, Boolean trimDuplicates)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  
*keywordQueryValue*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Keyword query  
*(optional) trimDuplicates*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;Indicates if dublicates should be trimmed or not  
### Return Value
Type: System.Collections.Generic.List<OfficeDevPnP.Core.Entities.SiteEntity>  
All found site collections

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
