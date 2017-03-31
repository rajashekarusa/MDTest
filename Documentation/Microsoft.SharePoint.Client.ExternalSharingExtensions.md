# ExternalSharingExtensions
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class ExternalSharingExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ResolvePeoplePickerValueForEmail(Web, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.7657A39C.md) | 
| [CreateAnonymousLinkForDocument(Web, String, ExternalSharingDocumentOption)](Microsoft.SharePoint.Client.ExternalSharingExtensions.65ADE625.md) | 
| [CreateAnonymousLinkWithExpirationForDocument(Web, String, ExternalSharingDocumentOption, DateTime)](Microsoft.SharePoint.Client.ExternalSharingExtensions.D634F954.md) | 
| [ShareDocument(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.66DC7567.md) | Abstracted methid for sharing documents just with given email address.
| [ShareDocumentWithPeoplePickerValue(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.1122069F.md) | Share document with complex JSON string value.
| [UnshareDocument(Web, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.FA304889.md) | Can be used to programatically to unshare any document with the document URL.
| [GetObjectSharingSettingsForDocument(Web, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.F6E910EE.md) | Get current sharing settings for document and load list of users it has been shared automatically.
| [GetObjectSharingSettingsForSite(Web, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.67D0238B.md) | Get current sharing settings for site and load list of users it has been shared automatically.
| [InviteExternalUser(Group, String, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.AA73B5F1.md) | Invites an external user as a group member
| [ShareSite(Web, String, Group, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.3710FEA1.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSite(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.E85402CE.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSiteWithPeoplePickerValue(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.7E4B4D30.md) | Share site for a person using complex JSON object for people picker value.
| [ShareSiteWithPeoplePickerValue(Web, String, Group, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.D3EE6E16.md) | Share site for a person using complex JSON object for people picker value.
| [SolveGroupIdToShare(Web, ExternalSharingSiteOption)](Microsoft.SharePoint.Client.ExternalSharingExtensions.12815574.md) | Used to solve right group ID to assign user into - used for the site level sharing.
## See also
- [M:Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocument(Microsoft.SharePoint.Client.Web,System.String,System.String,Microsoft.SharePoint.Client.ExternalSharingDocumentOption,System.Boolean,System.String,System.Boolean)](M:Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocument(Microsoft.SharePoint.Client.Web,System.String,System.String,Microsoft.SharePoint.Client.ExternalSharingDocumentOption,System.Boolean,System.String,System.Boolean).md)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
