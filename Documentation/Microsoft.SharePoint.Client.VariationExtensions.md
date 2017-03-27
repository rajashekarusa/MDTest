# VariationExtensions
Class that provides methods for variations
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class VariationExtensions```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ConfigureVariationsSettings(ClientContext, OfficeDevPnP.Core.Entities.VariationInformation)](VariationExtensionsConfigureVariationsSettingsClientContextOfficeDevPnP.Core.Entities.VariationInformation.md) | Configures the variation settings
            1. Go to "Site Actions" -> "Site settings"
            2. Under "Site collection administration", click "Variation Settings".
            This method is for the page above to change or update the "Variation Settings"
| [ProvisionSourceVariationLabel(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](VariationExtensionsProvisionSourceVariationLabelClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Creates source variation label
| [ProvisionTargetVariationLabels(ClientContext, Collections.Generic.List1<OfficeDevPnP.Core.Entities.VariationLabelEntity>)](VariationExtensionsProvisionTargetVariationLabelsClientContextCollections.Generic.List1<OfficeDevPnP.Core.Entities.VariationLabelEntity>.md) | 
| [WaitForVariationLabelCreation(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](VariationExtensionsWaitForVariationLabelCreationClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Wait for the variation label creation
| [GetVariationLabels(ClientContext)](VariationExtensionsGetVariationLabelsClientContext.md) | Retrieve all configured variation labels
| [CreateVariationLabels(ClientContext, Collections.Generic.List1<OfficeDevPnP.Core.Entities.VariationLabelEntity>)](VariationExtensionsCreateVariationLabelsClientContextCollections.Generic.List1<OfficeDevPnP.Core.Entities.VariationLabelEntity>.md) | 
| [CheckForHierarchyCreation(ClientContext, OfficeDevPnP.Core.Entities.VariationLabelEntity)](VariationExtensionsCheckForHierarchyCreationClientContextOfficeDevPnP.Core.Entities.VariationLabelEntity.md) | Checks if hierarchy is created for the variation label.
            Get the "Hierarchy_x0020_Is_x0020_Created" list item value
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
