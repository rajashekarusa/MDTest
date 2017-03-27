# BrandingExtensions
Class that holds the deprecated branding methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class BrandingExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [DisableReponsiveUI(Site)](BrandingExtensionsDisableReponsiveUISite.md) | Disables the Responsive UI on a Classic SharePoint Site
| [DisableReponsiveUI(Web)](BrandingExtensionsDisableReponsiveUIWeb.md) | Disables the Responsive UI on a Classic SharePoint Web
| [ComposedLookExists(Web, String)](BrandingExtensionsComposedLookExistsWebString.md) | Checks if a composed look exists.
| [CreateComposedLookByName(Web, String, String, String, String, String, Int32, Boolean)](BrandingExtensionsCreateComposedLookByNameWebStringStringStringStringStringInt32Boolean.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [CreateComposedLookByUrl(Web, String, String, String, String, String, Int32, Boolean)](BrandingExtensionsCreateComposedLookByUrlWebStringStringStringStringStringInt32Boolean.md) | Creates (or updates) a composed look in the web site; usually this is done in the root site of the collection.
| [SetComposedLookByUrl(Web, String, String, String, String, String, Boolean, Boolean)](BrandingExtensionsSetComposedLookByUrlWebStringStringStringStringStringBooleanBoolean.md) | Retrieves the named composed look, overrides with specified palette, font, background and master page, and then recursively sets the specified values.
| [SetThemeByUrl(Web, String, String, String, Boolean, Boolean)](BrandingExtensionsSetThemeByUrlWebStringStringStringBooleanBoolean.md) | Recursively applies the specified palette, font, and background image.
| [UploadThemeFile(Web, String, String)](BrandingExtensionsUploadThemeFileWebStringString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, String, String)](BrandingExtensionsUploadThemeFileWebStringStringString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [UploadThemeFile(Web, String, IO.Stream, String)](BrandingExtensionsUploadThemeFileWebStringIO.StreamString.md) | Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery (usually only exists in the root web of a site collection).
| [DeployPageLayout(Web, String, String, String, String, String)](BrandingExtensionsDeployPageLayoutWebStringStringStringStringString.md) | 
| [DeployHtmlPageLayout(Web, String, String, String, String, String)](BrandingExtensionsDeployHtmlPageLayoutWebStringStringStringStringString.md) | 
| [DeployMasterPageGalleryItem(Web, String, String, String, String, String, String)](BrandingExtensionsDeployMasterPageGalleryItemWebStringStringStringStringStringString.md) | Private method to support all kinds of file uploads to the master page gallery
| [DeployMasterPage(Web, String, String, String, String, String, String)](BrandingExtensionsDeployMasterPageWebStringStringStringStringStringString.md) | Deploys a new masterpage
| [SetMasterPagesByName(Web, String, String)](BrandingExtensionsSetMasterPagesByNameWebStringString.md) | Can be used to set master page and custom master page in single command
| [SetMasterPagesByUrl(Web, String, String)](BrandingExtensionsSetMasterPagesByUrlWebStringString.md) | Can be used to set master page and custom master page in single command
| [SetMasterPageByName(Web, String)](BrandingExtensionsSetMasterPageByNameWebString.md) | Master page is set by using master page name. Master page is set from the current web.
| [SetCustomMasterPageByName(Web, String)](BrandingExtensionsSetCustomMasterPageByNameWebString.md) | Master page is set by using master page name. Master page is set from the current web.
| [GetRelativeUrlForMasterByName(Web, String)](BrandingExtensionsGetRelativeUrlForMasterByNameWebString.md) | Returns the relative URL for a masterpage
| [GetLocalizedCurrentValue(Web)](BrandingExtensionsGetLocalizedCurrentValueWeb.md) | 
| [GetCurrentComposedLook(Web)](BrandingExtensionsGetCurrentComposedLookWeb.md) | Returns the current theme of a web
| [GetComposedLook(Web, String)](BrandingExtensionsGetComposedLookWebString.md) | Returns the named composed look from the web gallery
| [IsMatchingTheme(OfficeDevPnP.Core.Entities.ThemeEntity, String, String, String)](BrandingExtensionsIsMatchingThemeOfficeDevPnP.Core.Entities.ThemeEntityStringStringString.md) | Compares master page URL, theme URL and font URL values to current theme entity to check if they are the same. Handles also possible null values. Point is to figure out which theme is the one that is currently being selected as "Current"
| [IsUsingOfficeTheme(Web)](BrandingExtensionsIsUsingOfficeThemeWeb.md) | 
| [GetPageLayoutListItemByName(Web, String)](BrandingExtensionsGetPageLayoutListItemByNameWebString.md) | Gets a page layout from the master page catalog. Can be called with paramter as "pagelayout.aspx" or as full path like "_catalog/masterpage/pagelayout.aspx"
| [SetMasterPageByUrl(Web, String, Boolean, Boolean)](BrandingExtensionsSetMasterPageByUrlWebStringBooleanBoolean.md) | Set master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetCustomMasterPageByUrl(Web, String, Boolean, Boolean)](BrandingExtensionsSetCustomMasterPageByUrlWebStringBooleanBoolean.md) | Set Custom master page by using given URL as parameter. Suitable for example in cases where you want sub sites to reference root site master page gallery. This is typical with publishing sites.
| [SetDefaultPageLayoutForSite(Web, Web, String)](BrandingExtensionsSetDefaultPageLayoutForSiteWebWebString.md) | Sets specific page layout the default page layout for the particular site
| [CreateXmlNodeFromPageLayout(Xml.XmlDocument, Web, Web, String)](BrandingExtensionsCreateXmlNodeFromPageLayoutXml.XmlDocumentWebWebString.md) | 
| [SolveSiteRelativeUrl(Web, String)](BrandingExtensionsSolveSiteRelativeUrlWebString.md) | 
| [SetSiteToInheritPageLayouts(Web)](BrandingExtensionsSetSiteToInheritPageLayoutsWeb.md) | Can be used to set the site to inherit the default page layout option from parent. Cannot be used for root site of the site collection
| [AllowAllPageLayouts(Web)](BrandingExtensionsAllowAllPageLayoutsWeb.md) | Allow the web to use all available page layouts
| [SetAvailablePageLayouts(Web, Web, Collections.Generic.IEnumerable1<String>)](BrandingExtensionsSetAvailablePageLayoutsWebWebCollections.Generic.IEnumerable1<String>.md) | 
| [SetAvailableWebTemplates(Web, Collections.Generic.List1<OfficeDevPnP.Core.Entities.WebTemplateEntity>)](BrandingExtensionsSetAvailableWebTemplatesWebCollections.Generic.List1<OfficeDevPnP.Core.Entities.WebTemplateEntity>.md) | 
| [ClearAvailableWebTemplates(Web)](BrandingExtensionsClearAvailableWebTemplatesWeb.md) | Can be used to remote filters from the available web template
| [AddTemplateToCollection(Collections.Generic.Dictionary2<String,Collections.Generic.List1<String>>, OfficeDevPnP.Core.Entities.WebTemplateEntity)](BrandingExtensionsAddTemplateToCollectionCollections.Generic.Dictionary2<String,Collections.Generic.List1<String>>OfficeDevPnP.Core.Entities.WebTemplateEntity.md) | 
| [SetHomePage(Web, String)](BrandingExtensionsSetHomePageWebString.md) | Sets the web home page
| [EnableResponsiveUI(Web, String)](BrandingExtensionsEnableResponsiveUIWebString.md) | Enables the responsive UI of a classic SharePoint Web
| [EnableResponsiveUI(Site, String)](BrandingExtensionsEnableResponsiveUISiteString.md) | Enables the responsive UI of a classic SharePoint Site
| [EnableResponsiveUIImplementation(ClientObject, String)](BrandingExtensionsEnableResponsiveUIImplementationClientObjectString.md) | Enables the responsive UI of a classic SharePoint Web or Site
| [UploadStringAsFile(Web, Folder, String, String)](BrandingExtensionsUploadStringAsFileWebFolderStringString.md) | 
| [DisableResponsiveUI(Web)](BrandingExtensionsDisableResponsiveUIWeb.md) | Disables the Responsive UI on a Classic SharePoint Web
| [DisableResponsiveUI(Site)](BrandingExtensionsDisableResponsiveUISite.md) | Disables the Responsive UI on a Classic SharePoint Site
| [CheckOutIfNeeded(Web, File)](BrandingExtensionsCheckOutIfNeededWebFile.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
