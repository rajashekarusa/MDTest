# WebExtensions.IsNoScriptSite Method  
Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing.
            
            See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f
            for the effects of NoScript  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean IsNoScriptSite(Site site)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md 
)True if noscript, false otherwise

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)