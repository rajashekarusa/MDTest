# ListExtensions
Class that holds deprecated generic list creation and manipulation methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class ListExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](ListExtensionsAddRemoteEventReceiverListStringStringEventReceiverTypeEventReceiverSynchronizationBoolean.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](ListExtensionsAddRemoteEventReceiverListStringStringEventReceiverTypeEventReceiverSynchronizationInt32Boolean.md) | Registers a remote event receiver
| [GetEventReceiverById(List, Guid)](ListExtensionsGetEventReceiverByIdListGuid.md) | Returns an event receiver definition
| [GetEventReceiverByName(List, String)](ListExtensionsGetEventReceiverByNameListString.md) | Returns an event receiver definition
| [SetPropertyBagValue(List, String, Int32)](ListExtensionsSetPropertyBagValueListStringInt32.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(List, String, String)](ListExtensionsSetPropertyBagValueListStringString.md) | Sets a key/value pair in the list property bag
| [SetPropertyBagValueInternal(List, String, Object)](ListExtensionsSetPropertyBagValueInternalListStringObject.md) | Sets a key/value pair in the list property bag
| [GetPropertyBagValueInt(List, String, Int32)](ListExtensionsGetPropertyBagValueIntListStringInt32.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(List, String, String)](ListExtensionsGetPropertyBagValueStringListStringString.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(List, String)](ListExtensionsGetPropertyBagValueInternalListString.md) | Type independent implementation of the property gettter.
| [PropertyBagContainsKey(List, String)](ListExtensionsPropertyBagContainsKeyListString.md) | Checks if the given property bag entry exists
| [RemoveContentTypeByName(List, String)](ListExtensionsRemoveContentTypeByNameListString.md) | Removes a content type from a list/library by name
| [CreateDocumentLibrary(Web, String, Boolean, String)](ListExtensionsCreateDocumentLibraryWebStringBooleanString.md) | Adds a document library to a web. Execute Query is called during this implementation
| [ListExists(Web, String)](ListExtensionsListExistsWebString.md) | Checks if list exists on the particular site based on the list Title property.
| [ListExists(Web, Uri)](ListExtensionsListExistsWebUri.md) | Checks if list exists on the particular site based on the list's site relative path.
| [ListExists(Web, Guid)](ListExtensionsListExistsWebGuid.md) | Checks if list exists on the particular site based on the list id property.
| [CreateList(Web, ListTemplateType, String, Boolean, Boolean, String, Boolean)](ListExtensionsCreateListWebListTemplateTypeStringBooleanBooleanStringBoolean.md) | Adds a default list to a site
| [CreateList(Web, Guid, Int32, String, Boolean, Boolean, String, Boolean)](ListExtensionsCreateListWebGuidInt32StringBooleanBooleanStringBoolean.md) | Adds a custom list to a site
| [CreateListInternal(Web, Nullable1<Guid>, Int32, String, Boolean, Boolean, String, Boolean)](ListExtensionsCreateListInternalWebNullable1<Guid>Int32StringBooleanBooleanStringBoolean.md) | 
| [UpdateListVersioning(Web, String, Boolean, Boolean, Boolean)](ListExtensionsUpdateListVersioningWebStringBooleanBooleanBoolean.md) | Enable/disable versioning on a list
| [UpdateListVersioning(List, Boolean, Boolean, Boolean)](ListExtensionsUpdateListVersioningListBooleanBooleanBoolean.md) | Enable/disable versioning on a list
| [UpdateTaxonomyFieldDefaultValue(Web, String, String, String, Guid, Guid)](ListExtensionsUpdateTaxonomyFieldDefaultValueWebStringStringStringGuidGuid.md) | Sets the default value for a managed metadata column in the specified list. This operation will not change existing items in the list
| [SetJSLinkCustomizations(List, PageType, String)](ListExtensionsSetJSLinkCustomizationsListPageTypeString.md) | Sets JS link customization for a list form
| [SetJSLinkCustomizations(List, String, String)](ListExtensionsSetJSLinkCustomizationsListStringString.md) | Sets JS link customization for a list view page
| [SetJSLinkCustomizationsImplementation(List, File, String)](ListExtensionsSetJSLinkCustomizationsImplementationListFileString.md) | 
| [SetLocalizationLabelsForList(Web, String, String, String, String)](ListExtensionsSetLocalizationLabelsForListWebStringStringStringString.md) | 
| [SetLocalizationLabelsForList(List, String, String, String)](ListExtensionsSetLocalizationLabelsForListListStringStringString.md) | Can be used to set translations for different cultures.
| [GetListID(Web, String)](ListExtensionsGetListIDWebString.md) | Returns the GUID id of a list
| [GetListByTitle(Web, String, Linq.Expressions.Expression1<Func2<List,Object>>[])](ListExtensionsGetListByTitleWebStringLinq.Expressions.Expression1<Func2<List,Object>>[].md) | 
| [GetListByUrl(Web, String, Linq.Expressions.Expression1<Func2<List,Object>>[])](ListExtensionsGetListByUrlWebStringLinq.Expressions.Expression1<Func2<List,Object>>[].md) | 
| [GetPagesLibrary(Web)](ListExtensionsGetPagesLibraryWeb.md) | Gets the publishing pages library of the web based on site language
| [GetWebRelativeUrl(List)](ListExtensionsGetWebRelativeUrlList.md) | Gets the web relative URL. Allow users to get the web relative URL of a list. This is useful when exporting lists as it can then be used as a parameter to Web.GetListByUrl().
| [GetWebRelativeUrl(String, String)](ListExtensionsGetWebRelativeUrlStringString.md) | Gets the web relative URL.
| [SetListPermission(List, OfficeDevPnP.Core.Enums.BuiltInIdentity, RoleType)](ListExtensionsSetListPermissionListOfficeDevPnP.Core.Enums.BuiltInIdentityRoleType.md) | Set custom permission to the list
| [SetListPermission(List, Principal, RoleType)](ListExtensionsSetListPermissionListPrincipalRoleType.md) | Set custom permission to the list
| [CreateViewsFromXMLFile(Web, String, String)](ListExtensionsCreateViewsFromXMLFileWebStringString.md) | Creates list views based on specific xml structure from file
| [CreateViewsFromXMLString(Web, String, String)](ListExtensionsCreateViewsFromXMLStringWebStringString.md) | Creates views based on specific xml structure from string
| [CreateViewsFromXML(Web, String, Xml.XmlDocument)](ListExtensionsCreateViewsFromXMLWebStringXml.XmlDocument.md) | Create list views based on xml structure loaded to memory
| [CreateViewsFromXMLFile(List, String)](ListExtensionsCreateViewsFromXMLFileListString.md) | Create list views based on specific xml structure in external file
| [CreateViewsFromXMLString(List, String)](ListExtensionsCreateViewsFromXMLStringListString.md) | Create list views based on specific xml structure in string
| [CreateViewsFromXML(List, Xml.XmlDocument)](ListExtensionsCreateViewsFromXMLListXml.XmlDocument.md) | Actual implementation of the view creation logic based on given xml
| [CreateView(List, String, ViewType, String[], UInt32, Boolean, String, Boolean, Boolean)](ListExtensionsCreateViewListStringViewTypeString[]UInt32BooleanStringBooleanBoolean.md) | Create view to existing list
| [GetViewById(List, Guid, Linq.Expressions.Expression1<Func2<View,Object>>[])](ListExtensionsGetViewByIdListGuidLinq.Expressions.Expression1<Func2<View,Object>>[].md) | 
| [GetViewByName(List, String, Linq.Expressions.Expression1<Func2<View,Object>>[])](ListExtensionsGetViewByNameListStringLinq.Expressions.Expression1<Func2<View,Object>>[].md) | 
| [SetDefaultColumnValuesImplementation(List, Collections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.IDefaultColumnValue>)](ListExtensionsSetDefaultColumnValuesImplementationListCollections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.IDefaultColumnValue>.md) | 
| [SetDefaultColumnValues(List, Collections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.IDefaultColumnValue>)](ListExtensionsSetDefaultColumnValuesListCollections.Generic.IEnumerable1<OfficeDevPnP.Core.Entities.IDefaultColumnValue>.md) | 
| [GetDefaultColumnValues(List)](ListExtensionsGetDefaultColumnValuesList.md) | 
| [ReIndexList(List)](ListExtensionsReIndexListList.md) | Queues a list for a full crawl the next incremental crawl
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
