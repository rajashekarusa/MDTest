Web# WebExtensions.IsNoScriptSite members
Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing.
            
            See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f
            for the effects of NoScript  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean IsNoScriptSite(Web)
```
### Parameters
#### web
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
#### 
### Return Value
Type: [System.Boolean](System.Boolean.md)True if noscript, false otherwise
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
