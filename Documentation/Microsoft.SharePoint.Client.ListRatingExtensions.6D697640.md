List, VotingExperience# ListRatingExtensions.SetRating members
Enable Social Settings Likes/Ratings on list. 
            Note: 1. Requires Publishing feature enabled on the web.
                  2. Defaults enable Ratings Experience on the List
                  3. When experience set to None, fields are not removed from the list since CSOM does not support removing hidden fields  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SetRating(List, VotingExperience)
```
### Parameters
#### list
Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
#### 
#### experience
Type: [OfficeDevPnP.Core.VotingExperience](OfficeDevPnP.Core.VotingExperience.md) 
#### 
### Return Value
Type: [System.Void](System.Void.md)## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
