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
| [GetAdministrators(Web)](Microsoft.SharePoint.Client.SecurityExtensions.GetAdministratorsWeb.md) | Get a list of site collection administrators
| [AddAdministrators(Web, Collections.Generic.List<OfficeDevPnP.Core.Entities.UserEntity>, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddAdministratorsWebCollections.Generic.List<OfficeDevPnP.Core.Entities.UserEntity>Boolean.md) | 
| [RemoveAdministrator(Web, OfficeDevPnP.Core.Entities.UserEntity)](Microsoft.SharePoint.Client.SecurityExtensions.RemoveAdministratorWebOfficeDevPnP.Core.Entities.UserEntity.md) | Removes an administrators from the site collection
| [AddReaderAccess(Web)](Microsoft.SharePoint.Client.SecurityExtensions.AddReaderAccessWeb.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccess(Web, OfficeDevPnP.Core.Enums.BuiltInIdentity)](Microsoft.SharePoint.Client.SecurityExtensions.AddReaderAccessWebOfficeDevPnP.Core.Enums.BuiltInIdentity.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccessImplementation(Web, OfficeDevPnP.Core.Enums.BuiltInIdentity)](Microsoft.SharePoint.Client.SecurityExtensions.AddReaderAccessImplementationWebOfficeDevPnP.Core.Enums.BuiltInIdentity.md) | 
| [GetSharingCapabilitiesTenant(Web, Uri)](Microsoft.SharePoint.Client.SecurityExtensions.GetSharingCapabilitiesTenantWebUri.md) | Get the external sharing settings for the provided site. Only works in Office 365 Multi-Tenant
| [GetExternalUsersTenant(Web)](Microsoft.SharePoint.Client.SecurityExtensions.GetExternalUsersTenantWeb.md) | Returns a list all external users in your tenant
| [GetExternalUsersForSiteTenant(Web, Uri)](Microsoft.SharePoint.Client.SecurityExtensions.GetExternalUsersForSiteTenantWebUri.md) | Returns a list all external users for a given site that have at least the viewpages permission
| [GetGroupID(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.GetGroupIDWebString.md) | Returns the integer ID for a given group name
| [AddGroup(Web, String, String, Boolean, Boolean, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddGroupWebStringStringBooleanBooleanBoolean.md) | Adds a group
| [AssociateDefaultGroups(Web, Group, Group, Group)](Microsoft.SharePoint.Client.SecurityExtensions.AssociateDefaultGroupsWebGroupGroupGroup.md) | Associate the provided groups as default owners, members or visitors groups. If a group is null then the association is not done
| [AddUserToGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.AddUserToGroupWebStringString.md) | Adds a user to a group
| [AddUserToGroup(Web, Int32, String)](Microsoft.SharePoint.Client.SecurityExtensions.AddUserToGroupWebInt32String.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, User)](Microsoft.SharePoint.Client.SecurityExtensions.AddUserToGroupWebGroupUser.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, String)](Microsoft.SharePoint.Client.SecurityExtensions.AddUserToGroupWebGroupString.md) | Adds a user to a group
| [AddPermissionLevelToUser(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToUserSecurableObjectStringRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a user
| [AddPermissionLevelToUser(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToUserSecurableObjectStringStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a user
| [AddPermissionLevelToGroup(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToGroupSecurableObjectStringRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToPrincipalSecurableObjectPrincipalRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToGroup(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToGroupSecurableObjectStringStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelToPrincipalSecurableObjectPrincipalStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.AddPermissionLevelImplementationSecurableObjectPrincipalRoleDefinitionBoolean.md) | 
| [RemovePermissionLevelFromUser(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromUserSecurableObjectStringRoleTypeBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromPrincipalSecurableObjectPrincipalRoleTypeBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromUser(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromUserSecurableObjectStringStringBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromPrincipalSecurableObjectPrincipalStringBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromGroup(SecurableObject, String, RoleType, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromGroupSecurableObjectStringRoleTypeBoolean.md) | Removes a permission level from a group
| [RemovePermissionLevelFromGroup(SecurableObject, String, String, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelFromGroupSecurableObjectStringStringBoolean.md) | Removes a permission level from a group
| [RemovePermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](Microsoft.SharePoint.Client.SecurityExtensions.RemovePermissionLevelImplementationSecurableObjectPrincipalRoleDefinitionBoolean.md) | 
| [GetAssociatedWeb(SecurableObject)](Microsoft.SharePoint.Client.SecurityExtensions.GetAssociatedWebSecurableObject.md) | 
| [RemoveUserFromGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.RemoveUserFromGroupWebStringString.md) | Removes a user from a group
| [RemoveUserFromGroup(Web, Group, User)](Microsoft.SharePoint.Client.SecurityExtensions.RemoveUserFromGroupWebGroupUser.md) | Removes a user from a group
| [RemoveGroup(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.RemoveGroupWebString.md) | Remove a group
| [RemoveGroup(Web, Group)](Microsoft.SharePoint.Client.SecurityExtensions.RemoveGroupWebGroup.md) | Remove a group
| [IsUserInGroup(Web, String, String)](Microsoft.SharePoint.Client.SecurityExtensions.IsUserInGroupWebStringString.md) | Checks if a user is member of a group
| [GroupExists(Web, String)](Microsoft.SharePoint.Client.SecurityExtensions.GroupExistsWebString.md) | Checks if a group exists
| [IsGroupCannotBeFoundException(Exception)](Microsoft.SharePoint.Client.SecurityExtensions.IsGroupCannotBeFoundExceptionException.md) | 
| [GetAuthenticationRealm(Web)](Microsoft.SharePoint.Client.SecurityExtensions.GetAuthenticationRealmWeb.md) | Returns the authentication realm for the current web
| [GetPath(SecurableObject)](Microsoft.SharePoint.Client.SecurityExtensions.GetPathSecurableObject.md) | Get URL path of a securable object
| [Preload(SecurableObject, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.PreloadSecurableObjectInt32.md) | Load properties of the current securable object and get child securable objects with unique role assignments if any.
| [Visit(SecurableObject, Int32, Action<SecurableObject,String>)](Microsoft.SharePoint.Client.SecurityExtensions.VisitSecurableObjectInt32Action<SecurableObject,String>.md) | 
| [GetUserEmail(Web, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.GetUserEmailWebInt32.md) | Get user email by user id.
| [EnsureGroupCache(SecurableObject, String)](Microsoft.SharePoint.Client.SecurityExtensions.EnsureGroupCacheSecurableObjectString.md) | Ensure all users of a given SharePoint group has been cached.
| [GetAllUniqueRoleAssignments(Web, Int32)](Microsoft.SharePoint.Client.SecurityExtensions.GetAllUniqueRoleAssignmentsWebInt32.md) | Get all unique role assignments for a web object and all its descendents down to document or list item level.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
