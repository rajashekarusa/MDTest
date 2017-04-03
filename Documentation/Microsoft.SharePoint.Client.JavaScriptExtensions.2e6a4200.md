# JavaScriptExtensions.AddJsLink Method  
Injects links to javascript files via a adding a custom action to the site  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean AddJsLink(Site site,String key,String scriptLinks,Int32 sequence)
```
### Parameters
*site*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Site  
&emsp;&emsp;Site to be processed  
  
*key*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Identifier (key) for the custom action that will be created  
  
*scriptLinks*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;semi colon delimited list of links to javascript files  
  
*(optional) sequence*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean]  
True if action was ok

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)