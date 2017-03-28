# ListInstance
This class holds deprecated ListInstance properties and methods  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class ListInstance: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ListInstance()](ListInstanceconstructor1details.md) | 
| [ListInstance(Collections.Generic.IEnumerable1<ContentTypeBinding>, Collections.Generic.IEnumerable1<View>, Collections.Generic.IEnumerable1<Field>, Collections.Generic.IEnumerable1<FieldRef>, Collections.Generic.List1<DataRow>)](ListInstanceconstructor1details.md) | 
| [ListInstance(Collections.Generic.IEnumerable1<ContentTypeBinding>, Collections.Generic.IEnumerable1<View>, Collections.Generic.IEnumerable1<Field>, Collections.Generic.IEnumerable1<FieldRef>, Collections.Generic.List1<DataRow>, Collections.Generic.Dictionary2<String,String>, ObjectSecurity)](ListInstanceconstructor1details.md) | 
| [ListInstance(Collections.Generic.IEnumerable1<ContentTypeBinding>, Collections.Generic.IEnumerable1<View>, Collections.Generic.IEnumerable1<Field>, Collections.Generic.IEnumerable1<FieldRef>, Collections.Generic.List1<DataRow>, Collections.Generic.Dictionary2<String,String>, ObjectSecurity, Collections.Generic.List1<Folder>)](ListInstanceconstructor1details.md) | 
| [ListInstance(Collections.Generic.IEnumerable1<ContentTypeBinding>, Collections.Generic.IEnumerable1<View>, Collections.Generic.IEnumerable1<Field>, Collections.Generic.IEnumerable1<FieldRef>, Collections.Generic.List1<DataRow>, Collections.Generic.Dictionary2<String,String>, ObjectSecurity, Collections.Generic.List1<Folder>, Collections.Generic.List1<CustomAction>)](ListInstanceconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Title](ListInstance.Title.md) | Gets or sets the list title
| [Description](ListInstance.Description.md) | Gets or sets the description of the list
| [DocumentTemplate](ListInstance.DocumentTemplate.md) | Gets or sets a value that specifies the identifier of the document template for the new list.
| [OnQuickLaunch](ListInstance.OnQuickLaunch.md) | Gets or sets a value that specifies whether the new list is displayed on the Quick Launch of the site.
| [TemplateType](ListInstance.TemplateType.md) | Gets or sets a value that specifies the list server template of the new list.
            https://msdn.microsoft.com/en-us/library/office/microsoft.sharepoint.client.listtemplatetype.aspx
| [Url](ListInstance.Url.md) | Gets or sets a value that specifies whether the new list is displayed on the Quick Launch of the site.
| [EnableVersioning](ListInstance.EnableVersioning.md) | Gets or sets whether verisioning is enabled on the list
| [EnableMinorVersions](ListInstance.EnableMinorVersions.md) | Gets or sets whether minor verisioning is enabled on the list
| [DraftVersionVisibility](ListInstance.DraftVersionVisibility.md) | Gets or sets the DraftVersionVisibility for the list
| [EnableModeration](ListInstance.EnableModeration.md) | Gets or sets whether moderation/content approval is enabled on the list
| [MinorVersionLimit](ListInstance.MinorVersionLimit.md) | Gets or sets the MinorVersionLimit  for versioning, just in case it is enabled on the list
| [MaxVersionLimit](ListInstance.MaxVersionLimit.md) | Gets or sets the MinorVersionLimit  for verisioning, just in case it is enabled on the list
| [RemoveExistingContentTypes](ListInstance.RemoveExistingContentTypes.md) | Gets or sets whether existing content types should be removed
| [RemoveExistingViews](ListInstance.RemoveExistingViews.md) | Gets or sets whether existing views should be removed
| [ContentTypesEnabled](ListInstance.ContentTypesEnabled.md) | Gets or sets whether content types are enabled
| [Hidden](ListInstance.Hidden.md) | Gets or sets whether to hide the list
| [ForceCheckout](ListInstance.ForceCheckout.md) | Gets or sets whether to force checkout of documents in the library
| [EnableAttachments](ListInstance.EnableAttachments.md) | Gets or sets whether attachments are enabled. Defaults to true.
| [EnableFolderCreation](ListInstance.EnableFolderCreation.md) | Gets or sets whether folder is enabled. Defaults to true.
| [ContentTypeBindings](ListInstance.ContentTypeBindings.md) | Gets or sets the content types to associate to the list
| [Views](ListInstance.Views.md) | Gets or sets the content types to associate to the list
| [Fields](ListInstance.Fields.md) | 
| [FieldRefs](ListInstance.FieldRefs.md) | 
| [TemplateFeatureID](ListInstance.TemplateFeatureID.md) | 
| [DataRows](ListInstance.DataRows.md) | 
| [FieldDefaults](ListInstance.FieldDefaults.md) | Defines a list of default values for the Fields of the List Instance
| [Security](ListInstance.Security.md) | Defines the Security rules for the List Instance
| [Folders](ListInstance.Folders.md) | Defines a collection of folders (eventually nested) that 
            will be provisioned into the target list/library
| [UserCustomActions](ListInstance.UserCustomActions.md) | Defines a collection of user custom actions that 
            will be provisioned into the target list/library
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](ListInstanceGetHashCode.md) | 
| [Equals(Object)](ListInstanceEqualsObject.md) | 
| [Equals(ListInstance)](ListInstanceEqualsListInstance.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
