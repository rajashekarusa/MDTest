# PnPPackage
Defines a PnP OpenXML package file
**Namespace:** [OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.md)
**Assembly:** OfficeDevPnP.Core.dll
## Classes
System.Object
## Syntax
```C#
public class PnPPackage
```
## Constructors
|**Name**|**Description**|
|:-----|:-----|
| [PnPPackage()](PnPPackageconstructor1details.md) | 
## Properties
|**Name**|**Description**|
|:-----|:-----|
| [Package](PnPPackage.Package.md) | 
| [ManifestPart](PnPPackage.ManifestPart.md) | The Manifest Part of the package file
| [Manifest](PnPPackage.Manifest.md) | The Manifest of the package file
| [Properties](PnPPackage.Properties.md) | The Properties of the package
| [FilesMap](PnPPackage.FilesMap.md) | The File Map for files stored in the OpenXML file
| [FilesOriginPart](PnPPackage.FilesOriginPart.md) | The Files origin
| [FilesPackageParts](PnPPackage.FilesPackageParts.md) | The Files Parts of the package
| [Files](PnPPackage.Files.md) | The Files of the package
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [Open(String, IO.FileMode, IO.FileAccess)](PnPPackageOpenStringIO.FileModeIO.FileAccess.md) | 
| [Open(IO.Stream, IO.FileMode, IO.FileAccess)](PnPPackageOpenIO.StreamIO.FileModeIO.FileAccess.md) | 
| [AddFile(String, Byte[])](PnPPackageAddFileStringByte[].md) | 
| [ClearFiles()](PnPPackageClearFiles.md) | 
| [EnsureMandatoryPackageComponents()](PnPPackageEnsureMandatoryPackageComponents.md) | 
| [EnsurePackagePartWithRelationshipType(String, String, String, IO.Packaging.PackagePart)](PnPPackageEnsurePackagePartWithRelationshipTypeStringStringStringIO.Packaging.PackagePart.md) | 
| [EnsurePackagePartWithUri(String, String, String, IO.Packaging.PackagePart)](PnPPackageEnsurePackagePartWithUriStringStringStringIO.Packaging.PackagePart.md) | 
| [GetSinglePackagePartWithRelationshipType(String, IO.Packaging.PackagePart)](PnPPackageGetSinglePackagePartWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [GetAllPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart)](PnPPackageGetAllPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [GetXamlSerializedPackagePartValue(IO.Packaging.PackagePart)](PnPPackageGetXamlSerializedPackagePartValueIO.Packaging.PackagePart.md) | 
| [SetXamlSerializedPackagePartValue(Object, IO.Packaging.PackagePart)](PnPPackageSetXamlSerializedPackagePartValueObjectIO.Packaging.PackagePart.md) | 
| [SetPackagePartValue(Byte[], IO.Packaging.PackagePart)](PnPPackageSetPackagePartValueByte[]IO.Packaging.PackagePart.md) | 
| [CreatePackagePart(String, String, String, IO.Packaging.PackagePart)](PnPPackageCreatePackagePartStringStringStringIO.Packaging.PackagePart.md) | 
| [ClearPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart)](PnPPackageClearPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePart.md) | 
| [ClearPackagePartsWithRelationshipType(String, IO.Packaging.PackagePart, String)](PnPPackageClearPackagePartsWithRelationshipTypeStringIO.Packaging.PackagePartString.md) | 
| [ReadPackagePartListBytes(Collections.Generic.List1<IO.Packaging.PackagePart>)](PnPPackageReadPackagePartListBytesCollections.Generic.List1<IO.Packaging.PackagePart>.md) | 
| [ReadPackagePartBytes(IO.Packaging.PackagePart)](PnPPackageReadPackagePartBytesIO.Packaging.PackagePart.md) | 
| [GetUri(String)](PnPPackageGetUriString.md) | 
| [System.IDisposable.Dispose()](PnPPackageSystem.IDisposable.Dispose.md) | 
## See also
- [OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML](OfficeDevPnP.Core.Framework.Provisioning.Connectors.OpenXML.md)
