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
| [GetBaseTemplateId(Web)](Microsoft.SharePoint.Client.WebExtensions.GetBaseTemplateIdWeb.md) | Returns the Base Template ID for the current web
| [CreateWeb(Web, OfficeDevPnP.Core.Entities.SiteEntity, Boolean, Boolean)](Microsoft.SharePoint.Client.WebExtensions.CreateWebWebOfficeDevPnP.Core.Entities.SiteEntityBooleanBoolean.md) | Adds a new child Web (site) to a parent Web.
| [CreateWeb(Web, String, String, String, String, Int32, Boolean, Boolean)](Microsoft.SharePoint.Client.WebExtensions.CreateWebWebStringStringStringStringInt32BooleanBoolean.md) | Adds a new child Web (site) to a parent Web.
| [DeleteWeb(Web, String)](Microsoft.SharePoint.Client.WebExtensions.DeleteWebWebString.md) | Deletes the child website with the specified leaf URL, from a parent Web, if it exists.
| [GetAllWebUrls(Site)](Microsoft.SharePoint.Client.WebExtensions.GetAllWebUrlsSite.md) | Gets the collection of the URLs of all Web sites that are contained within the site collection, including the top-level site and its subsites.
| [GetWeb(Web, String)](Microsoft.SharePoint.Client.WebExtensions.GetWebWebString.md) | Returns the child Web site with the specified leaf URL.
| [WebExists(Web, String)](Microsoft.SharePoint.Client.WebExtensions.WebExistsWebString.md) | Determines if a child Web site with the specified leaf URL exists.
| [WebExistsFullUrl(ClientRuntimeContext, String)](Microsoft.SharePoint.Client.WebExtensions.WebExistsFullUrlClientRuntimeContextString.md) | Determines if a Web (site) exists at the specified full URL, either accessible or that returns an access error.
| [WebExistsByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.WebExistsByTitleWebString.md) | Determines if a web exists by title.
| [IsSubSite(Web)](Microsoft.SharePoint.Client.WebExtensions.IsSubSiteWeb.md) | Checks if the current web is a sub site or not
| [IsPublishingWeb(Web)](Microsoft.SharePoint.Client.WebExtensions.IsPublishingWebWeb.md) | 
| [IsNoScriptSite(Site)](Microsoft.SharePoint.Client.WebExtensions.IsNoScriptSiteSite.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsNoScriptSite(Web)](Microsoft.SharePoint.Client.WebExtensions.IsNoScriptSiteWeb.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsCannotGetSiteException(Exception)](Microsoft.SharePoint.Client.WebExtensions.IsCannotGetSiteExceptionException.md) | 
| [IsUnableToAccessSiteException(Exception)](Microsoft.SharePoint.Client.WebExtensions.IsUnableToAccessSiteExceptionException.md) | 
| [GetAppInstances(Web, Linq.Expressions.Expression<Func<AppInstance,Object>>[])](Microsoft.SharePoint.Client.WebExtensions.GetAppInstancesWebLinq.Expressions.Expression<Func<AppInstance,Object>>[].md) | 
| [RemoveAppInstanceByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.RemoveAppInstanceByTitleWebString.md) | Removes the app instance with the specified title.
| [InstallSolution(Site, Guid, String, Int32, Int32)](Microsoft.SharePoint.Client.WebExtensions.InstallSolutionSiteGuidStringInt32Int32.md) | Uploads and installs a sandbox solution package (.WSP) file, replacing existing solution if necessary.
| [UninstallSolution(Site, Guid, String, Int32, Int32)](Microsoft.SharePoint.Client.WebExtensions.UninstallSolutionSiteGuidStringInt32Int32.md) | Uninstalls a sandbox solution package (.WSP) file
| [MySiteSearch(Web)](Microsoft.SharePoint.Client.WebExtensions.MySiteSearchWeb.md) | Returns all my site site collections
| [SiteSearch(Web)](Microsoft.SharePoint.Client.WebExtensions.SiteSearchWeb.md) | Returns all site collections that are indexed. In MT the search center, mysite host and contenttype hub are defined as non indexable by default and thus are not returned
| [SiteSearch(Web, String, Boolean)](Microsoft.SharePoint.Client.WebExtensions.SiteSearchWebStringBoolean.md) | Returns the site collections that comply with the passed keyword query
| [SiteSearchScopedByUrl(Web, String)](Microsoft.SharePoint.Client.WebExtensions.SiteSearchScopedByUrlWebString.md) | Returns all site collection that start with the provided URL
| [SiteSearchScopedByTitle(Web, String)](Microsoft.SharePoint.Client.WebExtensions.SiteSearchScopedByTitleWebString.md) | Returns all site collection that match with the provided title
| [ProcessQuery(Web, String, Collections.Generic.List<OfficeDevPnP.Core.Entities.SiteEntity>, Search.Query.KeywordQuery)](Microsoft.SharePoint.Client.WebExtensions.ProcessQueryWebStringCollections.Generic.List<OfficeDevPnP.Core.Entities.SiteEntity>Search.Query.KeywordQuery.md) | 
| [SetPropertyBagValue(Web, String, Int32)](Microsoft.SharePoint.Client.WebExtensions.SetPropertyBagValueWebStringInt32.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, String)](Microsoft.SharePoint.Client.WebExtensions.SetPropertyBagValueWebStringString.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, DateTime)](Microsoft.SharePoint.Client.WebExtensions.SetPropertyBagValueWebStringDateTime.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValueInternal(Web, String, Object)](Microsoft.SharePoint.Client.WebExtensions.SetPropertyBagValueInternalWebStringObject.md) | Sets a key/value pair in the web property bag
| [RemovePropertyBagValue(Web, String)](Microsoft.SharePoint.Client.WebExtensions.RemovePropertyBagValueWebString.md) | Removes a property bag value from the property bag
| [RemovePropertyBagValueInternal(Web, String, Boolean)](Microsoft.SharePoint.Client.WebExtensions.RemovePropertyBagValueInternalWebStringBoolean.md) | Removes a property bag value
| [GetPropertyBagValueInt(Web, String, Int32)](Microsoft.SharePoint.Client.WebExtensions.GetPropertyBagValueIntWebStringInt32.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueDateTime(Web, String, DateTime)](Microsoft.SharePoint.Client.WebExtensions.GetPropertyBagValueDateTimeWebStringDateTime.md) | Get DateTime typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(Web, String, String)](Microsoft.SharePoint.Client.WebExtensions.GetPropertyBagValueStringWebStringString.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(Web, String)](Microsoft.SharePoint.Client.WebExtensions.GetPropertyBagValueInternalWebString.md) | Type independent implementation of the property getter.
| [PropertyBagContainsKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.PropertyBagContainsKeyWebString.md) | Checks if the given property bag entry exists
| [GetEncodedValueForSearchIndexProperty(Collections.Generic.IEnumerable<String>)](Microsoft.SharePoint.Client.WebExtensions.GetEncodedValueForSearchIndexPropertyCollections.Generic.IEnumerable<String>.md) | 
| [GetIndexedPropertyBagKeys(Web)](Microsoft.SharePoint.Client.WebExtensions.GetIndexedPropertyBagKeysWeb.md) | Returns all keys in the property bag that have been marked for indexing
| [AddIndexedPropertyBagKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.AddIndexedPropertyBagKeyWebString.md) | Marks a property bag key for indexing
| [RemoveIndexedPropertyBagKey(Web, String)](Microsoft.SharePoint.Client.WebExtensions.RemoveIndexedPropertyBagKeyWebString.md) | Unmarks a property bag key for indexing
| [ReIndexWeb(Web)](Microsoft.SharePoint.Client.WebExtensions.ReIndexWebWeb.md) | Queues a web for a full crawl the next incremental/continous crawl
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](Microsoft.SharePoint.Client.WebExtensions.AddRemoteEventReceiverWebStringStringEventReceiverTypeEventReceiverSynchronizationBoolean.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](Microsoft.SharePoint.Client.WebExtensions.AddRemoteEventReceiverWebStringStringEventReceiverTypeEventReceiverSynchronizationInt32Boolean.md) | Registers a remote event receiver
| [GetEventReceiverById(Web, Guid)](Microsoft.SharePoint.Client.WebExtensions.GetEventReceiverByIdWebGuid.md) | Returns an event receiver definition
| [GetEventReceiverByName(Web, String)](Microsoft.SharePoint.Client.WebExtensions.GetEventReceiverByNameWebString.md) | Returns an event receiver definition
| [SetLocalizationLabels(Web, String, String, String)](Microsoft.SharePoint.Client.WebExtensions.SetLocalizationLabelsWebStringStringString.md) | Can be used to set translations for different cultures.
| [ApplyProvisioningTemplate(Web, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation)](Microsoft.SharePoint.Client.WebExtensions.ApplyProvisioningTemplateWebOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.md) | Can be used to apply custom remote provisioning template on top of existing site.
| [GetProvisioningTemplate(Web)](Microsoft.SharePoint.Client.WebExtensions.GetProvisioningTemplateWeb.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [GetProvisioningTemplate(Web, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation)](Microsoft.SharePoint.Client.WebExtensions.GetProvisioningTemplateWebOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [SetPageOutputCache(Web, Boolean, Int32, Int32, Boolean)](Microsoft.SharePoint.Client.WebExtensions.SetPageOutputCacheWebBooleanInt32Int32Boolean.md) | Sets output cache on publishing web. The settings can be maintained from UI by visiting url /_layouts/15/sitecachesettings.aspx
| [DisableRequestAccess(Web)](Microsoft.SharePoint.Client.WebExtensions.DisableRequestAccessWeb.md) | Disables the request access on the web.
| [EnableRequestAccess(Web, String[])](Microsoft.SharePoint.Client.WebExtensions.EnableRequestAccessWebString[].md) | Enables request access for the specified e-mail addresses.
| [EnableRequestAccess(Web, Collections.Generic.IEnumerable<String>)](Microsoft.SharePoint.Client.WebExtensions.EnableRequestAccessWebCollections.Generic.IEnumerable<String>.md) | 
| [GetRequestAccessEmails(Web)](Microsoft.SharePoint.Client.WebExtensions.GetRequestAccessEmailsWeb.md) | Gets the request access e-mail addresses of the web.
## Examples
```C#
 web.SetLocalizationForSiteLabels("fi-fi", "Name of the site in Finnish", "Description in Finnish"); 
```
## See also
- [http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx](http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
