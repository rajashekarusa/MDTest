# ExternalSharingExtensions

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class ExternalSharingExtensions```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ResolvePeoplePickerValueForEmail(Web, String)](ExternalSharingExtensionsResolvePeoplePickerValueForEmailWebString.md) | 
| [CreateAnonymousLinkForDocument(Web, String, ExternalSharingDocumentOption)](ExternalSharingExtensionsCreateAnonymousLinkForDocumentWebStringExternalSharingDocumentOption.md) | 
| [CreateAnonymousLinkWithExpirationForDocument(Web, String, ExternalSharingDocumentOption, DateTime)](ExternalSharingExtensionsCreateAnonymousLinkWithExpirationForDocumentWebStringExternalSharingDocumentOptionDateTime.md) | 
| [ShareDocument(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](ExternalSharingExtensionsShareDocumentWebStringStringExternalSharingDocumentOptionBooleanStringBoolean.md) | Abstracted methid for sharing documents just with given email address.
| [ShareDocumentWithPeoplePickerValue(Web, String, String, ExternalSharingDocumentOption, Boolean, String, Boolean)](ExternalSharingExtensionsShareDocumentWithPeoplePickerValueWebStringStringExternalSharingDocumentOptionBooleanStringBoolean.md) | Share document with complex JSON string value.
| [UnshareDocument(Web, String)](ExternalSharingExtensionsUnshareDocumentWebString.md) | Can be used to programatically to unshare any document with the document URL.
| [GetObjectSharingSettingsForDocument(Web, String, Boolean)](ExternalSharingExtensionsGetObjectSharingSettingsForDocumentWebStringBoolean.md) | Get current sharing settings for document and load list of users it has been shared automatically.
| [GetObjectSharingSettingsForSite(Web, Boolean)](ExternalSharingExtensionsGetObjectSharingSettingsForSiteWebBoolean.md) | Get current sharing settings for site and load list of users it has been shared automatically.
| [InviteExternalUser(Group, String, Boolean, String)](ExternalSharingExtensionsInviteExternalUserGroupStringBooleanString.md) | Invites an external user as a group member
| [ShareSite(Web, String, Group, Boolean, String)](ExternalSharingExtensionsShareSiteWebStringGroupBooleanString.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSite(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](ExternalSharingExtensionsShareSiteWebStringExternalSharingSiteOptionBooleanStringBoolean.md) | Share site for a person using just email. Will resolve needed people picker JSON value automatically.
| [ShareSiteWithPeoplePickerValue(Web, String, ExternalSharingSiteOption, Boolean, String, Boolean)](ExternalSharingExtensionsShareSiteWithPeoplePickerValueWebStringExternalSharingSiteOptionBooleanStringBoolean.md) | Share site for a person using complex JSON object for people picker value.
| [ShareSiteWithPeoplePickerValue(Web, String, Group, Boolean, String)](ExternalSharingExtensionsShareSiteWithPeoplePickerValueWebStringGroupBooleanString.md) | Share site for a person using complex JSON object for people picker value.
| [SolveGroupIdToShare(Web, ExternalSharingSiteOption)](ExternalSharingExtensionsSolveGroupIdToShareWebExternalSharingSiteOption.md) | Used to solve right group ID to assign user into - used for the site level sharing.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
