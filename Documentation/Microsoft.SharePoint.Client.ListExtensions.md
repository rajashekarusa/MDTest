# ListExtensions
Class that holds deprecated generic list creation and manipulation methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class ListExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](Microsoft.SharePoint.Client.ListExtensions.AddRemoteEventReceiverListStringStringEventReceiverTypeEventReceiverSynchronizationBoolean.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](Microsoft.SharePoint.Client.ListExtensions.AddRemoteEventReceiverListStringStringEventReceiverTypeEventReceiverSynchronizationInt32Boolean.md) | Registers a remote event receiver
| [GetEventReceiverById(List, Guid)](Microsoft.SharePoint.Client.ListExtensions.GetEventReceiverByIdListGuid.md) | Returns an event receiver definition
| [GetEventReceiverByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.GetEventReceiverByNameListString.md) | Returns an event receiver definition
| [SetPropertyBagValue(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.SetPropertyBagValueListStringInt32.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.SetPropertyBagValueListStringString.md) | Sets a key/value pair in the list property bag
| [SetPropertyBagValueInternal(List, String, Object)](Microsoft.SharePoint.Client.ListExtensions.SetPropertyBagValueInternalListStringObject.md) | Sets a key/value pair in the list property bag
| [GetPropertyBagValueInt(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.GetPropertyBagValueIntListStringInt32.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.GetPropertyBagValueStringListStringString.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(List, String)](Microsoft.SharePoint.Client.ListExtensions.GetPropertyBagValueInternalListString.md) | Type independent implementation of the property gettter.
| [PropertyBagContainsKey(List, String)](Microsoft.SharePoint.Client.ListExtensions.PropertyBagContainsKeyListString.md) | Checks if the given property bag entry exists
| [RemoveContentTypeByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.RemoveContentTypeByNameListString.md) | Removes a content type from a list/library by name
| [CreateDocumentLibrary(Web, String, Boolean, String)](Microsoft.SharePoint.Client.ListExtensions.CreateDocumentLibraryWebStringBooleanString.md) | Adds a document library to a web. Execute Query is called during this implementation
| [ListExists(Web, String)](Microsoft.SharePoint.Client.ListExtensions.ListExistsWebString.md) | Checks if list exists on the particular site based on the list Title property.
| [ListExists(Web, Uri)](Microsoft.SharePoint.Client.ListExtensions.ListExistsWebUri.md) | Checks if list exists on the particular site based on the list's site relative path.
| [ListExists(Web, Guid)](Microsoft.SharePoint.Client.ListExtensions.ListExistsWebGuid.md) | Checks if list exists on the particular site based on the list id property.
| [CreateList(Web, ListTemplateType, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.CreateListWebListTemplateTypeStringBooleanBooleanStringBoolean.md) | Adds a default list to a site
| [CreateList(Web, Guid, Int32, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.CreateListWebGuidInt32StringBooleanBooleanStringBoolean.md) | Adds a custom list to a site
| [CreateListInternal(Web, Nullable<Guid>, Int32, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.CreateListInternalWebNullable<Guid>Int32StringBooleanBooleanStringBoolean.md) | 
| [UpdateListVersioning(Web, String, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.UpdateListVersioningWebStringBooleanBooleanBoolean.md) | Enable/disable versioning on a list
| [UpdateListVersioning(List, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.UpdateListVersioningListBooleanBooleanBoolean.md) | Enable/disable versioning on a list
| [UpdateTaxonomyFieldDefaultValue(Web, String, String, String, Guid, Guid)](Microsoft.SharePoint.Client.ListExtensions.UpdateTaxonomyFieldDefaultValueWebStringStringStringGuidGuid.md) | Sets the default value for a managed metadata column in the specified list. This operation will not change existing items in the list
| [SetJSLinkCustomizations(List, PageType, String)](Microsoft.SharePoint.Client.ListExtensions.SetJSLinkCustomizationsListPageTypeString.md) | Sets JS link customization for a list form
| [SetJSLinkCustomizations(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.SetJSLinkCustomizationsListStringString.md) | Sets JS link customization for a list view page
| [SetJSLinkCustomizationsImplementation(List, File, String)](Microsoft.SharePoint.Client.ListExtensions.SetJSLinkCustomizationsImplementationListFileString.md) | 
| [SetLocalizationLabelsForList(Web, String, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.SetLocalizationLabelsForListWebStringStringStringString.md) | 
| [SetLocalizationLabelsForList(List, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.SetLocalizationLabelsForListListStringStringString.md) | Can be used to set translations for different cultures.
| [GetListID(Web, String)](Microsoft.SharePoint.Client.ListExtensions.GetListIDWebString.md) | Returns the GUID id of a list
| [GetListByTitle(Web, String, Linq.Expressions.Expression<Func<List,Object>>[])](Microsoft.SharePoint.Client.ListExtensions.GetListByTitleWebStringLinq.Expressions.Expression<Func<List,Object>>[].md) | 
| [GetListByUrl(Web, String, Linq.Expressions.Expression<Func<List,Object>>[])](Microsoft.SharePoint.Client.ListExtensions.GetListByUrlWebStringLinq.Expressions.Expression<Func<List,Object>>[].md) | 
| [GetPagesLibrary(Web)](Microsoft.SharePoint.Client.ListExtensions.GetPagesLibraryWeb.md) | Gets the publishing pages library of the web based on site language
| [GetWebRelativeUrl(List)](Microsoft.SharePoint.Client.ListExtensions.GetWebRelativeUrlList.md) | Gets the web relative URL. Allow users to get the web relative URL of a list. This is useful when exporting lists as it can then be used as a parameter to Web.GetListByUrl().
| [GetWebRelativeUrl(String, String)](Microsoft.SharePoint.Client.ListExtensions.GetWebRelativeUrlStringString.md) | Gets the web relative URL.
| [SetListPermission(List, OfficeDevPnP.Core.Enums.BuiltInIdentity, RoleType)](Microsoft.SharePoint.Client.ListExtensions.SetListPermissionListOfficeDevPnP.Core.Enums.BuiltInIdentityRoleType.md) | Set custom permission to the list
| [SetListPermission(List, Principal, RoleType)](Microsoft.SharePoint.Client.ListExtensions.SetListPermissionListPrincipalRoleType.md) | Set custom permission to the list
| [CreateViewsFromXMLFile(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLFileWebStringString.md) | Creates list views based on specific xml structure from file
| [CreateViewsFromXMLString(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLStringWebStringString.md) | Creates views based on specific xml structure from string
| [CreateViewsFromXML(Web, String, Xml.XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLWebStringXml.XmlDocument.md) | Create list views based on xml structure loaded to memory
| [CreateViewsFromXMLFile(List, String)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLFileListString.md) | Create list views based on specific xml structure in external file
| [CreateViewsFromXMLString(List, String)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLStringListString.md) | Create list views based on specific xml structure in string
| [CreateViewsFromXML(List, Xml.XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.CreateViewsFromXMLListXml.XmlDocument.md) | Actual implementation of the view creation logic based on given xml
| [CreateView(List, String, ViewType, String[], UInt32, Boolean, String, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.CreateViewListStringViewTypeString[]UInt32BooleanStringBooleanBoolean.md) | Create view to existing list
| [GetViewById(List, Guid, Linq.Expressions.Expression<Func<View,Object>>[])](Microsoft.SharePoint.Client.ListExtensions.GetViewByIdListGuidLinq.Expressions.Expression<Func<View,Object>>[].md) | 
| [GetViewByName(List, String, Linq.Expressions.Expression<Func<View,Object>>[])](Microsoft.SharePoint.Client.ListExtensions.GetViewByNameListStringLinq.Expressions.Expression<Func<View,Object>>[].md) | 
| [SetDefaultColumnValuesImplementation(List, Collections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.IDefaultColumnValue>)](Microsoft.SharePoint.Client.ListExtensions.SetDefaultColumnValuesImplementationListCollections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.IDefaultColumnValue>.md) | 
| [SetDefaultColumnValues(List, Collections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.IDefaultColumnValue>)](Microsoft.SharePoint.Client.ListExtensions.SetDefaultColumnValuesListCollections.Generic.IEnumerable<OfficeDevPnP.Core.Entities.IDefaultColumnValue>.md) | 
| [GetDefaultColumnValues(List)](Microsoft.SharePoint.Client.ListExtensions.GetDefaultColumnValuesList.md) | 
| [ReIndexList(List)](Microsoft.SharePoint.Client.ListExtensions.ReIndexListList.md) | Queues a list for a full crawl the next incremental crawl
## Examples
```C#
 list.SetLocalizationForSiteLabels("fi-fi", "Name of the site in Finnish", "Description in Finnish"); 
```
## See also
- [http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx](http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
