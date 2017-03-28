# ProvisioningExtensions
File-based (CAML) deprecated provisioning extensions  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class ProvisioningExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ProvisionElementFile(Web, String)](ProvisioningExtensionsProvisionElementFileWebString.md) | Provisions the items defined by the specified Elements (CAML) file; currently only supports modules (files).
| [ProvisionElementXml(Web, String, Xml.Linq.XElement)](ProvisioningExtensionsProvisionElementXmlWebStringXml.Linq.XElement.md) | Provisions the items defined by the specified Elements (CAML) XML; currently only supports modules (files).
| [ProvisionModuleInternal(Web, String, Xml.Linq.XElement)](ProvisioningExtensionsProvisionModuleInternalWebStringXml.Linq.XElement.md) | Uploads all files defined by the moduleXml
| [ProvisionFileInternal(Web, String, String, Xml.Linq.XElement, Boolean)](ProvisioningExtensionsProvisionFileInternalWebStringStringXml.Linq.XElementBoolean.md) | Uploads the file defined by the fileXml, creating folders as necessary.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
