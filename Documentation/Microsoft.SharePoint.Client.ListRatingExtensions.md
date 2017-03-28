# ListRatingExtensions
Enables: Ratings / Likes functionality on list in publishing web.
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class ListRatingExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [SetRating(List, OfficeDevPnP.Core.VotingExperience)](ListRatingExtensionsSetRatingListOfficeDevPnP.Core.VotingExperience.md) | Enable Social Settings Likes/Ratings on list. Note: 1. Requires Publishing feature enabled on the web. 2. Defaults enable Ratings Experience on the List 3. When experience set to None, fields are not removed from the list since CSOM does not support removing hidden fields
| [RemoveViewFields()](ListRatingExtensionsRemoveViewFields.md) | Removes the view fields associated with any rating type
| [AddListFields()](ListRatingExtensionsAddListFields.md) | Add Ratings/Likes related fields to List from current Web
| [AddViewFields(OfficeDevPnP.Core.VotingExperience)](ListRatingExtensionsAddViewFieldsOfficeDevPnP.Core.VotingExperience.md) | Add/Remove Ratings/Likes field in default view depending on exerpeince selected
| [RemoveField(List, Guid)](ListRatingExtensionsRemoveFieldListGuid.md) | Removes a field from a list
| [EnsureField(List, Guid)](ListRatingExtensionsEnsureFieldListGuid.md) | Check for Ratings/Likes field and add to ListField if doesn't exists.
| [SetProperty(OfficeDevPnP.Core.VotingExperience)](ListRatingExtensionsSetPropertyOfficeDevPnP.Core.VotingExperience.md) | Add required key/value settings on List Root-Folder
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
