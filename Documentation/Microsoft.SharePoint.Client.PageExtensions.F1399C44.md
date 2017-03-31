# PageExtensions.AddNavigationFriendlyUrl Method  
Adds a user-friendly URL for a PublishingPage object.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string AddNavigationFriendlyUrl(PublishingPage page,Web web,String navigationTitle,String friendlyUrlSegment,NavigationTermSetItem editableParent,Boolean showInGlobalNavigation,Boolean showInCurrentNavigation)
```
### Parameters
*page*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Publishing.PublishingPage](Microsoft.SharePoint.Client.Publishing.PublishingPage.md) 
&emsp;&emsp;  
  
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*navigationTitle*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*friendlyUrlSegment*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*editableParent*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Publishing.Navigation.NavigationTermSetItem](Microsoft.SharePoint.Client.Publishing.Navigation.NavigationTermSetItem.md) 
&emsp;&emsp;  
  
*(optional) showInGlobalNavigation*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) showInCurrentNavigation*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.String](System.String.md 
)The simple link URL just created.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
