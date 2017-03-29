# AzureStorageConnector
Connector for files in Azure blob storage  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class AzureStorageConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [AzureStorageConnector()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.Constructor1details.md) | 
| [AzureStorageConnector(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.Constructor2details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFiles.md) | Get the files available in the default container
| [GetFiles(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFilesString.md) | Get the files available in the specified container
| [GetFolders()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFolders.md) | Get the folders of the default container
| [GetFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFileString.md) | Gets a file as string from the default container
| [GetFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.SaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.SaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.DeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.DeleteFileStringString.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFilenamePartString.md) | 
| [Initialize()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.Initialize.md) | 
| [GetFileFromStorage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.GetFileFromStorageStringString.md) | 
| [ParseContainer(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.ParseContainerString.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
