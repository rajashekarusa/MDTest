# FileConnectorBase
Base file connector class  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class FileConnectorBase
```
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Parameters](FileConnectorBase.Parameters.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](FileConnectorBaseGetFiles.md) | Get the files available in the default container
| [GetFiles(String)](FileConnectorBaseGetFilesString.md) | Get the files available in the specified container
| [GetFolders()](FileConnectorBaseGetFolders.md) | Get the folders of the default container
| [GetFolders(String)](FileConnectorBaseGetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](FileConnectorBaseGetFileString.md) | Gets a file as string from the default container
| [GetFile(String, String)](FileConnectorBaseGetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](FileConnectorBaseGetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](FileConnectorBaseGetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](FileConnectorBaseSaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](FileConnectorBaseSaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](FileConnectorBaseDeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](FileConnectorBaseDeleteFileStringString.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](FileConnectorBaseGetFilenamePartString.md) | Returns a filename without a path
| [AddParameterAsString(String, String)](FileConnectorBaseAddParameterAsStringStringString.md) | 
| [AddParameter(String, Object)](FileConnectorBaseAddParameterStringObject.md) | 
| [GetConnectionString()](FileConnectorBaseGetConnectionString.md) | 
| [GetContainer()](FileConnectorBaseGetContainer.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
