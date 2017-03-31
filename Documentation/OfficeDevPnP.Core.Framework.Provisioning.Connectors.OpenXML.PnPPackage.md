# PnPPackage
Defines a PnP OpenXML package file  

**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public class PnPPackage
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [PnPPackage()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ctor1.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Package](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.Package.md) | 
| [ManifestPart](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ManifestPart.md) | The Manifest Part of the package file
| [Manifest](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.Manifest.md) | The Manifest of the package file
| [Properties](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.Properties.md) | The Properties of the package
| [FilesMap](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.FilesMap.md) | The File Map for files stored in the OpenXML file
| [FilesOriginPart](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.FilesOriginPart.md) | The Files origin
| [FilesPackageParts](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.FilesPackageParts.md) | The Files Parts of the package
| [Files](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.Files.md) | The Files of the package
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Open(String, FileMode, FileAccess)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.423B4A84.md) | 
| [Open(Stream, FileMode, FileAccess)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.FA8E8F48.md) | 
| [AddFile(String, Byte[])](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.C1F2E4E7.md) | 
| [ClearFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.8277AC85.md) | 
| [EnsureMandatoryPackageComponents()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.4CE2D421.md) | 
| [EnsurePackagePartWithRelationshipType(String, String, String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.70129E21.md) | 
| [EnsurePackagePartWithUri(String, String, String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.BD03CB5F.md) | 
| [GetSinglePackagePartWithRelationshipType(String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.D3012DF4.md) | 
| [GetAllPackagePartsWithRelationshipType(String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.992A36DC.md) | 
| [GetXamlSerializedPackagePartValue(PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.E370C833.md) | 
| [SetXamlSerializedPackagePartValue(Object, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.5ED4D80C.md) | 
| [SetPackagePartValue(Byte[], PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.9B48F3DF.md) | 
| [CreatePackagePart(String, String, String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.AFEC24C.md) | 
| [ClearPackagePartsWithRelationshipType(String, PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.D1881D5E.md) | 
| [ClearPackagePartsWithRelationshipType(String, PackagePart, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.C2C3D69E.md) | 
| [ReadPackagePartListBytes(List<PackagePart>)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.44933D7D.md) | 
| [ReadPackagePartBytes(PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.95ADB267.md) | 
| [GetUri(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.F2E524C1.md) | 
| [System.IDisposable.Dispose()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.FCEAD813.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.md)
