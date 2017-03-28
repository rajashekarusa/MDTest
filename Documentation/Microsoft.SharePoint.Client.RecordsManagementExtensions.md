# RecordsManagementExtensions
Class that deals with deprecated records management functionality  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class RecordsManagementExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [IsInPlaceRecordsManagementActive(Site)](RecordsManagementExtensionsIsInPlaceRecordsManagementActiveSite.md) | Checks if in place records management functionality is enabled for this site collection
| [ActivateInPlaceRecordsManagementFeature(Site)](RecordsManagementExtensionsActivateInPlaceRecordsManagementFeatureSite.md) | Activate the in place records management feature
| [DisableInPlaceRecordsManagementFeature(Site)](RecordsManagementExtensionsDisableInPlaceRecordsManagementFeatureSite.md) | Deactivate the in place records management feature
| [EnableSiteForInPlaceRecordsManagement(Site)](RecordsManagementExtensionsEnableSiteForInPlaceRecordsManagementSite.md) | Enable in place records management. The in place records management feature will be enabled and the in place record management will be enabled in all locations with record declaration allowed by all contributors and undeclaration by site admins
| [SetManualRecordDeclarationInAllLocations(Site, Boolean)](RecordsManagementExtensionsSetManualRecordDeclarationInAllLocationsSiteBoolean.md) | Defines if in place records management is allowed in all places
| [GetManualRecordDeclarationInAllLocations(Site)](RecordsManagementExtensionsGetManualRecordDeclarationInAllLocationsSite.md) | Get the value of the records management is allowed in all places setting
| [SetRecordRestrictions(Site, OfficeDevPnP.Core.EcmSiteRecordRestrictions)](RecordsManagementExtensionsSetRecordRestrictionsSiteOfficeDevPnP.Core.EcmSiteRecordRestrictions.md) | Defines the restrictions that are placed on a document once it's declared as a record
| [GetRecordRestrictions(Site)](RecordsManagementExtensionsGetRecordRestrictionsSite.md) | Gets the current restrictions on declared records
| [SetRecordDeclarationBy(Site, OfficeDevPnP.Core.EcmRecordDeclarationBy)](RecordsManagementExtensionsSetRecordDeclarationBySiteOfficeDevPnP.Core.EcmRecordDeclarationBy.md) | Defines who can declare records
| [GetRecordDeclarationBy(Site)](RecordsManagementExtensionsGetRecordDeclarationBySite.md) | Gets who can declare records
| [SetRecordUnDeclarationBy(Site, OfficeDevPnP.Core.EcmRecordDeclarationBy)](RecordsManagementExtensionsSetRecordUnDeclarationBySiteOfficeDevPnP.Core.EcmRecordDeclarationBy.md) | Defines who can undeclare records
| [GetRecordUnDeclarationBy(Site)](RecordsManagementExtensionsGetRecordUnDeclarationBySite.md) | Gets who can undeclare records
| [IsListRecordSettingDefined(List)](RecordsManagementExtensionsIsListRecordSettingDefinedList.md) | Checks if this list has active in place records management settings defined
| [SetListManualRecordDeclaration(List, OfficeDevPnP.Core.EcmListManualRecordDeclaration)](RecordsManagementExtensionsSetListManualRecordDeclarationListOfficeDevPnP.Core.EcmListManualRecordDeclaration.md) | Defines the manual in place record declaration for this list
| [GetListManualRecordDeclaration(List)](RecordsManagementExtensionsGetListManualRecordDeclarationList.md) | Gets the manual in place record declaration for this list
| [SetListAutoRecordDeclaration(List, Boolean)](RecordsManagementExtensionsSetListAutoRecordDeclarationListBoolean.md) | Defines if auto record declaration is active for this list: all added items will be automatically declared as a record if active
| [GetListAutoRecordDeclaration(List)](RecordsManagementExtensionsGetListAutoRecordDeclarationList.md) | Returns if auto record declaration is active for this list
| [CreateECMRecordEventReceiverDefinition(EventReceiverType, Int32, Int32)](RecordsManagementExtensionsCreateECMRecordEventReceiverDefinitionEventReceiverTypeInt32Int32.md) | 
| [ContainsECMRecordEventReceiver(EventReceiverDefinitionCreationInformation, Collections.Generic.List1<EventReceiverDefinition>)](RecordsManagementExtensionsContainsECMRecordEventReceiverEventReceiverDefinitionCreationInformationCollections.Generic.List1<EventReceiverDefinition>.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
