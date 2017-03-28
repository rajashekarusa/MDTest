# Directory
Defines a Directory element, to describe a folder in the current 
            repository that will be used to upload files into the target Site  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel](OfficeDevPnP.Core.Framework.Provisioning.Model.BaseModel.md)
## Syntax
```C#
public class Directory: BaseModel
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [Directory()](Directoryconstructor1details.md) | 
| [Directory(String, String, Boolean, FileLevel, Boolean, String, String, String, ObjectSecurity)](Directoryconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Src](Directory.Src.md) | The Src of the Directory
| [Folder](Directory.Folder.md) | The TargetFolder of the Directory
| [Overwrite](Directory.Overwrite.md) | The Overwrite flag for the files in the Directory
| [Level](Directory.Level.md) | The Level status for the files in the Directory
| [Recursive](Directory.Recursive.md) | Defines whether to recursively browse through all the child folders of the Directory
| [IncludedExtensions](Directory.IncludedExtensions.md) | The file Extensions to include while uploading the Directory
| [ExcludedExtensions](Directory.ExcludedExtensions.md) | The file Extensions to exclude while uploading the Directory
| [MetadataMappingFile](Directory.MetadataMappingFile.md) | The file path of JSON mapping file with metadata for files to upload in the Directory
| [Security](Directory.Security.md) | Defines the Security rules for the File
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetHashCode()](DirectoryGetHashCode.md) | 
| [Equals(Object)](DirectoryEqualsObject.md) | 
| [Equals(Directory)](DirectoryEqualsDirectory.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Model](OfficeDevPnP.Core.Framework.Provisioning.Model.md)
