# BrandingExtensions
Class that holds the deprecated branding methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class BrandingExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [DisableReponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.bb864eed.md) | Disables the Responsive UI on a Classic SharePoint Site
| [DisableReponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.74132147.md) | Disables the Responsive UI on a Classic SharePoint Web
| [ComposedLookExists(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.8b080f34.md) | Checks if a composed look exists.
| [CreateComposedLookByName(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.740548bb.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [CreateComposedLookByUrl(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.c9d5a1a3.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [SetComposedLookByUrl(Web, String, String, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.cfb62650.md) | Retrieves the named composed look, overrides with specified palette, font, background and master page, and then recursively sets the specified values.
| [SetThemeByUrl(Web, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.4bbb0290.md) | Recursively applies the specified palette, font, and background image.
| [UploadThemeFile(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.1dd5757d.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.80e3ffa7.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, Stream, String)](Microsoft.SharePoint.Client.BrandingExtensions.38560132.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [DeployPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.27a51e60.md) | 
| [DeployHtmlPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.9325730f.md) | 
| [DeployMasterPage(Web, String, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.80e54a26.md) | Deploys a new masterpage
| [SetMasterPagesByName(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.ba4e10c4.md) | Can be used to set master page and custom master page in single command
| [SetMasterPagesByUrl(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.a5f0fb38.md) | Can be used to set master page and custom master page in single command
| [SetMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.8c66b500.md) | Master page is set by using master page name. Master page is set from the current web.
| [SetCustomMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.466447f0.md) | Master page is set by using master page name. Master page is set from the current web.
| [GetRelativeUrlForMasterByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.7326b0b4.md) | Returns the relative URL for a masterpage
| [GetCurrentComposedLook(Web)](Microsoft.SharePoint.Client.BrandingExtensions.fbddcb48.md) | Returns the current theme of a web
| [GetComposedLook(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.a330b520.md) | Returns the named composed look from the web gallery
| [GetPageLayoutListItemByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.96c01769.md) | Gets a page layout from the master page catalog. Can be called with paramter as "pagelayout.aspx" or as full path like "_catalog/masterpage/pagelayout.aspx"
| [SetMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.7b48ca5d.md) | Set master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetCustomMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.75358b14.md) | Set Custom master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetDefaultPageLayoutForSite(Web, Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.243814be.md) | Sets specific page layout the default page layout for the particular site
| [SetSiteToInheritPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.e4957e9d.md) | Can be used to set the site to inherit the default page layout option from parent. Cannot be used for root site of the site collection
| [AllowAllPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.a6488d6.md) | Allow the web to use all available page layouts
| [SetAvailablePageLayouts(Web, Web, IEnumerable<String>)](Microsoft.SharePoint.Client.BrandingExtensions.dc5b39bf.md) | 
| [SetAvailableWebTemplates(Web, List<WebTemplateEntity>)](Microsoft.SharePoint.Client.BrandingExtensions.99c4bf57.md) | 
| [ClearAvailableWebTemplates(Web)](Microsoft.SharePoint.Client.BrandingExtensions.51affb5f.md) | Can be used to remote filters from the available web template
| [SetHomePage(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.faac5aeb.md) | Sets the web home page
| [EnableResponsiveUI(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.e725b3ed.md) | Enables the responsive UI of a classic SharePoint Web
| [EnableResponsiveUI(Site, String)](Microsoft.SharePoint.Client.BrandingExtensions.3ce3c068.md) | Enables the responsive UI of a classic SharePoint Site
| [DisableResponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.19801284.md) | Disables the Responsive UI on a Classic SharePoint Web
| [DisableResponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.64f93e6e.md) | Disables the Responsive UI on a Classic SharePoint Site
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
