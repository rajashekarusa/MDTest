# ProvisioningExtensions
File-based (CAML) deprecated provisioning extensions  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class ProvisioningExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ProvisionElementFile(Web, String)](Microsoft.SharePoint.Client.ProvisioningExtensions.ProvisionElementFileWebString.md) | Provisions the items defined by the specified Elements (CAML) file; currently only supports modules (files).
| [ProvisionElementXml(Web, String, Xml.Linq.XElement)](Microsoft.SharePoint.Client.ProvisioningExtensions.ProvisionElementXmlWebStringXml.Linq.XElement.md) | Provisions the items defined by the specified Elements (CAML) XML; currently only supports modules (files).
| [ProvisionModuleInternal(Web, String, Xml.Linq.XElement)](Microsoft.SharePoint.Client.ProvisioningExtensions.ProvisionModuleInternalWebStringXml.Linq.XElement.md) | Uploads all files defined by the moduleXml
| [ProvisionFileInternal(Web, String, String, Xml.Linq.XElement, Boolean)](Microsoft.SharePoint.Client.ProvisioningExtensions.ProvisionFileInternalWebStringStringXml.Linq.XElementBoolean.md) | Uploads the file defined by the fileXml, creating folders as necessary.
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
