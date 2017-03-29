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
| [ResolvePeoplePickerValueForEmail(Web, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ResolvePeoplePickerValueForEmailWebString.md) | 
| [CreateAnonymousLinkForDocument(Web, String, ExternalSharingDocumentOption)](Microsoft.SharePoint.Client.ExternalSharingExtensions.CreateAnonymousLinkForDocumentWebStringExternalSharingDocumentOption.md) | 
| [CreateAnonymousLinkWithExpirationForDocument(Web, String, ExternalSharingDocumentOption, DateTime)](Microsoft.SharePoint.Client.ExternalSharingExtensions.CreateAnonymousLinkWithExpirationForDocumentWebStringExternalSharingDocumentOptionDateTime.md) | 
| [ShareDocument(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocumentWebStringStringExternalSharingDocumentOptionBooleanStringBoolean.md) | Abstracted methid for sharing documents just with given email address.
| [ShareDocumentWithPeoplePickerValue(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocumentWithPeoplePickerValueWebStringStringExternalSharingDocumentOptionBooleanStringBoolean.md) | Share document with complex JSON string value.
| [UnshareDocument(Web, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.UnshareDocumentWebString.md) | Can be used to programatically to unshare any document with the document URL.
| [GetObjectSharingSettingsForDocument(Web, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.GetObjectSharingSettingsForDocumentWebStringBoolean.md) | Get current sharing settings for document and load list of users it has been shared automatically.
| [GetObjectSharingSettingsForSite(Web, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.GetObjectSharingSettingsForSiteWebBoolean.md) | Get current sharing settings for site and load list of users it has been shared automatically.
| [InviteExternalUser(Group, String, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.InviteExternalUserGroupStringBooleanString.md) | Invites an external user as a group member
| [ShareSite(Web, String, Group, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareSiteWebStringGroupBooleanString.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSite(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareSiteWebStringExternalSharingSiteOptionBooleanStringBoolean.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSiteWithPeoplePickerValue(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareSiteWithPeoplePickerValueWebStringExternalSharingSiteOptionBooleanStringBoolean.md) | Share site for a person using complex JSON object for people picker value.
| [ShareSiteWithPeoplePickerValue(Web, String, Group, Boolean, String)](Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareSiteWithPeoplePickerValueWebStringGroupBooleanString.md) | Share site for a person using complex JSON object for people picker value.
| [SolveGroupIdToShare(Web, ExternalSharingSiteOption)](Microsoft.SharePoint.Client.ExternalSharingExtensions.SolveGroupIdToShareWebExternalSharingSiteOption.md) | Used to solve right group ID to assign user into - used for the site level sharing.
## See also
- [M:Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocument(Microsoft.SharePoint.Client.Web,System.String,System.String,Microsoft.SharePoint.Client.ExternalSharingDocumentOption,System.Boolean,System.String,System.Boolean)](M:Microsoft.SharePoint.Client.ExternalSharingExtensions.ShareDocument(Microsoft.SharePoint.Client.Web,System.String,System.String,Microsoft.SharePoint.Client.ExternalSharingDocumentOption,System.Boolean,System.String,System.Boolean).md)
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
