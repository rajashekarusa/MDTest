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
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](Microsoft.SharePoint.Client.ListExtensions.B9C036ED.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](Microsoft.SharePoint.Client.ListExtensions.F19FBC38.md) | Registers a remote event receiver
| [GetEventReceiverById(List, Guid)](Microsoft.SharePoint.Client.ListExtensions.63BE7C1A.md) | Returns an event receiver definition
| [GetEventReceiverByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.FCDEFF9F.md) | Returns an event receiver definition
| [SetPropertyBagValue(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.C741671E.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.F4A64B4F.md) | Sets a key/value pair in the list property bag
| [SetPropertyBagValueInternal(List, String, Object)](Microsoft.SharePoint.Client.ListExtensions.A60FBDFC.md) | Sets a key/value pair in the list property bag
| [GetPropertyBagValueInt(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.1E690EC1.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.6838EF8B.md) | Get string typed property bag value. If does not contain, returns given default value.
| [GetPropertyBagValueInternal(List, String)](Microsoft.SharePoint.Client.ListExtensions.F1204806.md) | Type independent implementation of the property gettter.
| [PropertyBagContainsKey(List, String)](Microsoft.SharePoint.Client.ListExtensions.1FCB2C8B.md) | Checks if the given property bag entry exists
| [RemoveContentTypeByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.8E0C93CA.md) | Removes a content type from a list/library by name
| [CreateDocumentLibrary(Web, String, Boolean, String)](Microsoft.SharePoint.Client.ListExtensions.E18B841C.md) | Adds a document library to a web. Execute Query is called during this implementation
| [ListExists(Web, String)](Microsoft.SharePoint.Client.ListExtensions.696F8225.md) | Checks if list exists on the particular site based on the list Title property.
| [ListExists(Web, Uri)](Microsoft.SharePoint.Client.ListExtensions.18FFAEAE.md) | Checks if list exists on the particular site based on the list's site relative path.
| [ListExists(Web, Guid)](Microsoft.SharePoint.Client.ListExtensions.B0DD134E.md) | Checks if list exists on the particular site based on the list id property.
| [CreateList(Web, ListTemplateType, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.8C2B1D97.md) | Adds a default list to a site
| [CreateList(Web, Guid, Int32, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.BC245822.md) | Adds a custom list to a site
| [CreateListInternal(Web, Nullable<Guid>, Int32, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.F5DB462F.md) | 
| [UpdateListVersioning(Web, String, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.3DB99D1B.md) | Enable/disable versioning on a list
| [UpdateListVersioning(List, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.9A7EBB3C.md) | Enable/disable versioning on a list
| [UpdateTaxonomyFieldDefaultValue(Web, String, String, String, Guid, Guid)](Microsoft.SharePoint.Client.ListExtensions.24C445B5.md) | Sets the default value for a managed metadata column in the specified list. This operation will not change existing items in the list
| [SetJSLinkCustomizations(List, PageType, String)](Microsoft.SharePoint.Client.ListExtensions.2F8C0EE3.md) | Sets JS link customization for a list form
| [SetJSLinkCustomizations(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.81A6F21D.md) | Sets JS link customization for a list view page
| [SetJSLinkCustomizationsImplementation(List, File, String)](Microsoft.SharePoint.Client.ListExtensions.CAC1335A.md) | 
| [SetLocalizationLabelsForList(Web, String, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.80380769.md) | 
| [SetLocalizationLabelsForList(List, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.8ED7FD4C.md) | Can be used to set translations for different cultures.
| [GetListID(Web, String)](Microsoft.SharePoint.Client.ListExtensions.7E803D44.md) | Returns the GUID id of a list
| [GetListByTitle(Web, String, Expression<Func<List, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.8078CF54.md) | 
| [GetListByUrl(Web, String, Expression<Func<List, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.45B98E2A.md) | 
| [GetPagesLibrary(Web)](Microsoft.SharePoint.Client.ListExtensions.72BC72EB.md) | Gets the publishing pages library of the web based on site language
| [GetWebRelativeUrl(List)](Microsoft.SharePoint.Client.ListExtensions.1D0B225D.md) | Gets the web relative URL. Allow users to get the web relative URL of a list. This is useful when exporting lists as it can then be used as a parameter to Web.GetListByUrl().
| [GetWebRelativeUrl(String, String)](Microsoft.SharePoint.Client.ListExtensions.192DE070.md) | Gets the web relative URL.
| [SetListPermission(List, BuiltInIdentity, RoleType)](Microsoft.SharePoint.Client.ListExtensions.1F730C53.md) | Set custom permission to the list
| [SetListPermission(List, Principal, RoleType)](Microsoft.SharePoint.Client.ListExtensions.BD1961BA.md) | Set custom permission to the list
| [CreateViewsFromXMLFile(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.1BDF14C8.md) | Creates list views based on specific xml structure from file
| [CreateViewsFromXMLString(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.A682431E.md) | Creates views based on specific xml structure from string
| [CreateViewsFromXML(Web, String, XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.EAED2442.md) | Create list views based on xml structure loaded to memory
| [CreateViewsFromXMLFile(List, String)](Microsoft.SharePoint.Client.ListExtensions.7DFCEB65.md) | Create list views based on specific xml structure in external file
| [CreateViewsFromXMLString(List, String)](Microsoft.SharePoint.Client.ListExtensions.E6E048F7.md) | Create list views based on specific xml structure in string
| [CreateViewsFromXML(List, XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.8B3C7905.md) | Actual implementation of the view creation logic based on given xml
| [CreateView(List, String, ViewType, String[], UInt32, Boolean, String, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.1A961E12.md) | Create view to existing list
| [GetViewById(List, Guid, Expression<Func<View, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.77CA9349.md) | 
| [GetViewByName(List, String, Expression<Func<View, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.53D0489.md) | 
| [SetDefaultColumnValuesImplementation(List, IEnumerable<IDefaultColumnValue>)](Microsoft.SharePoint.Client.ListExtensions.D1FF784.md) | 
| [SetDefaultColumnValues(List, IEnumerable<IDefaultColumnValue>)](Microsoft.SharePoint.Client.ListExtensions.4BB08D61.md) | 
| [GetDefaultColumnValues(List)](Microsoft.SharePoint.Client.ListExtensions.B3D11314.md) | 
| [ReIndexList(List)](Microsoft.SharePoint.Client.ListExtensions.9D2CA161.md) | Queues a list for a full crawl the next incremental crawl
## Examples
```C#
 list.SetLocalizationForSiteLabels("fi-fi", "Name of the site in Finnish", "Description in Finnish"); 
```
## See also
- [http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx](http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
