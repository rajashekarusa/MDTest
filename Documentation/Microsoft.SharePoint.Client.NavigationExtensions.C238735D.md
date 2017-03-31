Site, CustomActionEntity# NavigationExtensions.AddCustomAction members
Adds custom action to a site collection. If the CustomAction exists the item will be updated.
            Setting CustomActionEntity.Remove == true will delete the CustomAction.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean AddCustomAction(Site, CustomActionEntity)
```
### Parameters
#### site
Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
#### 
#### customAction
Type: [OfficeDevPnP.Core.Entities.CustomActionEntity](OfficeDevPnP.Core.Entities.CustomActionEntity.md) 
#### 
### Return Value
Type: [System.Boolean](System.Boolean.md)True if action was successfull
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
