# VariationExtensions
Class that provides methods for variations  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class VariationExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ConfigureVariationsSettings(ClientContext, OfficeDevPnP.Core.Entities.VariationInformation)](Microsoft.SharePoint.Client.VariationExtensions.ConfigureVariationsSettingsClientContextOfficeDevPnP.Core.Entities.VariationInformation.md) | Configures the variation settings 1. Go to "Site Actions" -> "Site settings" 2. Under "Site collection administration", click "Variation Settings". This method is for the page above to change or update the "Variation Settings"
| [ProvisionSourceVariationLabel(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](Microsoft.SharePoint.Client.VariationExtensions.ProvisionSourceVariationLabelClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Creates source variation label
| [ProvisionTargetVariationLabels(ClientContext, Collections.Generic.List<OfficeDevPnP.Core.Entities.VariationLabelEntity>)](Microsoft.SharePoint.Client.VariationExtensions.ProvisionTargetVariationLabelsClientContextCollections.Generic.List<OfficeDevPnP.Core.Entities.VariationLabelEntity>.md) | 
| [WaitForVariationLabelCreation(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](Microsoft.SharePoint.Client.VariationExtensions.WaitForVariationLabelCreationClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Wait for the variation label creation
| [GetVariationLabels(ClientContext)](Microsoft.SharePoint.Client.VariationExtensions.GetVariationLabelsClientContext.md) | Retrieve all configured variation labels
| [CreateVariationLabels(ClientContext, Collections.Generic.List<OfficeDevPnP.Core.Entities.VariationLabelEntity>)](Microsoft.SharePoint.Client.VariationExtensions.CreateVariationLabelsClientContextCollections.Generic.List<OfficeDevPnP.Core.Entities.VariationLabelEntity>.md) | 
| [CheckForHierarchyCreation(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](Microsoft.SharePoint.Client.VariationExtensions.CheckForHierarchyCreationClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Checks if hierarchy is created for the variation label. Get the "Hierarchy_x0020_Is_x0020_Created" list item value
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
