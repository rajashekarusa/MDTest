# SharePointConnector
Connector for files in SharePoint  
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class SharePointConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [SharePointConnector()](SharePointConnectorconstructor1details.md) | 
| [SharePointConnector(Microsoft.SharePoint.Client.ClientRuntimeContext, String, String)](SharePointConnectorconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](SharePointConnectorGetFiles.md) | Get the files available in the default container
| [GetFiles(String)](SharePointConnectorGetFilesString.md) | Get the files available in the specified container
| [GetFolders()](SharePointConnectorGetFolders.md) | Get the folders of the default container
| [GetFolders(String)](SharePointConnectorGetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](SharePointConnectorGetFileString.md) | Gets a file as string from the default container
| [GetFile(String, String)](SharePointConnectorGetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](SharePointConnectorGetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](SharePointConnectorGetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](SharePointConnectorSaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](SharePointConnectorSaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](SharePointConnectorDeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](SharePointConnectorDeleteFileStringString.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](SharePointConnectorGetFilenamePartString.md) | 
| [GetFileServerRelativeUrl(Microsoft.SharePoint.Client.ClientContext, String, String)](SharePointConnectorGetFileServerRelativeUrlMicrosoft.SharePoint.Client.ClientContextStringString.md) | 
| [GetFileFromStorage(String, String)](SharePointConnectorGetFileFromStorageStringString.md) | 
| [GetDocumentLibrary(String)](SharePointConnectorGetDocumentLibraryString.md) | 
| [GetUrlFolders(String)](SharePointConnectorGetUrlFoldersString.md) | 
| [GetClientContext()](SharePointConnectorGetClientContext.md) | 
| [GetContainer()](SharePointConnectorGetContainer.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
