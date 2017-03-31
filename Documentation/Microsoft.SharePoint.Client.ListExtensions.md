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
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Boolean)](Microsoft.SharePoint.Client.ListExtensions.b9c036ed.md) | Registers a remote event receiver
| [AddRemoteEventReceiver(List, String, String, EventReceiverType, EventReceiverSynchronization, Int32, Boolean)](Microsoft.SharePoint.Client.ListExtensions.f19fbc38.md) | Registers a remote event receiver
| [GetEventReceiverById(List, Guid)](Microsoft.SharePoint.Client.ListExtensions.63be7c1a.md) | Returns an event receiver definition
| [GetEventReceiverByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.fcdeff9f.md) | Returns an event receiver definition
| [SetPropertyBagValue(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.c741671e.md) | Sets a key/value pair in the web property bag
| [SetPropertyBagValue(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.f4a64b4f.md) | Sets a key/value pair in the list property bag
| [GetPropertyBagValueInt(List, String, Int32)](Microsoft.SharePoint.Client.ListExtensions.1e690ec1.md) | Get int typed property bag value. If does not contain, returns default value.
| [GetPropertyBagValueString(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.6838ef8b.md) | Get string typed property bag value. If does not contain, returns given default value.
| [PropertyBagContainsKey(List, String)](Microsoft.SharePoint.Client.ListExtensions.1fcb2c8b.md) | Checks if the given property bag entry exists
| [RemoveContentTypeByName(List, String)](Microsoft.SharePoint.Client.ListExtensions.8e0c93ca.md) | Removes a content type from a list/library by name
| [CreateDocumentLibrary(Web, String, Boolean, String)](Microsoft.SharePoint.Client.ListExtensions.e18b841c.md) | Adds a document library to a web. Execute Query is called during this implementation
| [ListExists(Web, String)](Microsoft.SharePoint.Client.ListExtensions.696f8225.md) | Checks if list exists on the particular site based on the list Title property.
| [ListExists(Web, Uri)](Microsoft.SharePoint.Client.ListExtensions.18ffaeae.md) | Checks if list exists on the particular site based on the list's site relative path.
| [ListExists(Web, Guid)](Microsoft.SharePoint.Client.ListExtensions.b0dd134e.md) | Checks if list exists on the particular site based on the list id property.
| [CreateList(Web, ListTemplateType, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.8c2b1d97.md) | Adds a default list to a site
| [CreateList(Web, Guid, Int32, String, Boolean, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ListExtensions.bc245822.md) | Adds a custom list to a site
| [UpdateListVersioning(Web, String, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.3db99d1b.md) | Enable/disable versioning on a list
| [UpdateListVersioning(List, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.9a7ebb3c.md) | Enable/disable versioning on a list
| [UpdateTaxonomyFieldDefaultValue(Web, String, String, String, Guid, Guid)](Microsoft.SharePoint.Client.ListExtensions.24c445b5.md) | Sets the default value for a managed metadata column in the specified list. This operation will not change existing items in the list
| [SetJSLinkCustomizations(List, PageType, String)](Microsoft.SharePoint.Client.ListExtensions.2f8c0ee3.md) | Sets JS link customization for a list form
| [SetJSLinkCustomizations(List, String, String)](Microsoft.SharePoint.Client.ListExtensions.81a6f21d.md) | Sets JS link customization for a list view page
| [SetLocalizationLabelsForList(Web, String, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.80380769.md) | 
| [SetLocalizationLabelsForList(List, String, String, String)](Microsoft.SharePoint.Client.ListExtensions.8ed7fd4c.md) | Can be used to set translations for different cultures.
| [GetListID(Web, String)](Microsoft.SharePoint.Client.ListExtensions.7e803d44.md) | Returns the GUID id of a list
| [GetListByTitle(Web, String, Expression<Func<List, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.8078cf54.md) | 
| [GetListByUrl(Web, String, Expression<Func<List, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.45b98e2a.md) | 
| [GetPagesLibrary(Web)](Microsoft.SharePoint.Client.ListExtensions.72bc72eb.md) | Gets the publishing pages library of the web based on site language
| [GetWebRelativeUrl(List)](Microsoft.SharePoint.Client.ListExtensions.1d0b225d.md) | Gets the web relative URL. Allow users to get the web relative URL of a list. This is useful when exporting lists as it can then be used as a parameter to Web.GetListByUrl().
| [SetListPermission(List, BuiltInIdentity, RoleType)](Microsoft.SharePoint.Client.ListExtensions.1f730c53.md) | Set custom permission to the list
| [SetListPermission(List, Principal, RoleType)](Microsoft.SharePoint.Client.ListExtensions.bd1961ba.md) | Set custom permission to the list
| [CreateViewsFromXMLFile(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.1bdf14c8.md) | Creates list views based on specific xml structure from file
| [CreateViewsFromXMLString(Web, String, String)](Microsoft.SharePoint.Client.ListExtensions.a682431e.md) | Creates views based on specific xml structure from string
| [CreateViewsFromXML(Web, String, XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.eaed2442.md) | Create list views based on xml structure loaded to memory
| [CreateViewsFromXMLFile(List, String)](Microsoft.SharePoint.Client.ListExtensions.7dfceb65.md) | Create list views based on specific xml structure in external file
| [CreateViewsFromXMLString(List, String)](Microsoft.SharePoint.Client.ListExtensions.e6e048f7.md) | Create list views based on specific xml structure in string
| [CreateViewsFromXML(List, XmlDocument)](Microsoft.SharePoint.Client.ListExtensions.8b3c7905.md) | Actual implementation of the view creation logic based on given xml
| [CreateView(List, String, ViewType, String[], UInt32, Boolean, String, Boolean, Boolean)](Microsoft.SharePoint.Client.ListExtensions.1a961e12.md) | Create view to existing list
| [GetViewById(List, Guid, Expression<Func<View, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.77ca9349.md) | 
| [GetViewByName(List, String, Expression<Func<View, Object>>[])](Microsoft.SharePoint.Client.ListExtensions.53d0489.md) | 
| [SetDefaultColumnValues(List, IEnumerable<IDefaultColumnValue>)](Microsoft.SharePoint.Client.ListExtensions.4bb08d61.md) | 
| [GetDefaultColumnValues(List)](Microsoft.SharePoint.Client.ListExtensions.b3d11314.md) | 
| [ReIndexList(List)](Microsoft.SharePoint.Client.ListExtensions.9d2ca161.md) | Queues a list for a full crawl the next incremental crawl
## Examples
```C#
 list.SetLocalizationForSiteLabels("fi-fi", "Name of the site in Finnish", "Description in Finnish"); 
```
## See also
- [http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx](http://blogs.msdn.com/b/vesku/archive/2014/03/20/office365-multilingual-content-types-site-columns-and-site-other-elements.aspx)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
