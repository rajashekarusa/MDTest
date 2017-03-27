# FeatureExtensions
Class that holds deprecated feature activation and deactivation methods
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class FeatureExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ActivateFeature(Web, Guid, Boolean, Int32)](FeatureExtensionsActivateFeatureWebGuidBooleanInt32.md) | Activates a site collection or site scoped feature
| [ActivateFeature(Site, Guid, Boolean, Int32)](FeatureExtensionsActivateFeatureSiteGuidBooleanInt32.md) | Activates a site collection or site scoped feature
| [DeactivateFeature(Web, Guid, Int32)](FeatureExtensionsDeactivateFeatureWebGuidInt32.md) | Deactivates a site collection or site scoped feature
| [DeactivateFeature(Site, Guid, Int32)](FeatureExtensionsDeactivateFeatureSiteGuidInt32.md) | Deactivates a site collection or site scoped feature
| [IsFeatureActive(Site, Guid)](FeatureExtensionsIsFeatureActiveSiteGuid.md) | Checks if a feature is active
| [IsFeatureActive(Web, Guid)](FeatureExtensionsIsFeatureActiveWebGuid.md) | Checks if a feature is active
| [IsFeatureActiveInternal(FeatureCollection, Guid, Boolean)](FeatureExtensionsIsFeatureActiveInternalFeatureCollectionGuidBoolean.md) | Checks if a feature is active in the given FeatureCollection.
| [ProcessFeature(Site, Guid, Boolean, Boolean, Int32)](FeatureExtensionsProcessFeatureSiteGuidBooleanBooleanInt32.md) | Activates or deactivates a site collection scoped feature
| [ProcessFeature(Web, Guid, Boolean, Boolean, Int32)](FeatureExtensionsProcessFeatureWebGuidBooleanBooleanInt32.md) | Activates or deactivates a web scoped feature
| [ProcessFeatureInternal(FeatureCollection, Guid, Boolean, FeatureDefinitionScope, Int32)](FeatureExtensionsProcessFeatureInternalFeatureCollectionGuidBooleanFeatureDefinitionScopeInt32.md) | Activates or deactivates a site collection or web scoped feature
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
