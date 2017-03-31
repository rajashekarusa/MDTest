# FileFolderExtensions
Class that holds the deprecated file and folder methods  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Inheritance Hierarchy
System.Object  
## Syntax
```C#
public static class FileFolderExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ApproveFile(Web, String, String)](Microsoft.SharePoint.Client.FileFolderExtensions.AB86A84B.md) | Approves a file
| [CheckInFile(Web, String, CheckinType, String)](Microsoft.SharePoint.Client.FileFolderExtensions.C0C23A8A.md) | Checks in a file
| [CheckOutFile(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.777298BA.md) | Checks out a file
| [CopyStream(Stream, Stream)](Microsoft.SharePoint.Client.FileFolderExtensions.9309F1.md) | 
| [CreateDocumentSet(Folder, String, ContentTypeId)](Microsoft.SharePoint.Client.FileFolderExtensions.CCEEB4A1.md) | Creates a new document set as a child of an existing folder, with the specified content type ID.
| [ConvertFolderToDocumentSet(List, String)](Microsoft.SharePoint.Client.FileFolderExtensions.B1EE8B29.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSet(List, Folder)](Microsoft.SharePoint.Client.FileFolderExtensions.19B00AC7.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSetImplementation(List, Folder)](Microsoft.SharePoint.Client.FileFolderExtensions.E24FD41A.md) | Internal implementation of the Folder conversion to Document set
| [CreateFolder(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.5A3CBD57.md) | Creates a folder with the given name as a child of the Web. Note it is more common to create folders within an existing Folder, such as the RootFolder of a List.
| [CreateFolder(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.2D34EDC8.md) | Creates a folder with the given name.
| [CreateFolderImplementation(FolderCollection, String, Folder, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.38845A52.md) | 
| [DoesFolderExists(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.F242FF96.md) | Checks if a specific folder exists
| [EnsureFolder(Web, Folder, String, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.FF1BC66D.md) | 
| [EnsureFolder(Web, String, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.F0AF8F8.md) | 
| [EnsureFolder(Folder, String, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.CB4683A9.md) | 
| [EnsureFolderImplementation(FolderCollection, String, Folder, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.5D1DDEAD.md) | 
| [EnsureFolderPath(Web, String, Expression<Func<Folder, Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.35B06E1C.md) | 
| [FindFiles(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.9355C7CA.md) | Finds files in the web. Can be slow.
| [FindFiles(List, String)](Microsoft.SharePoint.Client.FileFolderExtensions.610D4135.md) | Find files in the list, Can be slow.
| [FindFiles(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.D977F1FA.md) | Find files in a specific folder
| [FolderExists(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.E44BE55D.md) | Checks if the folder exists at the top level of the web site.
| [FolderExists(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.D7370E83.md) | Checks if the subfolder exists.
| [FolderExistsImplementation(FolderCollection, String)](Microsoft.SharePoint.Client.FileFolderExtensions.3A055058.md) | 
| [GetFileAsString(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.CCCF4E5B.md) | Returns a file as string
| [ParseFiles(Folder, String, ClientContext, List<File>&)](Microsoft.SharePoint.Client.FileFolderExtensions.BC4B9FC6.md) | 
| [PublishFile(Web, String, String)](Microsoft.SharePoint.Client.FileFolderExtensions.1C9A167D.md) | Publishes a file existing on a server url
| [ResolveSubFolder(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.228E8E66.md) | 
| [SaveFileToLocal(Web, String, String, String, Func<String, Boolean>)](Microsoft.SharePoint.Client.FileFolderExtensions.B94118AD.md) | 
| [UploadFile(Folder, String, String, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.4188915.md) | Uploads a file to the specified folder.
| [UploadFile(Folder, String, Stream, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.203708BC.md) | Uploads a file to the specified folder.
| [UploadFileWebDav(Folder, String, String, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.49DC7CAD.md) | Uploads a file to the specified folder by saving the binary directly (via webdav).
| [UploadFileWebDav(Folder, String, Stream, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.2A46B076.md) | Uploads a file to the specified folder by saving the binary directly (via webdav). Note: this method does not work using app only token.
| [GetFile(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.68F7E2CB.md) | Gets a file in a document library.
| [VerifyIfUploadRequired(File, String)](Microsoft.SharePoint.Client.FileFolderExtensions.D0DE8DE0.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [VerifyIfUploadRequired(File, Stream)](Microsoft.SharePoint.Client.FileFolderExtensions.16CBA753.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [SetFileProperties(File, IDictionary<String, String>, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.DC97957.md) | 
| [PublishFileToLevel(File, FileLevel)](Microsoft.SharePoint.Client.FileFolderExtensions.BE85F58D.md) | Publishes a file based on the type of versioning required on the parent library.
| [WildcardToRegex(String)](Microsoft.SharePoint.Client.FileFolderExtensions.A210465E.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
