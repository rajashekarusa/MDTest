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
| [OpenXMLConnector(Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.ctor1.md) | 
| [OpenXMLConnector(String, FileConnectorBase, String, X509Certificate2)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.ctor2.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.1EF203BB.md) | Get the files available in the default container
| [GetFiles(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.349A20D0.md) | Get the files available in the specified container
| [GetFolders()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.183FC5F5.md) | Get the folders of the default container
| [GetFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.C388CAF.md) | Get the folders of a specified container
| [GetFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.DF261957.md) | Gets a file as string from the default container
| [GetFilenamePart(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.9E3B826.md) | 
| [GetFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.7AD54AAC.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.667E64B2.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.E43BB5.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.3B54D26B.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.EC95A2C1.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.9AD8ACAF.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.476DD1F3.md) | Deletes a file from the specified container
| [GetFileFromStorage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.963D6687.md) | 
| [GetFileFromInsidePackage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.40EF1725.md) | Will first try to find the file based on container/filename from the mapped file names. As a fallback it will try to find by container/filename in the pnp file structure, which was the original format.
| [GetContainer()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.CDDE79F5.md) | 
| [Commit()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.17C9D8E5.md) | 
| [<GetFileFromInsidePackage>b__19_1(KeyValuePair<String, String>)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXMLConnector.270336.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
