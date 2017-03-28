# ContentType
  
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class ContentType: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [ContentType()](ContentTypeconstructor1details.md) | 
| [ContentType(String, String, String, String, Boolean, Boolean, Boolean, String, Boolean, Collections.Generic.IEnumerable1<FieldRef>)](ContentTypeconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Id](ContentType.Id.md) | The Id of the Content Type
| [Name](ContentType.Name.md) | The name of the Content Type
| [Description](ContentType.Description.md) | The description of the Content Type
| [Group](ContentType.Group.md) | The group name of the content type
| [FieldRefs](ContentType.FieldRefs.md) | The FieldRefs entries of the List Instance
| [Hidden](ContentType.Hidden.md) | True to define the content type as hidden. If you define a content type as hidden, SharePoint Foundation does not display that content type on the New button in list views.
| [Sealed](ContentType.Sealed.md) | True to prevent changes to this content type. You cannot change the value of this attribute through the user interface, but you can change it in code if you have sufficient rights. You must have site collection administrator rights to unseal a content type.
| [ReadOnly](ContentType.ReadOnly.md) | True to specify that the content type cannot be edited without explicitly removing the read-only setting. This can be done either in the user interface or in code.
| [Overwrite](ContentType.Overwrite.md) | True to overwrite an existing content type with the same ID.
| [DocumentTemplate](ContentType.DocumentTemplate.md) | Specifies the document template for the content type
| [DocumentSetTemplate](ContentType.DocumentSetTemplate.md) | Specifies the properties of the DocumentSet Template if the ContentType defines a DocumentSet
| [DisplayFormUrl](ContentType.DisplayFormUrl.md) | Specifies the URL of a custom display form to use for list items that have been assigned the content type
| [EditFormUrl](ContentType.EditFormUrl.md) | Specifies the URL of a custom edit form to use for list items that have been assigned the content type
| [NewFormUrl](ContentType.NewFormUrl.md) | Specifies the URL of a custom new form to use for list items that have been assigned the content type
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](ContentTypeGetHashCode.md) | 
| [Equals(Object)](ContentTypeEqualsObject.md) | 
| [Equals(ContentType)](ContentTypeEqualsContentType.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
