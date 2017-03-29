# PageExtensions
Class that holds all deprecated page and web part related operations  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class PageExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetWikiPageContent(Web, String)](Microsoft.SharePoint.Client.PageExtensions.GetWikiPageContentWebString.md) | Returns the HTML contents of a wiki page
| [GetWebParts(Web, String)](Microsoft.SharePoint.Client.PageExtensions.GetWebPartsWebString.md) | List the web parts on a page
| [AddWebPartToWebPartPage(Web, OfficeDevPnP.Core.Entities.WebPartEntity, String)](Microsoft.SharePoint.Client.PageExtensions.AddWebPartToWebPartPageWebOfficeDevPnP.Core.Entities.WebPartEntityString.md) | Inserts a web part on a web part page
| [AddWebPartToWebPartPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity)](Microsoft.SharePoint.Client.PageExtensions.AddWebPartToWebPartPageWebStringOfficeDevPnP.Core.Entities.WebPartEntity.md) | Inserts a web part on a web part page
| [AddWebPartToWikiPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity, String, Int32, Int32, Boolean)](Microsoft.SharePoint.Client.PageExtensions.AddWebPartToWikiPageWebStringOfficeDevPnP.Core.Entities.WebPartEntityStringInt32Int32Boolean.md) | Add web part to a wiki style page
| [AddWebPartToWikiPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity, Int32, Int32, Boolean)](Microsoft.SharePoint.Client.PageExtensions.AddWebPartToWikiPageWebStringOfficeDevPnP.Core.Entities.WebPartEntityInt32Int32Boolean.md) | Add web part to a wiki style page
| [GetWebPartXml(Web, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.GetWebPartXmlWebGuidString.md) | 
| [AddLayoutToWikiPage(Web, OfficeDevPnP.Core.WikiPageLayout, String)](Microsoft.SharePoint.Client.PageExtensions.AddLayoutToWikiPageWebOfficeDevPnP.Core.WikiPageLayoutString.md) | Applies a layout to a wiki page
| [AddLayoutToWikiPage(Web, String, OfficeDevPnP.Core.WikiPageLayout, String)](Microsoft.SharePoint.Client.PageExtensions.AddLayoutToWikiPageWebStringOfficeDevPnP.Core.WikiPageLayoutString.md) | Applies a layout to a wiki page
| [AddHtmlToWikiPage(Web, String, String, String)](Microsoft.SharePoint.Client.PageExtensions.AddHtmlToWikiPageWebStringStringString.md) | Add html to a wiki style page
| [AddHtmlToWikiPage(Web, String, String)](Microsoft.SharePoint.Client.PageExtensions.AddHtmlToWikiPageWebStringString.md) | Add HTML to a wiki page
| [AddHtmlToWikiPage(Web, String, String, String, Int32, Int32)](Microsoft.SharePoint.Client.PageExtensions.AddHtmlToWikiPageWebStringStringStringInt32Int32.md) | Add a HTML fragment to a location on a wiki style page
| [AddHtmlToWikiPage(Web, String, String, Int32, Int32)](Microsoft.SharePoint.Client.PageExtensions.AddHtmlToWikiPageWebStringStringInt32Int32.md) | Add a HTML fragment to a location on a wiki style page
| [DeleteWebPart(Web, String, String, String)](Microsoft.SharePoint.Client.PageExtensions.DeleteWebPartWebStringStringString.md) | Deletes a web part from a page
| [DeleteWebPart(Web, String, String)](Microsoft.SharePoint.Client.PageExtensions.DeleteWebPartWebStringString.md) | Deletes a web part from a page
| [AddClientSidePage(Web, String, Boolean)](Microsoft.SharePoint.Client.PageExtensions.AddClientSidePageWebStringBoolean.md) | Adds a client side "modern" page to a "classic" or "modern" site
| [LoadClientSidePage(Web, String)](Microsoft.SharePoint.Client.PageExtensions.LoadClientSidePageWebString.md) | Loads a client side "modern" page
| [AddWikiPage(Web, String, String)](Microsoft.SharePoint.Client.PageExtensions.AddWikiPageWebStringString.md) | Adds a blank Wiki page to the site pages library
| [EnsureWikiPage(Web, String, String)](Microsoft.SharePoint.Client.PageExtensions.EnsureWikiPageWebStringString.md) | Returns the Url for the requested wiki page, creates it if the pageis not yet available
| [WikiPageImplementation(Web, String, String, String&, List&, String&, File&, String&)](Microsoft.SharePoint.Client.PageExtensions.WikiPageImplementationWebStringStringString&List&String&File&String&.md) | 
| [AddWikiPageByUrl(Web, String, String)](Microsoft.SharePoint.Client.PageExtensions.AddWikiPageByUrlWebStringString.md) | Adds a wiki page by Url
| [SetWebPartProperty(Web, String, String, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.SetWebPartPropertyWebStringStringGuidString.md) | Sets a web part property
| [SetWebPartProperty(Web, String, Int32, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.SetWebPartPropertyWebStringInt32GuidString.md) | Sets a web part property
| [SetWebPartProperty(Web, String, Boolean, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.SetWebPartPropertyWebStringBooleanGuidString.md) | Sets a web part property
| [AddWebPart(File, OfficeDevPnP.Core.Entities.WebPartEntity, String, Int32)](Microsoft.SharePoint.Client.PageExtensions.AddWebPartFileOfficeDevPnP.Core.Entities.WebPartEntityStringInt32.md) | 
| [SetWebPartPropertyInternal(Web, String, Object, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.SetWebPartPropertyInternalWebStringObjectGuidString.md) | 
| [GetWebPartProperties(Web, Guid, String)](Microsoft.SharePoint.Client.PageExtensions.GetWebPartPropertiesWebGuidString.md) | Returns web part properties
| [AddNavigationFriendlyUrl(Publishing.PublishingPage, Web, String, String, Publishing.Navigation.NavigationTermSetItem, Boolean, Boolean)](Microsoft.SharePoint.Client.PageExtensions.AddNavigationFriendlyUrlPublishing.PublishingPageWebStringStringPublishing.Navigation.NavigationTermSetItemBooleanBoolean.md) | Adds a user-friendly URL for a PublishingPage object.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
