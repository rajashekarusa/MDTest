PublishingPage, Web, String, String, NavigationTermSetItem, Boolean, Boolean# PageExtensions.AddNavigationFriendlyUrl members
Adds a user-friendly URL for a PublishingPage object.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string AddNavigationFriendlyUrl(PublishingPage, Web, String, String, NavigationTermSetItem, Boolean, Boolean)
```
### Parameters
#### page
Type: [Microsoft.SharePoint.Client.Publishing.PublishingPage](Microsoft.SharePoint.Client.Publishing.PublishingPage.md) 
#### 
#### web
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
#### 
#### navigationTitle
Type: [System.String](System.String.md) 
#### 
#### friendlyUrlSegment
Type: [System.String](System.String.md) 
#### 
#### editableParent
Type: [Microsoft.SharePoint.Client.Publishing.Navigation.NavigationTermSetItem](Microsoft.SharePoint.Client.Publishing.Navigation.NavigationTermSetItem.md) 
#### 
#### (optional) showInGlobalNavigation
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) showInCurrentNavigation
Type: [System.Boolean](System.Boolean.md) 
#### 
### Return Value
Type: [System.String](System.String.md)The simple link URL just created.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
