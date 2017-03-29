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
| [PnPPackage()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.Constructor1details.md) | 
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
| [Open(String, IO.FileMode, IO.FileAccess)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.OpenStringIO.FileModeIO.FileAccess.md) | 
| [Open(IO.Stream, IO.FileMode, IO.FileAccess)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.OpenIO.StreamIO.FileModeIO.FileAccess.md) | 
| [AddFile(String, Byte[])](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.AddFileStringByte[].md) | 
| [ClearFiles()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ClearFiles.md) | 
| [EnsureMandatoryPackageComponents()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.EnsureMandatoryPackageComponents.md) | 
| [EnsurePackagePartWithRelationshipType(String, String, String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.EnsurePackagePartWithRelationshipTypeStringStringStringIO.Packaging.PackagePart.md) | 
| [EnsurePackagePartWithUri(String, String, String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.EnsurePackagePartWithUriStringStringStringIO.Packaging.PackagePart.md) | 
| [GetSinglePackagePartWithRelationshipType(String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.GetSinglePackagePartWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [GetAllPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.GetAllPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [GetXamlSerializedPackagePartValue(IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.GetXamlSerializedPackagePartValueIO.Packaging.PackagePart.md) | 
| [SetXamlSerializedPackagePartValue(Object, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.SetXamlSerializedPackagePartValueObjectIO.Packaging.PackagePart.md) | 
| [SetPackagePartValue(Byte[], IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.SetPackagePartValueByte[]IO.Packaging.PackagePart.md) | 
| [CreatePackagePart(String, String, String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.CreatePackagePartStringStringStringIO.Packaging.PackagePart.md) | 
| [ClearPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ClearPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [ClearPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart, String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ClearPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePartString.md) | 
| [ReadPackagePartListBytes(Collections.Generic.List<IO.Packaging.PackagePart>)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ReadPackagePartListBytesCollections.Generic.List<IO.Packaging.PackagePart>.md) | 
| [ReadPackagePartBytes(IO.Packaging.PackagePart)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.ReadPackagePartBytesIO.Packaging.PackagePart.md) | 
| [GetUri(String)](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.GetUriString.md) | 
| [System.IDisposable.Dispose()](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.PnPPackage.System.IDisposable.Dispose.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.md)
