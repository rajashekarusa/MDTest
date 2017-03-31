# WebExtensions
Class that holds deprecated methods for site (both site collection and web site) creation, status, retrieval and settings  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class WebExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetBaseTemplateId(Web)](Microsoft.SharePoint.Client.WebExtensions.F90C56F2.md) | Returns the Base Template ID for the current web
| [CreateWeb(Web, SiteEntity, Boolean, Boolean)](Microsoft.SharePoint.Client.WebExtensions.6792428F.md) | Adds a new child Web (site) to a parent Web.
| [CreateWeb(Web, String, String, String, String, Int32, Boolean, Boolean)](Microsoft.SharePoint.Client.WebExtensions.593E8E9D.md) | Adds a new child Web (site) to a parent Web.
| [DeleteWeb(Web, String)](Microsoft.SharePoint.Client.WebExtensions.34D305DE.md) | Deletes the child website with the specified leaf URL, from a parent Web, if it exists.
| [GetAllWebUrls(Site)](Microsoft.SharePoint.Client.WebExtensions.3201F18F.md) | Gets the collection of the URLs of all Web sites that are contained within the site collection, including the top-level site and its subsites.
| [GetWeb(Web, String)](Microsoft.SharePoint.Client.WebExtensions.F4D9AE5B.md) | Returns the child Web site with the specified leaf URL.
| [WebExists(Web, String)](Microsoft.SharePoint.Client.WebExtensions.9FABA1E2.md) | Determines if a child Web site with the specified leaf URL exists.
| [WebExistsFullUrl(ClientRuntimeContext, String)](Microsoft.SharePoint.Client.WebExtensions.5F46FD34.md) | Determines if a Web (site) exists at the specified full URL, either accessible or that returns an access error.
| [WebExistsByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.D29A4F65.md) | Determines if a web exists by title.
| [IsSubSite(Web)](Microsoft.SharePoint.Client.WebExtensions.3F4614D5.md) | Checks if the current web is a sub site or not
| [IsPublishingWeb(Web)](Microsoft.SharePoint.Client.WebExtensions.471E4515.md) | 
| [IsNoScriptSite(Site)](Microsoft.SharePoint.Client.WebExtensions.F9298408.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsNoScriptSite(Web)](Microsoft.SharePoint.Client.WebExtensions.E5B2B186.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsCannotGetSiteException(Exception)](Microsoft.SharePoint.Client.WebExtensions.21D08CEE.md) | 
| [IsUnableToAccessSiteException(Exception)](Microsoft.SharePoint.Client.WebExtensions.7504D4FC.md) | 
| [GetAppInstances(Web, Expression<Func<AppInstance, Object>>[])](Microsoft.SharePoint.Client.WebExtensions.B057F688.md) | 
| [RemoveAppInstanceByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.CE847939.md) | Removes the app instance with the specified title.
| [InstallSolution(Site, Guid, String, Int32, Int32)](Microsoft.SharePoint.Client.WebExtensions.8E60CD11.md) | Uploads and installs a sandbox solution package (.WSP) file, replacing existing solution if necessary.
| [UninstallSolution(Site, Guid, String, Int32, Int32)](Microsoft.SharePoint.Client.WebExtensions.CB455E2D.md) | Uninstalls a sandbox solution package (.WSP) file
| [MySiteSearch(Web)](Microsoft.SharePoint.Client.WebExtensions.CD9358CE.md) | Returns all my site site collections
| [SiteSearch(Web)](Microsoft.SharePoint.Client.WebExtensions.96462F9D.md) | Returns all site collections that are indexed. In MT the search center, mysite host and contenttype hub are defined as non indexable by default and thus are not returned
| [SiteSearch(Web, String, Boolean)](Microsoft.SharePoint.Client.WebExtensions.FDAF2CE0.md) | Returns the site collections that comply with the passed keyword query
| [SiteSearchScopedByUrl(Web, String)](Microsoft.SharePoint.Client.WebExtensions.2AA306D6.md) | Returns all site collection that start with the provided URL
| [SiteSearchScopedByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.9FFF44D9.md) | Returns all site collection that match with the provided title
| [ProcessQuery(Web, String, List<SiteEntity>, KeywordQuery)](Microsoft.SharePoint.Client.WebExtensions.33850AF4.md) | 
| [SetPropertyBagValue(Web, String, Int32)](Microsoft.SharePoint.Client.WebExtensions.62C0B9DA.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, String)](Microsoft.SharePoint.Client.WebExtensions.E498740A.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, DateTime)](Microsoft.SharePoint.Client.WebExtensions.C46C00D1.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValueInternal(Web, String, Object)](Microsoft.SharePoint.Client.WebExtensions.D566B06D.md) | Sets a key/value pair in the web property bag
| [RemovePropertyBagValue(Web, String)](Microsoft.SharePoint.Client.WebExtensions.7EBF8D0F.md) | Removes a property bag value from the property bag
| [RemovePropertyBagValueInternal(Web, String, Boolean)](Microsoft.SharePoint.Client.WebExtensions.FEF68470.md) | Removes a property bag value
| [GetPropertyBagValueInt(Web, String, Int32)](Microsoft.SharePoint.Client.WebExtensions.FB0E8960.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueDateTime(Web, String, DateTime)](Microsoft.SharePoint.Client.WebExtensions.FDFEBC13.md) | Get DateTime typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(Web, String, String)](Microsoft.SharePoint.Client.WebExtensions.4427B00A.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(Web, String)](Microsoft.SharePoint.Client.WebExtensions.7C8AB456.md) | Type independent implementation of the property getter.
| [PropertyBagContainsKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.7A7AE50C.md) | Checks if the given property bag entry exists
| [GetEncodedValueForSearchIndexProperty(IEnumerable<String>)](Microsoft.SharePoint.Client.WebExtensions.5215102.md) | 
| [GetIndexedPropertyBagKeys(Web)](Microsoft.SharePoint.Client.WebExtensions.FC2A9547.md) | Returns all keys in the property bag that have been marked for indexing
| [AddIndexedPropertyBagKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.1E21757A.md) | Marks a property bag key for indexing
| [RemoveIndexedPropertyBagKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.D4650EF6.md) | Unmarks a property bag key for indexing
| [ReIndexWeb(Web)](Microsoft.SharePoint.Client.WebExtensions.3FC076F8.md) | Queues a web for a full crawl the next incremental/continous crawl
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](Microsoft.SharePoint.Client.WebExtensions.E1C51DCB.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](Microsoft.SharePoint.Client.WebExtensions.4C2AF14E.md) | Registers a remote event receiver
| [GetEventReceiverById(Web, Guid)](Microsoft.SharePoint.Client.WebExtensions.A2BBB95B.md) | Returns an event receiver definition
| [GetEventReceiverByName(Web, String)](Microsoft.SharePoint.Client.WebExtensions.F3860FDA.md) | Returns an event receiver definition
| [SetLocalizationLabels(Web, String, String, String)](Microsoft.SharePoint.Client.WebExtensions.4FC70325.md) | Can be used to set translations for different cultures.
| [ApplyProvisioningTemplate(Web, ProvisioningTemplate, ProvisioningTemplateApplyingInformation)](Microsoft.SharePoint.Client.WebExtensions.5FDC38CC.md) | Can be used to apply custom remote provisioning template on top of existing site.
| [GetProvisioningTemplate(Web)](Microsoft.SharePoint.Client.WebExtensions.58235816.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [GetProvisioningTemplate(Web, ProvisioningTemplateCreationInformation)](Microsoft.SharePoint.Client.WebExtensions.8E22F686.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [SetPageOutputCache(Web, Boolean, Int32, Int32, Boolean)](Microsoft.SharePoint.Client.WebExtensions.6F3DDC09.md) | Sets output cache on publishing web. The settings can be maintained from UI by visiting url /_layouts/15/sitecachesettings.aspx
| [DisableRequestAccess(Web)](Microsoft.SharePoint.Client.WebExtensions.1FEC6F8D.md) | Disables the request access on the web.
| [EnableRequestAccess(Web, String[])](Microsoft.SharePoint.Client.WebExtensions.A6AEB360.md) | Enables request access for the specified e-mail addresses.
| [EnableRequestAccess(Web, IEnumerable<String>)](Microsoft.SharePoint.Client.WebExtensions.EFAF0293.md) | 
| [GetRequestAccessEmails(Web)](Microsoft.SharePoint.Client.WebExtensions.E3474AC6.md) | Gets the request access e-mail addresses of the web.
## Examples
```C#
 web.SetLocalizationForSiteLabels("fi-fi", "Name of the site in Finnish", "Description in Finnish"); 
```
## See also
- [http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx](http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
