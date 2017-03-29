# FeatureExtensions
Class that holds deprecated feature activation and deactivation methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class FeatureExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ActivateFeature(Web, Guid, Boolean, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.ActivateFeatureWebGuidBooleanInt32.md) | Activates a site collection or site scoped feature
| [ActivateFeature(Site, Guid, Boolean, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.ActivateFeatureSiteGuidBooleanInt32.md) | Activates a site collection or site scoped feature
| [DeactivateFeature(Web, Guid, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.DeactivateFeatureWebGuidInt32.md) | Deactivates a site collection or site scoped feature
| [DeactivateFeature(Site, Guid, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.DeactivateFeatureSiteGuidInt32.md) | Deactivates a site collection or site scoped feature
| [IsFeatureActive(Site, Guid)](Microsoft.SharePoint.Client.FeatureExtensions.IsFeatureActiveSiteGuid.md) | Checks if a feature is active
| [IsFeatureActive(Web, Guid)](Microsoft.SharePoint.Client.FeatureExtensions.IsFeatureActiveWebGuid.md) | Checks if a feature is active
| [IsFeatureActiveInternal(FeatureCollection, Guid, Boolean)](Microsoft.SharePoint.Client.FeatureExtensions.IsFeatureActiveInternalFeatureCollectionGuidBoolean.md) | Checks if a feature is active in the given FeatureCollection.
| [ProcessFeature(Site, Guid, Boolean, Boolean, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.ProcessFeatureSiteGuidBooleanBooleanInt32.md) | Activates or deactivates a site collection scoped feature
| [ProcessFeature(Web, Guid, Boolean, Boolean, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.ProcessFeatureWebGuidBooleanBooleanInt32.md) | Activates or deactivates a web scoped feature
| [ProcessFeatureInternal(FeatureCollection, Guid, Boolean, FeatureDefinitionScope, Int32)](Microsoft.SharePoint.Client.FeatureExtensions.ProcessFeatureInternalFeatureCollectionGuidBooleanFeatureDefinitionScopeInt32.md) | Activates or deactivates a site collection or web scoped feature
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
