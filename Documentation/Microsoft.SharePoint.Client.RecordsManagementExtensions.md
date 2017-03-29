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
| [IsInPlaceRecordsManagementActive(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.IsInPlaceRecordsManagementActiveSite.md) | Checks if in place records management functionality is enabled for this site collection
| [ActivateInPlaceRecordsManagementFeature(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.ActivateInPlaceRecordsManagementFeatureSite.md) | Activate the in place records management feature
| [DisableInPlaceRecordsManagementFeature(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.DisableInPlaceRecordsManagementFeatureSite.md) | Deactivate the in place records management feature
| [EnableSiteForInPlaceRecordsManagement(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.EnableSiteForInPlaceRecordsManagementSite.md) | Enable in place records management. The in place records management feature will be enabled and the in place record management will be enabled in all locations with record declaration allowed by all contributors and undeclaration by site admins
| [SetManualRecordDeclarationInAllLocations(Site, Boolean)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetManualRecordDeclarationInAllLocationsSiteBoolean.md) | Defines if in place records management is allowed in all places
| [GetManualRecordDeclarationInAllLocations(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetManualRecordDeclarationInAllLocationsSite.md) | Get the value of the records management is allowed in all places setting
| [SetRecordRestrictions(Site, OfficeDevPnP.Core.EcmSiteRecordRestrictions)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetRecordRestrictionsSiteOfficeDevPnP.Core.EcmSiteRecordRestrictions.md) | Defines the restrictions that are placed on a document once it's declared as a record
| [GetRecordRestrictions(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetRecordRestrictionsSite.md) | Gets the current restrictions on declared records
| [SetRecordDeclarationBy(Site, OfficeDevPnP.Core.EcmRecordDeclarationBy)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetRecordDeclarationBySiteOfficeDevPnP.Core.EcmRecordDeclarationBy.md) | Defines who can declare records
| [GetRecordDeclarationBy(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetRecordDeclarationBySite.md) | Gets who can declare records
| [SetRecordUnDeclarationBy(Site, OfficeDevPnP.Core.EcmRecordDeclarationBy)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetRecordUnDeclarationBySiteOfficeDevPnP.Core.EcmRecordDeclarationBy.md) | Defines who can undeclare records
| [GetRecordUnDeclarationBy(Site)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetRecordUnDeclarationBySite.md) | Gets who can undeclare records
| [IsListRecordSettingDefined(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.IsListRecordSettingDefinedList.md) | Checks if this list has active in place records management settings defined
| [SetListManualRecordDeclaration(List, OfficeDevPnP.Core.EcmListManualRecordDeclaration)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetListManualRecordDeclarationListOfficeDevPnP.Core.EcmListManualRecordDeclaration.md) | Defines the manual in place record declaration for this list
| [GetListManualRecordDeclaration(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetListManualRecordDeclarationList.md) | Gets the manual in place record declaration for this list
| [SetListAutoRecordDeclaration(List, Boolean)](Microsoft.SharePoint.Client.RecordsManagementExtensions.SetListAutoRecordDeclarationListBoolean.md) | Defines if auto record declaration is active for this list: all added items will be automatically declared as a record if active
| [GetListAutoRecordDeclaration(List)](Microsoft.SharePoint.Client.RecordsManagementExtensions.GetListAutoRecordDeclarationList.md) | Returns if auto record declaration is active for this list
| [CreateECMRecordEventReceiverDefinition(EventReceiverType, Int32, Int32)](Microsoft.SharePoint.Client.RecordsManagementExtensions.CreateECMRecordEventReceiverDefinitionEventReceiverTypeInt32Int32.md) | 
| [ContainsECMRecordEventReceiver(EventReceiverDefinitionCreationInformation, Collections.Generic.List<EventReceiverDefinition>)](Microsoft.SharePoint.Client.RecordsManagementExtensions.ContainsECMRecordEventReceiverEventReceiverDefinitionCreationInformationCollections.Generic.List<EventReceiverDefinition>.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
