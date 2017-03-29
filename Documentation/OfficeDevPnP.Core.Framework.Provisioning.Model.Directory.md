# Directory
Defines a Directory element, to describe a folder in the current 
            repository that will be used to upload files into the target Site  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class Directory: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [Directory()](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Constructor1details.md) | 
| [Directory(String, String, Boolean, FileLevel, Boolean, String, String, String, ObjectSecurity)](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Constructor2details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Src](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Src.md) | The Src of the Directory
| [Folder](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Folder.md) | The TargetFolder of the Directory
| [Overwrite](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Overwrite.md) | The Overwrite flag for the files in the Directory
| [Level](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Level.md) | The Level status for the files in the Directory
| [Recursive](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Recursive.md) | Defines whether to recursively browse through all the child folders of the Directory
| [IncludedExtensions](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.IncludedExtensions.md) | The file Extensions to include while uploading the Directory
| [ExcludedExtensions](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.ExcludedExtensions.md) | The file Extensions to exclude while uploading the Directory
| [MetadataMappingFile](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.MetadataMappingFile.md) | The file path of JSON mapping file with metadata for files to upload in the Directory
| [Security](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.Security.md) | Defines the Security rules for the File
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.GetHashCode.md) | 
| [Equals(Object)](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.EqualsObject.md) | 
| [Equals(Directory)](OfficeDevPnP.Core.Framework.Provisioning.Model.Directory.EqualsDirectory.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
