# SecurityExtensions
This manager class holds deprecated security related methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class SecurityExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetAdministrators(Web)](Microsoft.SharePoint.Client.SecurityExtensions.10B24275.md) | Get a list of site collection administrators
| [AddAdministrators(Web, List<UserEntity>, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.6AE7B819.md) | 
| [RemoveAdministrator(Web, UserEntity)](Microsoft.SharePoint.Client.SecurityExtensions.FE945EB0.md) | Removes an administrators from the site collection
| [AddReaderAccess(Web)](Microsoft.SharePoint.Client.SecurityExtensions.ED280CD0.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccess(Web, BuiltInIdentity)](Microsoft.SharePoint.Client.SecurityExtensions.C7DA83A8.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccessImplementation(Web, BuiltInIdentity)](Microsoft.SharePoint.Client.SecurityExtensions.3B9A10A7.md) | 
| [GetSharingCapabilitiesTenant(Web, Uri)](Microsoft.SharePoint.Client.SecurityExtensions.6165887C.md) | Get the external sharing settings for the provided site. Only works in Office 365 Multi-Tenant
| [GetExternalUsersTenant(Web)](Microsoft.SharePoint.Client.SecurityExtensions.DAC3008A.md) | Returns a list all external users in your tenant
| [GetExternalUsersForSiteTenant(Web, Uri)](Microsoft.SharePoint.Client.SecurityExtensions.96E5DABD.md) | Returns a list all external users for a given site that have at least the viewpages permission
| [GetGroupID(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.14A0CF4F.md) | Returns the integer ID for a given group name
| [AddGroup(Web, String, String, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.6821C296.md) | Adds a group
| [AssociateDefaultGroups(Web, Group, Group, Group)](Microsoft.SharePoint.Client.SecurityExtensions.9CEAF057.md) | Associate the provided groups as default owners, members or visitors groups. If a group is null then the association is not done
| [AddUserToGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.174DA59D.md) | Adds a user to a group
| [AddUserToGroup(Web, Int32, String)](Microsoft.SharePoint.Client.SecurityExtensions.A15D4933.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, User)](Microsoft.SharePoint.Client.SecurityExtensions.86E5291A.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, String)](Microsoft.SharePoint.Client.SecurityExtensions.FB8DC920.md) | Adds a user to a group
| [AddPermissionLevelToUser(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.5ADAD6C1.md) | Add a permission level (e.g.Contribute, Reader,...) to a user
| [AddPermissionLevelToUser(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.F973C234.md) | Add a role definition (e.g.Contribute, Read, Approve) to a user
| [AddPermissionLevelToGroup(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.7E8844C.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.27DD60BF.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToGroup(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.E4482CF4.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.BCAFBED3.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.6A88D4E3.md) | 
| [RemovePermissionLevelFromUser(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.B4DB0942.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.8F162E10.md) | Removes a permission level from a user
| [RemovePermissionLevelFromUser(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.4D6B82EF.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.F3F34F1.md) | Removes a permission level from a user
| [RemovePermissionLevelFromGroup(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.D42B6C97.md) | Removes a permission level from a group
| [RemovePermissionLevelFromGroup(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.64EEF5DF.md) | Removes a permission level from a group
| [RemovePermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.D029C12B.md) | 
| [GetAssociatedWeb(SecurableObject)](Microsoft.SharePoint.Client.SecurityExtensions.DA1F9241.md) | 
| [RemoveUserFromGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.EC40D40C.md) | Removes a user from a group
| [RemoveUserFromGroup(Web, Group, User)](Microsoft.SharePoint.Client.SecurityExtensions.138472C.md) | Removes a user from a group
| [RemoveGroup(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.20A8AF35.md) | Remove a group
| [RemoveGroup(Web, Group)](Microsoft.SharePoint.Client.SecurityExtensions.BFA1EE44.md) | Remove a group
| [IsUserInGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.75D377F2.md) | Checks if a user is member of a group
| [GroupExists(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.7E0748A8.md) | Checks if a group exists
| [IsGroupCannotBeFoundException(Exception)](Microsoft.SharePoint.Client.SecurityExtensions.15560D8B.md) | 
| [GetAuthenticationRealm(Web)](Microsoft.SharePoint.Client.SecurityExtensions.C7F71F9E.md) | Returns the authentication realm for the current web
| [GetPath(SecurableObject)](Microsoft.SharePoint.Client.SecurityExtensions.E125969F.md) | Get URL path of a securable object
| [Preload(SecurableObject, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.6C795FF5.md) | Load properties of the current securable object and get child securable objects with unique role assignments if any.
| [Visit(SecurableObject, Int32, Action<SecurableObject, String>)](Microsoft.SharePoint.Client.SecurityExtensions.27C75005.md) | 
| [GetUserEmail(Web, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.895DECA1.md) | Get user email by user id.
| [EnsureGroupCache(SecurableObject, String)](Microsoft.SharePoint.Client.SecurityExtensions.FD933433.md) | Ensure all users of a given SharePoint group has been cached.
| [GetAllUniqueRoleAssignments(Web, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.DAA2E7F4.md) | Get all unique role assignments for a web object and all its descendents down to document or list item level.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
