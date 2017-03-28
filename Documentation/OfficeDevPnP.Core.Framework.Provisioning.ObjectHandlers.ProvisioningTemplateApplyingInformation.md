# ProvisioningTemplateApplyingInformation

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class ProvisioningTemplateApplyingInformation
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ProvisioningTemplateApplyingInformation()](ProvisioningTemplateApplyingInformationconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [ProgressDelegate](ProvisioningTemplateApplyingInformation.ProgressDelegate.md) | 
| [MessagesDelegate](ProvisioningTemplateApplyingInformation.MessagesDelegate.md) | 
| [PersistTemplateInfo](ProvisioningTemplateApplyingInformation.PersistTemplateInfo.md) | 
| [OverwriteSystemPropertyBagValues](ProvisioningTemplateApplyingInformation.OverwriteSystemPropertyBagValues.md) | If true, system propertybag entries that start with _, vti_, dlc_ etc. will be overwritten if overwrite = true on the PropertyBagEntry. If not true those keys will be skipped, regardless of the overwrite property of the entry.
| [ClearNavigation](ProvisioningTemplateApplyingInformation.ClearNavigation.md) | If true, existing navigation nodes of the site (where applicable) will be cleared out before applying the navigation nodes from the template (if any). This setting will override any settings made in the template.
| [IgnoreDuplicateDataRowErrors](ProvisioningTemplateApplyingInformation.IgnoreDuplicateDataRowErrors.md) | If true then duplicate id errors when the same importing datarows simply generate a warning don't stop the engine. Reason for this is being able to apply the same template multiple times (Delta handling)
            without that failing cause the same record is being added twice
| [ProvisionContentTypesToSubWebs](ProvisioningTemplateApplyingInformation.ProvisionContentTypesToSubWebs.md) | If true then any content types in the template will be provisioned to subwebs
| [HandlersToProcess](ProvisioningTemplateApplyingInformation.HandlersToProcess.md) | 
| [ExtensibilityHandlers](ProvisioningTemplateApplyingInformation.ExtensibilityHandlers.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers](OfficeDevPnP.Core.Framework.Provisioning.ObjectHandlers.md)
