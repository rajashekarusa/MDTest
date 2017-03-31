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
| [AzureStorageConnector()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.ctor1.md) | 
| [AzureStorageConnector(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.ctor2.md) | 
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [GetFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.1EF203BB.md) | Get the files available in the default container
| [GetFiles(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.349A20D0.md) | Get the files available in the specified container
| [GetFolders()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.183FC5F5.md) | Get the folders of the default container
| [GetFolders(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.C388CAF.md) | Get the folders of a specified container
| [GetFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.DF261957.md) | Gets a file as string from the default container
| [GetFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.7AD54AAC.md) | Gets a file as string from the specified container
| [GetFileStream(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.667E64B2.md) | Gets a file as stream from the default container
| [GetFileStream(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.E43BB5.md) | Gets a file as stream from the specified container
| [SaveFileStream(String, Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.3B54D26B.md) | Saves a stream to the default container with the given name. If the file exists it will be overwritten
| [SaveFileStream(String, String, Stream)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.EC95A2C1.md) | Saves a stream to the specified container with the given name. If the file exists it will be overwritten
| [DeleteFile(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.9AD8ACAF.md) | Deletes a file from the default container
| [DeleteFile(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.476DD1F3.md) | Deletes a file from the specified container
| [GetFilenamePart(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.9E3B826.md) | 
| [Initialize()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.97690B88.md) | 
| [GetFileFromStorage(String, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.963D6687.md) | 
| [ParseContainer(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.AzureStorageConnector.426FBF0A.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors](OfficeDevPnP.Core.Framework.Provisioning.Connectors.md)
