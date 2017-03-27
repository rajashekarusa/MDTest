# PageExtensions
Class that holds all deprecated page and web part related operations
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class PageExtensions```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetWikiPageContent(Web, String)](PageExtensionsGetWikiPageContentWebString.md) | Returns the HTML contents of a wiki page
| [GetWebParts(Web, String)](PageExtensionsGetWebPartsWebString.md) | List the web parts on a page
| [AddWebPartToWebPartPage(Web, OfficeDevPnP.Core.Entities.WebPartEntity, String)](PageExtensionsAddWebPartToWebPartPageWebOfficeDevPnP.Core.Entities.WebPartEntityString.md) | Inserts a web part on a web part page
| [AddWebPartToWebPartPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity)](PageExtensionsAddWebPartToWebPartPageWebStringOfficeDevPnP.Core.Entities.WebPartEntity.md) | Inserts a web part on a web part page
| [AddWebPartToWikiPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity, String, Int32, Int32, Boolean)](PageExtensionsAddWebPartToWikiPageWebStringOfficeDevPnP.Core.Entities.WebPartEntityStringInt32Int32Boolean.md) | Add web part to a wiki style page
| [AddWebPartToWikiPage(Web, String, OfficeDevPnP.Core.Entities.WebPartEntity, Int32, Int32, Boolean)](PageExtensionsAddWebPartToWikiPageWebStringOfficeDevPnP.Core.Entities.WebPartEntityInt32Int32Boolean.md) | Add web part to a wiki style page
| [GetWebPartXml(Web, Guid, String)](PageExtensionsGetWebPartXmlWebGuidString.md) | 
| [AddLayoutToWikiPage(Web, OfficeDevPnP.Core.WikiPageLayout, String)](PageExtensionsAddLayoutToWikiPageWebOfficeDevPnP.Core.WikiPageLayoutString.md) | Applies a layout to a wiki page
| [AddLayoutToWikiPage(Web, String, OfficeDevPnP.Core.WikiPageLayout, String)](PageExtensionsAddLayoutToWikiPageWebStringOfficeDevPnP.Core.WikiPageLayoutString.md) | Applies a layout to a wiki page
| [AddHtmlToWikiPage(Web, String, String, String)](PageExtensionsAddHtmlToWikiPageWebStringStringString.md) | Add html to a wiki style page
| [AddHtmlToWikiPage(Web, String, String)](PageExtensionsAddHtmlToWikiPageWebStringString.md) | Add HTML to a wiki page
| [AddHtmlToWikiPage(Web, String, String, String, Int32, Int32)](PageExtensionsAddHtmlToWikiPageWebStringStringStringInt32Int32.md) | Add a HTML fragment to a location on a wiki style page
| [AddHtmlToWikiPage(Web, String, String, Int32, Int32)](PageExtensionsAddHtmlToWikiPageWebStringStringInt32Int32.md) | Add a HTML fragment to a location on a wiki style page
| [DeleteWebPart(Web, String, String, String)](PageExtensionsDeleteWebPartWebStringStringString.md) | Deletes a web part from a page
| [DeleteWebPart(Web, String, String)](PageExtensionsDeleteWebPartWebStringString.md) | Deletes a web part from a page
| [AddClientSidePage(Web, String, Boolean)](PageExtensionsAddClientSidePageWebStringBoolean.md) | Adds a client side "modern" page to a "classic" or "modern" site
| [LoadClientSidePage(Web, String)](PageExtensionsLoadClientSidePageWebString.md) | Loads a client side "modern" page
| [AddWikiPage(Web, String, String)](PageExtensionsAddWikiPageWebStringString.md) | Adds a blank Wiki page to the site pages library
| [EnsureWikiPage(Web, String, String)](PageExtensionsEnsureWikiPageWebStringString.md) | Returns the Url for the requested wiki page, creates it if the pageis not yet available
| [WikiPageImplementation(Web, String, String, String&, List&, String&, File&, String&)](PageExtensionsWikiPageImplementationWebStringStringString&List&String&File&String&.md) | 
| [AddWikiPageByUrl(Web, String, String)](PageExtensionsAddWikiPageByUrlWebStringString.md) | Adds a wiki page by Url
| [SetWebPartProperty(Web, String, String, Guid, String)](PageExtensionsSetWebPartPropertyWebStringStringGuidString.md) | Sets a web part property
| [SetWebPartProperty(Web, String, Int32, Guid, String)](PageExtensionsSetWebPartPropertyWebStringInt32GuidString.md) | Sets a web part property
| [SetWebPartProperty(Web, String, Boolean, Guid, String)](PageExtensionsSetWebPartPropertyWebStringBooleanGuidString.md) | Sets a web part property
| [AddWebPart(File, OfficeDevPnP.Core.Entities.WebPartEntity, String, Int32)](PageExtensionsAddWebPartFileOfficeDevPnP.Core.Entities.WebPartEntityStringInt32.md) | 
| [SetWebPartPropertyInternal(Web, String, Object, Guid, String)](PageExtensionsSetWebPartPropertyInternalWebStringObjectGuidString.md) | 
| [GetWebPartProperties(Web, Guid, String)](PageExtensionsGetWebPartPropertiesWebGuidString.md) | Returns web part properties
| [AddNavigationFriendlyUrl(Publishing.PublishingPage, Web, String, String, Publishing.Navigation.NavigationTermSetItem, Boolean, Boolean)](PageExtensionsAddNavigationFriendlyUrlPublishing.PublishingPageWebStringStringPublishing.Navigation.NavigationTermSetItemBooleanBoolean.md) | Adds a user-friendly URL for a PublishingPage object.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
