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
| [DisableReponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.BB864EED.md) | Disables the Responsive UI on a Classic SharePoint Site
| [DisableReponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.74132147.md) | Disables the Responsive UI on a Classic SharePoint Web
| [ComposedLookExists(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.8B080F34.md) | Checks if a composed look exists.
| [CreateComposedLookByName(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.740548BB.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [CreateComposedLookByUrl(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.C9D5A1A3.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [SetComposedLookByUrl(Web, String, String, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.CFB62650.md) | Retrieves the named composed look, overrides with specified palette, font, background and master page, and then recursively sets the specified values.
| [SetThemeByUrl(Web, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.4BBB0290.md) | Recursively applies the specified palette, font, and background image.
| [UploadThemeFile(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.1DD5757D.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.80E3FFA7.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, Stream, String)](Microsoft.SharePoint.Client.BrandingExtensions.38560132.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [DeployPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.27A51E60.md) | 
| [DeployHtmlPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.9325730F.md) | 
| [DeployMasterPageGalleryItem(Web, String, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.AD7C0AFA.md) | Private method to support all kinds of file uploads to the master page gallery
| [DeployMasterPage(Web, String, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.80E54A26.md) | Deploys a new masterpage
| [SetMasterPagesByName(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.BA4E10C4.md) | Can be used to set master page and custom master page in single command
| [SetMasterPagesByUrl(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.A5F0FB38.md) | Can be used to set master page and custom master page in single command
| [SetMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.8C66B500.md) | Master page is set by using master page name. Master page is set from the current web.
| [SetCustomMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.466447F0.md) | Master page is set by using master page name. Master page is set from the current web.
| [GetRelativeUrlForMasterByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.7326B0B4.md) | Returns the relative URL for a masterpage
| [GetLocalizedCurrentValue(Web)](Microsoft.SharePoint.Client.BrandingExtensions.D1B1B62A.md) | 
| [GetCurrentComposedLook(Web)](Microsoft.SharePoint.Client.BrandingExtensions.FBDDCB48.md) | Returns the current theme of a web
| [GetComposedLook(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.A330B520.md) | Returns the named composed look from the web gallery
| [IsMatchingTheme(ThemeEntity, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.D75EA246.md) | Compares master page URL, theme URL and font URL values to current theme entity to check if they are the same. Handles also possible null values. Point is to figure out which theme is the one that is currently being selected as "Current"
| [IsUsingOfficeTheme(Web)](Microsoft.SharePoint.Client.BrandingExtensions.6796FA9C.md) | 
| [GetPageLayoutListItemByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.96C01769.md) | Gets a page layout from the master page catalog. Can be called with paramter as "pagelayout.aspx" or as full path like "_catalog/masterpage/pagelayout.aspx"
| [SetMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.7B48CA5D.md) | Set master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetCustomMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.75358B14.md) | Set Custom master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetDefaultPageLayoutForSite(Web, Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.243814BE.md) | Sets specific page layout the default page layout for the particular site
| [CreateXmlNodeFromPageLayout(XmlDocument, Web, Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.B02194DC.md) | 
| [SolveSiteRelativeUrl(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.A3DCF811.md) | 
| [SetSiteToInheritPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.E4957E9D.md) | Can be used to set the site to inherit the default page layout option from parent. Cannot be used for root site of the site collection
| [AllowAllPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.A6488D6.md) | Allow the web to use all available page layouts
| [SetAvailablePageLayouts(Web, Web, IEnumerable<String>)](Microsoft.SharePoint.Client.BrandingExtensions.DC5B39BF.md) | 
| [SetAvailableWebTemplates(Web, List<WebTemplateEntity>)](Microsoft.SharePoint.Client.BrandingExtensions.99C4BF57.md) | 
| [ClearAvailableWebTemplates(Web)](Microsoft.SharePoint.Client.BrandingExtensions.51AFFB5F.md) | Can be used to remote filters from the available web template
| [AddTemplateToCollection(Dictionary<String, List<String>>, WebTemplateEntity)](Microsoft.SharePoint.Client.BrandingExtensions.9EC762E8.md) | 
| [SetHomePage(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.FAAC5AEB.md) | Sets the web home page
| [EnableResponsiveUI(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.E725B3ED.md) | Enables the responsive UI of a classic SharePoint Web
| [EnableResponsiveUI(Site, String)](Microsoft.SharePoint.Client.BrandingExtensions.3CE3C068.md) | Enables the responsive UI of a classic SharePoint Site
| [EnableResponsiveUIImplementation(ClientObject, String)](Microsoft.SharePoint.Client.BrandingExtensions.CF8B0F78.md) | Enables the responsive UI of a classic SharePoint Web or Site
| [UploadStringAsFile(Web, Folder, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.F86832B2.md) | 
| [DisableResponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.19801284.md) | Disables the Responsive UI on a Classic SharePoint Web
| [DisableResponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.64F93E6E.md) | Disables the Responsive UI on a Classic SharePoint Site
| [CheckOutIfNeeded(Web, File)](Microsoft.SharePoint.Client.BrandingExtensions.AAEF8EC2.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
