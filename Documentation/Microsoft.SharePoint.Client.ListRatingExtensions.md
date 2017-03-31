# ListRatingExtensions
Enables: Ratings / Likes functionality on list in publishing web.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class ListRatingExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [SetRating(List, VotingExperience)](Microsoft.SharePoint.Client.ListRatingExtensions.6D697640.md) | Enable Social Settings Likes/Ratings on list. Note: 1. Requires Publishing feature enabled on the web. 2. Defaults enable Ratings Experience on the List 3. When experience set to None, fields are not removed from the list since CSOM does not support removing hidden fields
| [RemoveViewFields()](Microsoft.SharePoint.Client.ListRatingExtensions.3E89BE40.md) | Removes the view fields associated with any rating type
| [AddListFields()](Microsoft.SharePoint.Client.ListRatingExtensions.97AF8335.md) | Add Ratings/Likes related fields to List from current Web
| [AddViewFields(VotingExperience)](Microsoft.SharePoint.Client.ListRatingExtensions.18EE796.md) | Add/Remove Ratings/Likes field in default view depending on exerpeince selected
| [RemoveField(List, Guid)](Microsoft.SharePoint.Client.ListRatingExtensions.F1B21E9B.md) | Removes a field from a list
| [EnsureField(List, Guid)](Microsoft.SharePoint.Client.ListRatingExtensions.52D5CBC0.md) | Check for Ratings/Likes field and add to ListField if doesn't exists.
| [SetProperty(VotingExperience)](Microsoft.SharePoint.Client.ListRatingExtensions.F06AAEEA.md) | Add required key/value settings on List Root-Folder
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
