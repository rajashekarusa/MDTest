# RecordsManagementExtensions
Class that deals with deprecated records management functionality  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class RecordsManagementExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [IsInPlaceRecordsManagementActive(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.43C6A592.md) | Checks if in place records management functionality is enabled for this site collection
| [ActivateInPlaceRecordsManagementFeature(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.3537381F.md) | Activate the in place records management feature
| [DisableInPlaceRecordsManagementFeature(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.8C9A2D70.md) | Deactivate the in place records management feature
| [EnableSiteForInPlaceRecordsManagement(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.1993740D.md) | Enable in place records management. The in place records management feature will be enabled and the in place record management will be enabled in all locations with record declaration allowed by all contributors and undeclaration by site admins
| [SetManualRecordDeclarationInAllLocations(Site, Boolean)](Microsoft.SharePoint.Client.RecordsManagementExtensions.E5A750B4.md) | Defines if in place records management is allowed in all places
| [GetManualRecordDeclarationInAllLocations(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.63E928BB.md) | Get the value of the records management is allowed in all places setting
| [SetRecordRestrictions(Site, EcmSiteRecordRestrictions)](Microsoft.SharePoint.Client.RecordsManagementExtensions.1B685F24.md) | Defines the restrictions that are placed on a document once it's declared as a record
| [GetRecordRestrictions(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.5D44E2D3.md) | Gets the current restrictions on declared records
| [SetRecordDeclarationBy(Site, EcmRecordDeclarationBy)](Microsoft.SharePoint.Client.RecordsManagementExtensions.47914E62.md) | Defines who can declare records
| [GetRecordDeclarationBy(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.8A882C7D.md) | Gets who can declare records
| [SetRecordUnDeclarationBy(Site, EcmRecordDeclarationBy)](Microsoft.SharePoint.Client.RecordsManagementExtensions.794EADC1.md) | Defines who can undeclare records
| [GetRecordUnDeclarationBy(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.526B1349.md) | Gets who can undeclare records
| [IsListRecordSettingDefined(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.DE1B84FC.md) | Checks if this list has active in place records management settings defined
| [SetListManualRecordDeclaration(List, EcmListManualRecordDeclaration)](Microsoft.SharePoint.Client.RecordsManagementExtensions.9A469FEB.md) | Defines the manual in place record declaration for this list
| [GetListManualRecordDeclaration(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.B115669F.md) | Gets the manual in place record declaration for this list
| [SetListAutoRecordDeclaration(List, Boolean)](Microsoft.SharePoint.Client.RecordsManagementExtensions.B8E7F815.md) | Defines if auto record declaration is active for this list: all added items will be automatically declared as a record if active
| [GetListAutoRecordDeclaration(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.C12E805C.md) | Returns if auto record declaration is active for this list
| [CreateECMRecordEventReceiverDefinition(EventReceiverType, Int32, Int32)](Microsoft.SharePoint.Client.RecordsManagementExtensions.11516BA6.md) | 
| [ContainsECMRecordEventReceiver(EventReceiverDefinitionCreationInformation, List<EventReceiverDefinition>)](Microsoft.SharePoint.Client.RecordsManagementExtensions.524CD77.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
