# WebExtensions
Class that holds deprecated methods for site (both site collection and web site) creation, status, retrieval and settings
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class WebExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetBaseTemplateId(Web)](WebExtensionsGetBaseTemplateIdWeb.md) | Returns the Base Template ID for the current web
| [CreateWeb(Web, OfficeDevPnP.Core.Entities.SiteEntity, Boolean, Boolean)](WebExtensionsCreateWebWebOfficeDevPnP.Core.Entities.SiteEntityBooleanBoolean.md) | Adds a new child Web (site) to a parent Web.
| [CreateWeb(Web, String, String, String, String, Int32, Boolean, Boolean)](WebExtensionsCreateWebWebStringStringStringStringInt32BooleanBoolean.md) | Adds a new child Web (site) to a parent Web.
| [DeleteWeb(Web, String)](WebExtensionsDeleteWebWebString.md) | Deletes the child website with the specified leaf URL, from a parent Web, if it exists.
| [GetAllWebUrls(Site)](WebExtensionsGetAllWebUrlsSite.md) | Gets the collection of the URLs of all Web sites that are contained within the site collection, including the top-level site and its subsites.
| [GetWeb(Web, String)](WebExtensionsGetWebWebString.md) | Returns the child Web site with the specified leaf URL.
| [WebExists(Web, String)](WebExtensionsWebExistsWebString.md) | Determines if a child Web site with the specified leaf URL exists.
| [WebExistsFullUrl(ClientRuntimeContext, String)](WebExtensionsWebExistsFullUrlClientRuntimeContextString.md) | Determines if a Web (site) exists at the specified full URL, either accessible or that returns an access error.
| [WebExistsByTitle(Web, String)](WebExtensionsWebExistsByTitleWebString.md) | Determines if a web exists by title.
| [IsSubSite(Web)](WebExtensionsIsSubSiteWeb.md) | Checks if the current web is a sub site or not
| [IsPublishingWeb(Web)](WebExtensionsIsPublishingWebWeb.md) | 
| [IsNoScriptSite(Site)](WebExtensionsIsNoScriptSiteSite.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsNoScriptSite(Web)](WebExtensionsIsNoScriptSiteWeb.md) | Detects if the site in question has no script enabled or not. Detection is done by verifying if the AddAndCustomizePages permission is missing. See https://support.office.com/en-us/article/Turn-scripting-capabilities-on-or-off-1f2c515f-5d7e-448a-9fd7-835da935584f for the effects of NoScript
| [IsCannotGetSiteException(Exception)](WebExtensionsIsCannotGetSiteExceptionException.md) | 
| [IsUnableToAccessSiteException(Exception)](WebExtensionsIsUnableToAccessSiteExceptionException.md) | 
| [GetAppInstances(Web, Linq.Expressions.Expression1<Func2<AppInstance,Object>>[])](WebExtensionsGetAppInstancesWebLinq.Expressions.Expression1<Func2<AppInstance,Object>>[].md) | 
| [RemoveAppInstanceByTitle(Web, String)](WebExtensionsRemoveAppInstanceByTitleWebString.md) | Removes the app instance with the specified title.
| [InstallSolution(Site, Guid, String, Int32, Int32)](WebExtensionsInstallSolutionSiteGuidStringInt32Int32.md) | Uploads and installs a sandbox solution package (.WSP) file, replacing existing solution if necessary.
| [UninstallSolution(Site, Guid, String, Int32, Int32)](WebExtensionsUninstallSolutionSiteGuidStringInt32Int32.md) | Uninstalls a sandbox solution package (.WSP) file
| [MySiteSearch(Web)](WebExtensionsMySiteSearchWeb.md) | Returns all my site site collections
| [SiteSearch(Web)](WebExtensionsSiteSearchWeb.md) | Returns all site collections that are indexed. In MT the search center, mysite host and contenttype hub are defined as non indexable by default and thus are not returned
| [SiteSearch(Web, String, Boolean)](WebExtensionsSiteSearchWebStringBoolean.md) | Returns the site collections that comply with the passed keyword query
| [SiteSearchScopedByUrl(Web, String)](WebExtensionsSiteSearchScopedByUrlWebString.md) | Returns all site collection that start with the provided URL
| [SiteSearchScopedByTitle(Web, String)](WebExtensionsSiteSearchScopedByTitleWebString.md) | Returns all site collection that match with the provided title
| [ProcessQuery(Web, String, Collections.Generic.List1<OfficeDevPnP.Core.Entities.SiteEntity>, Search.Query.KeywordQuery)](WebExtensionsProcessQueryWebStringCollections.Generic.List1<OfficeDevPnP.Core.Entities.SiteEntity>Search.Query.KeywordQuery.md) | 
| [SetPropertyBagValue(Web, String, Int32)](WebExtensionsSetPropertyBagValueWebStringInt32.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, String)](WebExtensionsSetPropertyBagValueWebStringString.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(Web, String, DateTime)](WebExtensionsSetPropertyBagValueWebStringDateTime.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValueInternal(Web, String, Object)](WebExtensionsSetPropertyBagValueInternalWebStringObject.md) | Sets a key/value pair in the web property bag
| [RemovePropertyBagValue(Web, String)](WebExtensionsRemovePropertyBagValueWebString.md) | Removes a property bag value from the property bag
| [RemovePropertyBagValueInternal(Web, String, Boolean)](WebExtensionsRemovePropertyBagValueInternalWebStringBoolean.md) | Removes a property bag value
| [GetPropertyBagValueInt(Web, String, Int32)](WebExtensionsGetPropertyBagValueIntWebStringInt32.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueDateTime(Web, String, DateTime)](WebExtensionsGetPropertyBagValueDateTimeWebStringDateTime.md) | Get DateTime typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(Web, String, String)](WebExtensionsGetPropertyBagValueStringWebStringString.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(Web, String)](WebExtensionsGetPropertyBagValueInternalWebString.md) | Type independent implementation of the property getter.
| [PropertyBagContainsKey(Web, String)](WebExtensionsPropertyBagContainsKeyWebString.md) | Checks if the given property bag entry exists
| [GetEncodedValueForSearchIndexProperty(Collections.Generic.IEnumerable1<String>)](WebExtensionsGetEncodedValueForSearchIndexPropertyCollections.Generic.IEnumerable1<String>.md) | 
| [GetIndexedPropertyBagKeys(Web)](WebExtensionsGetIndexedPropertyBagKeysWeb.md) | Returns all keys in the property bag that have been marked for indexing
| [AddIndexedPropertyBagKey(Web, String)](WebExtensionsAddIndexedPropertyBagKeyWebString.md) | Marks a property bag key for indexing
| [RemoveIndexedPropertyBagKey(Web, String)](WebExtensionsRemoveIndexedPropertyBagKeyWebString.md) | Unmarks a property bag key for indexing
| [ReIndexWeb(Web)](WebExtensionsReIndexWebWeb.md) | Queues a web for a full crawl the next incremental/continous crawl
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](WebExtensionsAddRemoteEventReceiverWebStringStringEventReceiverTypeEventReceiverSynchronizationBoolean.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(Web, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](WebExtensionsAddRemoteEventReceiverWebStringStringEventReceiverTypeEventReceiverSynchronizationInt32Boolean.md) | Registers a remote event receiver
| [GetEventReceiverById(Web, Guid)](WebExtensionsGetEventReceiverByIdWebGuid.md) | Returns an event receiver definition
| [GetEventReceiverByName(Web, String)](WebExtensionsGetEventReceiverByNameWebString.md) | Returns an event receiver definition
| [SetLocalizationLabels(Web, String, String, String)](WebExtensionsSetLocalizationLabelsWebStringStringString.md) | Can be used to set translations for different cultures.
| [ApplyProvisioningTemplate(Web, OfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplate, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation)](WebExtensionsApplyProvisioningTemplateWebOfficeDevPnP.Core.Framework.Provisioning.Model.ProvisioningTemplateOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateApplyingInformation.md) | Can be used to apply custom remote provisioning template on top of existing site.
| [GetProvisioningTemplate(Web)](WebExtensionsGetProvisioningTemplateWeb.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [GetProvisioningTemplate(Web, OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation)](WebExtensionsGetProvisioningTemplateWebOfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.ProvisioningTemplateCreationInformation.md) | Can be used to extract custom provisioning template from existing site. The extracted template will be compared with the default base template.
| [SetPageOutputCache(Web, Boolean, Int32, Int32, Boolean)](WebExtensionsSetPageOutputCacheWebBooleanInt32Int32Boolean.md) | Sets output cache on publishing web. The settings can be maintained from UI by visiting url /_layouts/15/sitecachesettings.aspx
| [DisableRequestAccess(Web)](WebExtensionsDisableRequestAccessWeb.md) | Disables the request access on the web.
| [EnableRequestAccess(Web, String[])](WebExtensionsEnableRequestAccessWebString[].md) | Enables request access for the specified e-mail addresses.
| [EnableRequestAccess(Web, Collections.Generic.IEnumerable1<String>)](WebExtensionsEnableRequestAccessWebCollections.Generic.IEnumerable1<String>.md) | 
| [GetRequestAccessEmails(Web)](WebExtensionsGetRequestAccessEmailsWeb.md) | Gets the request access e-mail addresses of the web.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
