# AzureStorageConnector
Connector for files in Azure blob storage
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class AzureStorageConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [AzureStorageConnector()](AzureStorageConnectorconstructor1details.md) | 
| [AzureStorageConnector(String, String)](AzureStorageConnectorconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](AzureStorageConnectorGetFiles.md) | Get the files available in the default container
| [GetFiles(String)](AzureStorageConnectorGetFilesString.md) | Get the files available in the specified container
| [GetFolders()](AzureStorageConnectorGetFolders.md) | Get the folders of the default container
| [GetFolders(String)](AzureStorageConnectorGetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](AzureStorageConnectorGetFileString.md) | Gets a file as string from the default container
| [GetFile(String, String)](AzureStorageConnectorGetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](AzureStorageConnectorGetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](AzureStorageConnectorGetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](AzureStorageConnectorSaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](AzureStorageConnectorSaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](AzureStorageConnectorDeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](AzureStorageConnectorDeleteFileStringString.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](AzureStorageConnectorGetFilenamePartString.md) | 
| [Initialize()](AzureStorageConnectorInitialize.md) | 
| [GetFileFromStorage(String, String)](AzureStorageConnectorGetFileFromStorageStringString.md) | 
| [ParseContainer(String)](AzureStorageConnectorParseContainerString.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
