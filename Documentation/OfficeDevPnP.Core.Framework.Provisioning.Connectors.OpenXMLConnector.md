# OpenXMLConnector
Connector that stores all the files into a unique .PNP OpenXML package  
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class OpenXMLConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [OpenXMLConnector(IO.Stream)](OpenXMLConnectorconstructor1details.md) | 
| [OpenXMLConnector(String, FileConnectorBase, String, Security.Cryptography.X509Certificates.X509Certificate2)](OpenXMLConnectorconstructor1details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OpenXMLConnectorGetFiles.md) | Get the files available in the default container
| [GetFiles(String)](OpenXMLConnectorGetFilesString.md) | Get the files available in the specified container
| [GetFolders()](OpenXMLConnectorGetFolders.md) | Get the folders of the default container
| [GetFolders(String)](OpenXMLConnectorGetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](OpenXMLConnectorGetFileString.md) | Gets a file as string from the default container
| [GetFilenamePart(String)](OpenXMLConnectorGetFilenamePartString.md) | 
| [GetFile(String, String)](OpenXMLConnectorGetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OpenXMLConnectorGetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OpenXMLConnectorGetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](OpenXMLConnectorSaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](OpenXMLConnectorSaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OpenXMLConnectorDeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OpenXMLConnectorDeleteFileStringString.md) | Deletes a file from the specified container
| [GetFileFromStorage(String, String)](OpenXMLConnectorGetFileFromStorageStringString.md) | 
| [GetFileFromInsidePackage(String, String)](OpenXMLConnectorGetFileFromInsidePackageStringString.md) | Will first try to find the file based on container/filename from the mapped file names. As a fallback it will try to find by container/filename in the pnp file structure, which was the original format.
| [GetContainer()](OpenXMLConnectorGetContainer.md) | 
| [Commit()](OpenXMLConnectorCommit.md) | 
| [<GetFileFromInsidePackage>b__19_1(Collections.Generic.KeyValuePair2<String,String>)](OpenXMLConnector<GetFileFromInsidePackage>b__19_1Collections.Generic.KeyValuePair2<String,String>.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
