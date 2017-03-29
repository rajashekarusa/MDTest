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
| [DisableReponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.DisableReponsiveUISite.md) | Disables the Responsive UI on a Classic SharePoint Site
| [DisableReponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.DisableReponsiveUIWeb.md) | Disables the Responsive UI on a Classic SharePoint Web
| [ComposedLookExists(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.ComposedLookExistsWebString.md) | Checks if a composed look exists.
| [CreateComposedLookByName(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.CreateComposedLookByNameWebStringStringStringStringStringInt32Boolean.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [CreateComposedLookByUrl(Web, String, String, String, String, String, Int32, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.CreateComposedLookByUrlWebStringStringStringStringStringInt32Boolean.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [SetComposedLookByUrl(Web, String, String, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.SetComposedLookByUrlWebStringStringStringStringStringBooleanBoolean.md) | Retrieves the named composed look, overrides with specified palette, font, background and master page, and then recursively sets the specified values.
| [SetThemeByUrl(Web, String, String, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.SetThemeByUrlWebStringStringStringBooleanBoolean.md) | Recursively applies the specified palette, font, and background image.
| [UploadThemeFile(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.UploadThemeFileWebStringString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.UploadThemeFileWebStringStringString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, IO.Stream, String)](Microsoft.SharePoint.Client.BrandingExtensions.UploadThemeFileWebStringIO.StreamString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [DeployPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.DeployPageLayoutWebStringStringStringStringString.md) | 
| [DeployHtmlPageLayout(Web, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.DeployHtmlPageLayoutWebStringStringStringStringString.md) | 
| [DeployMasterPageGalleryItem(Web, String, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.DeployMasterPageGalleryItemWebStringStringStringStringStringString.md) | Private method to support all kinds of file uploads to the master page gallery
| [DeployMasterPage(Web, String, String, String, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.DeployMasterPageWebStringStringStringStringStringString.md) | Deploys a new masterpage
| [SetMasterPagesByName(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetMasterPagesByNameWebStringString.md) | Can be used to set master page and custom master page in single command
| [SetMasterPagesByUrl(Web, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetMasterPagesByUrlWebStringString.md) | Can be used to set master page and custom master page in single command
| [SetMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetMasterPageByNameWebString.md) | Master page is set by using master page name. Master page is set from the current web.
| [SetCustomMasterPageByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetCustomMasterPageByNameWebString.md) | Master page is set by using master page name. Master page is set from the current web.
| [GetRelativeUrlForMasterByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.GetRelativeUrlForMasterByNameWebString.md) | Returns the relative URL for a masterpage
| [GetLocalizedCurrentValue(Web)](Microsoft.SharePoint.Client.BrandingExtensions.GetLocalizedCurrentValueWeb.md) | 
| [GetCurrentComposedLook(Web)](Microsoft.SharePoint.Client.BrandingExtensions.GetCurrentComposedLookWeb.md) | Returns the current theme of a web
| [GetComposedLook(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.GetComposedLookWebString.md) | Returns the named composed look from the web gallery
| [IsMatchingTheme(OfficeDevPnP.Core.Entities.ThemeEntity, String, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.IsMatchingThemeOfficeDevPnP.Core.Entities.ThemeEntityStringStringString.md) | Compares master page URL, theme URL and font URL values to current theme entity to check if they are the same. Handles also possible null values. Point is to figure out which theme is the one that is currently being selected as "Current"
| [IsUsingOfficeTheme(Web)](Microsoft.SharePoint.Client.BrandingExtensions.IsUsingOfficeThemeWeb.md) | 
| [GetPageLayoutListItemByName(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.GetPageLayoutListItemByNameWebString.md) | Gets a page layout from the master page catalog. Can be called with paramter as "pagelayout.aspx" or as full path like "_catalog/masterpage/pagelayout.aspx"
| [SetMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.SetMasterPageByUrlWebStringBooleanBoolean.md) | Set master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetCustomMasterPageByUrl(Web, String, Boolean, Boolean)](Microsoft.SharePoint.Client.BrandingExtensions.SetCustomMasterPageByUrlWebStringBooleanBoolean.md) | Set Custom master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetDefaultPageLayoutForSite(Web, Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetDefaultPageLayoutForSiteWebWebString.md) | Sets specific page layout the default page layout for the particular site
| [CreateXmlNodeFromPageLayout(Xml.XmlDocument, Web, Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.CreateXmlNodeFromPageLayoutXml.XmlDocumentWebWebString.md) | 
| [SolveSiteRelativeUrl(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.SolveSiteRelativeUrlWebString.md) | 
| [SetSiteToInheritPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.SetSiteToInheritPageLayoutsWeb.md) | Can be used to set the site to inherit the default page layout option from parent. Cannot be used for root site of the site collection
| [AllowAllPageLayouts(Web)](Microsoft.SharePoint.Client.BrandingExtensions.AllowAllPageLayoutsWeb.md) | Allow the web to use all available page layouts
| [SetAvailablePageLayouts(Web, Web, Collections.Generic.IEnumerable<String>)](Microsoft.SharePoint.Client.BrandingExtensions.SetAvailablePageLayoutsWebWebCollections.Generic.IEnumerable<String>.md) | 
| [SetAvailableWebTemplates(Web, Collections.Generic.List<OfficeDevPnP.Core.Entities.WebTemplateEntity>)](Microsoft.SharePoint.Client.BrandingExtensions.SetAvailableWebTemplatesWebCollections.Generic.List<OfficeDevPnP.Core.Entities.WebTemplateEntity>.md) | 
| [ClearAvailableWebTemplates(Web)](Microsoft.SharePoint.Client.BrandingExtensions.ClearAvailableWebTemplatesWeb.md) | Can be used to remote filters from the available web template
| [AddTemplateToCollection(Collections.Generic.Dictionary<String,Collections.Generic.List<String>>, OfficeDevPnP.Core.Entities.WebTemplateEntity)](Microsoft.SharePoint.Client.BrandingExtensions.AddTemplateToCollectionCollections.Generic.Dictionary<String,Collections.Generic.List<String>>OfficeDevPnP.Core.Entities.WebTemplateEntity.md) | 
| [SetHomePage(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.SetHomePageWebString.md) | Sets the web home page
| [EnableResponsiveUI(Web, String)](Microsoft.SharePoint.Client.BrandingExtensions.EnableResponsiveUIWebString.md) | Enables the responsive UI of a classic SharePoint Web
| [EnableResponsiveUI(Site, String)](Microsoft.SharePoint.Client.BrandingExtensions.EnableResponsiveUISiteString.md) | Enables the responsive UI of a classic SharePoint Site
| [EnableResponsiveUIImplementation(ClientObject, String)](Microsoft.SharePoint.Client.BrandingExtensions.EnableResponsiveUIImplementationClientObjectString.md) | Enables the responsive UI of a classic SharePoint Web or Site
| [UploadStringAsFile(Web, Folder, String, String)](Microsoft.SharePoint.Client.BrandingExtensions.UploadStringAsFileWebFolderStringString.md) | 
| [DisableResponsiveUI(Web)](Microsoft.SharePoint.Client.BrandingExtensions.DisableResponsiveUIWeb.md) | Disables the Responsive UI on a Classic SharePoint Web
| [DisableResponsiveUI(Site)](Microsoft.SharePoint.Client.BrandingExtensions.DisableResponsiveUISite.md) | Disables the Responsive UI on a Classic SharePoint Site
| [CheckOutIfNeeded(Web, File)](Microsoft.SharePoint.Client.BrandingExtensions.CheckOutIfNeededWebFile.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
