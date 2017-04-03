# NavigationExtensions.AddCustomAction Method  
Adds custom action to a web. If the CustomAction exists the item will be updated.
            Setting CustomActionEntity.Remove == true will delete the CustomAction.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean AddCustomAction(Web web,CustomActionEntity customAction)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Site to be processed - can be root web or sub site  
  
*customAction*  
&emsp;&emsp;Type: [OfficeDevPnP.Core.Entities.CustomActionEntity](OfficeDevPnP.Core.Entities.CustomActionEntity.md) 
&emsp;&emsp;Information about the custom action be added or deleted  
  
### Return Value
Type: [System.Boolean]  
True if action was successfull

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)