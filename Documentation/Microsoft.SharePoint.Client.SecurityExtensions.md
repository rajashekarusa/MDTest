# SecurityExtensions
This manager class holds deprecated security related methods  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class SecurityExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetAdministrators(Web)](SecurityExtensionsGetAdministratorsWeb.md) | Get a list of site collection administrators
| [AddAdministrators(Web, Collections.Generic.List1<OfficeDevPnP.Core.Entities.UserEntity>, Boolean)](SecurityExtensionsAddAdministratorsWebCollections.Generic.List1<OfficeDevPnP.Core.Entities.UserEntity>Boolean.md) | 
| [RemoveAdministrator(Web, OfficeDevPnP.Core.Entities.UserEntity)](SecurityExtensionsRemoveAdministratorWebOfficeDevPnP.Core.Entities.UserEntity.md) | Removes an administrators from the site collection
| [AddReaderAccess(Web)](SecurityExtensionsAddReaderAccessWeb.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccess(Web, OfficeDevPnP.Core.Enums.BuiltInIdentity)](SecurityExtensionsAddReaderAccessWebOfficeDevPnP.Core.Enums.BuiltInIdentity.md) | Add read access to the group "Everyone except external users".
| [AddReaderAccessImplementation(Web, OfficeDevPnP.Core.Enums.BuiltInIdentity)](SecurityExtensionsAddReaderAccessImplementationWebOfficeDevPnP.Core.Enums.BuiltInIdentity.md) | 
| [GetSharingCapabilitiesTenant(Web, Uri)](SecurityExtensionsGetSharingCapabilitiesTenantWebUri.md) | Get the external sharing settings for the provided site. Only works in Office 365 Multi-Tenant
| [GetExternalUsersTenant(Web)](SecurityExtensionsGetExternalUsersTenantWeb.md) | Returns a list all external users in your tenant
| [GetExternalUsersForSiteTenant(Web, Uri)](SecurityExtensionsGetExternalUsersForSiteTenantWebUri.md) | Returns a list all external users for a given site that have at least the viewpages permission
| [GetGroupID(Web, String)](SecurityExtensionsGetGroupIDWebString.md) | Returns the integer ID for a given group name
| [AddGroup(Web, String, String, Boolean, Boolean, Boolean)](SecurityExtensionsAddGroupWebStringStringBooleanBooleanBoolean.md) | Adds a group
| [AssociateDefaultGroups(Web, Group, Group, Group)](SecurityExtensionsAssociateDefaultGroupsWebGroupGroupGroup.md) | Associate the provided groups as default owners, members or visitors groups. If a group is null then the association is not done
| [AddUserToGroup(Web, String, String)](SecurityExtensionsAddUserToGroupWebStringString.md) | Adds a user to a group
| [AddUserToGroup(Web, Int32, String)](SecurityExtensionsAddUserToGroupWebInt32String.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, User)](SecurityExtensionsAddUserToGroupWebGroupUser.md) | Adds a user to a group
| [AddUserToGroup(Web, Group, String)](SecurityExtensionsAddUserToGroupWebGroupString.md) | Adds a user to a group
| [AddPermissionLevelToUser(SecurableObject, String, RoleType, Boolean)](SecurityExtensionsAddPermissionLevelToUserSecurableObjectStringRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a user
| [AddPermissionLevelToUser(SecurableObject, String, String, Boolean)](SecurityExtensionsAddPermissionLevelToUserSecurableObjectStringStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a user
| [AddPermissionLevelToGroup(SecurableObject, String, RoleType, Boolean)](SecurityExtensionsAddPermissionLevelToGroupSecurableObjectStringRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, RoleType, Boolean)](SecurityExtensionsAddPermissionLevelToPrincipalSecurableObjectPrincipalRoleTypeBoolean.md) | Add a permission level (e.g.Contribute, Reader,...) to a group
| [AddPermissionLevelToGroup(SecurableObject, String, String, Boolean)](SecurityExtensionsAddPermissionLevelToGroupSecurableObjectStringStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelToPrincipal(SecurableObject, Principal, String, Boolean)](SecurityExtensionsAddPermissionLevelToPrincipalSecurableObjectPrincipalStringBoolean.md) | Add a role definition (e.g.Contribute, Read, Approve) to a group
| [AddPermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](SecurityExtensionsAddPermissionLevelImplementationSecurableObjectPrincipalRoleDefinitionBoolean.md) | 
| [RemovePermissionLevelFromUser(SecurableObject, String, RoleType, Boolean)](SecurityExtensionsRemovePermissionLevelFromUserSecurableObjectStringRoleTypeBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, RoleType, Boolean)](SecurityExtensionsRemovePermissionLevelFromPrincipalSecurableObjectPrincipalRoleTypeBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromUser(SecurableObject, String, String, Boolean)](SecurityExtensionsRemovePermissionLevelFromUserSecurableObjectStringStringBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromPrincipal(SecurableObject, Principal, String, Boolean)](SecurityExtensionsRemovePermissionLevelFromPrincipalSecurableObjectPrincipalStringBoolean.md) | Removes a permission level from a user
| [RemovePermissionLevelFromGroup(SecurableObject, String, RoleType, Boolean)](SecurityExtensionsRemovePermissionLevelFromGroupSecurableObjectStringRoleTypeBoolean.md) | Removes a permission level from a group
| [RemovePermissionLevelFromGroup(SecurableObject, String, String, Boolean)](SecurityExtensionsRemovePermissionLevelFromGroupSecurableObjectStringStringBoolean.md) | Removes a permission level from a group
| [RemovePermissionLevelImplementation(SecurableObject, Principal, RoleDefinition, Boolean)](SecurityExtensionsRemovePermissionLevelImplementationSecurableObjectPrincipalRoleDefinitionBoolean.md) | 
| [GetAssociatedWeb(SecurableObject)](SecurityExtensionsGetAssociatedWebSecurableObject.md) | 
| [RemoveUserFromGroup(Web, String, String)](SecurityExtensionsRemoveUserFromGroupWebStringString.md) | Removes a user from a group
| [RemoveUserFromGroup(Web, Group, User)](SecurityExtensionsRemoveUserFromGroupWebGroupUser.md) | Removes a user from a group
| [RemoveGroup(Web, String)](SecurityExtensionsRemoveGroupWebString.md) | Remove a group
| [RemoveGroup(Web, Group)](SecurityExtensionsRemoveGroupWebGroup.md) | Remove a group
| [IsUserInGroup(Web, String, String)](SecurityExtensionsIsUserInGroupWebStringString.md) | Checks if a user is member of a group
| [GroupExists(Web, String)](SecurityExtensionsGroupExistsWebString.md) | Checks if a group exists
| [IsGroupCannotBeFoundException(Exception)](SecurityExtensionsIsGroupCannotBeFoundExceptionException.md) | 
| [GetAuthenticationRealm(Web)](SecurityExtensionsGetAuthenticationRealmWeb.md) | Returns the authentication realm for the current web
| [GetPath(SecurableObject)](SecurityExtensionsGetPathSecurableObject.md) | Get URL path of a securable object
| [Preload(SecurableObject, Int32)](SecurityExtensionsPreloadSecurableObjectInt32.md) | Load properties of the current securable object and get child securable objects with unique role assignments if any.
| [Visit(SecurableObject, Int32, Action2<SecurableObject,String>)](SecurityExtensionsVisitSecurableObjectInt32Action2<SecurableObject,String>.md) | 
| [GetUserEmail(Web, Int32)](SecurityExtensionsGetUserEmailWebInt32.md) | Get user email by user id.
| [EnsureGroupCache(SecurableObject, String)](SecurityExtensionsEnsureGroupCacheSecurableObjectString.md) | Ensure all users of a given SharePoint group has been cached.
| [GetAllUniqueRoleAssignments(Web, Int32)](SecurityExtensionsGetAllUniqueRoleAssignmentsWebInt32.md) | Get all unique role assignments for a web object and all its descendents down to document or list item level.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
