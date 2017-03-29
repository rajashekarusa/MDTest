# SharePointConnector
Connector for files in SharePoint  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class SharePointConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [SharePointConnector()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.Constructor1details.md) | 
| [SharePointConnector(ClientRuntimeContext, String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.Constructor2details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFiles.md) | Get the files available in the default container
| [GetFiles(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFilesString.md) | Get the files available in the specified container
| [GetFolders()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFolders.md) | Get the folders of the default container
| [GetFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileString.md) | Gets a file as string from the default container
| [GetFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.SaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.SaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.DeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.DeleteFileStringString.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFilenamePartString.md) | 
| [GetFileServerRelativeUrl(Microsoft.SharePoint.Client.ClientContext, String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileServerRelativeUrlMicrosoft.SharePoint.Client.ClientContextStringString.md) | 
| [GetFileFromStorage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetFileFromStorageStringString.md) | 
| [GetDocumentLibrary(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetDocumentLibraryString.md) | 
| [GetUrlFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetUrlFoldersString.md) | 
| [GetClientContext()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetClientContext.md) | 
| [GetContainer()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.SharePointConnector.GetContainer.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
