# OpenXMLConnector
Connector that stores all the files into a unique .PNP OpenXML package  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
-- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase](OfficeDevPnP.Core.Framework.Provisioning.Connectors.FileConnectorBase.md)
## Syntax
```C#
public class OpenXMLConnector: FileConnectorBase
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [OpenXMLConnector(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.Constructor1details.md) | 
| [OpenXMLConnector(String, FileConnectorBase, String, X509Certificate2)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.Constructor2details.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFiles.md) | Get the files available in the default container
| [GetFiles(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFilesString.md) | Get the files available in the specified container
| [GetFolders()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFolders.md) | Get the folders of the default container
| [GetFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFoldersString.md) | Get the folders of a specified container
| [GetFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileString.md) | Gets a file as string from the default container
| [GetFilenamePart(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFilenamePartString.md) | 
| [GetFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileStringString.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileStreamString.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileStreamStringString.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.SaveFileStreamStringIO.Stream.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, IO.Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.SaveFileStreamStringStringIO.Stream.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.DeleteFileString.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.DeleteFileStringString.md) | Deletes a file from the specified container
| [GetFileFromStorage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileFromStorageStringString.md) | 
| [GetFileFromInsidePackage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetFileFromInsidePackageStringString.md) | Will first try to find the file based on container/filename from the mapped file names. As a fallback it will try to find by container/filename in the pnp file structure, which was the original format.
| [GetContainer()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.GetContainer.md) | 
| [Commit()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.Commit.md) | 
| [<GetFileFromInsidePackage>b__19_1(Collections.Generic.KeyValuePair<String,String>)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.<GetFileFromInsidePackage>b__19_1Collections.Generic.KeyValuePair<String,String>.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
