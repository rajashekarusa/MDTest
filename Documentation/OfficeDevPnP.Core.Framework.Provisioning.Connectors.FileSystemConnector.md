# FileSystemConnector
Connector for files in file system
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class FileSystemConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [FileSystemConnector()](FileSystemConnectorconstructor1details.md) | 
| [FileSystemConnector(String, String)](FileSystemConnectorconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](FileSystemConnectorGetFiles.md) | Get the files available in the default container
| [GetFiles(String)](FileSystemConnectorGetFilesString.md) | Get the files available in the specified container
| [GetFolders()](FileSystemConnectorGetFolders.md) | Get the folders of the default container
| [GetFolders(String)](FileSystemConnectorGetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](FileSystemConnectorGetFileString.md) | Gets a file as string from the default container
| [GetFilenamePart(String)](FileSystemConnectorGetFilenamePartString.md) | 
| [GetFile(String, String)](FileSystemConnectorGetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](FileSystemConnectorGetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](FileSystemConnectorGetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](FileSystemConnectorSaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](FileSystemConnectorSaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](FileSystemConnectorDeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](FileSystemConnectorDeleteFileStringString.md) | Deletes a file from the specified container
| [GetFileFromStorage(String, String)](FileSystemConnectorGetFileFromStorageStringString.md) | 
| [ConstructPath(String, String)](FileSystemConnectorConstructPathStringString.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
