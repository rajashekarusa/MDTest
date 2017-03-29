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
| [ApproveFile(Web, String, String)](Microsoft.SharePoint.Client.FileFolderExtensions.ApproveFileWebStringString.md) | Approves a file
| [CheckInFile(Web, String, CheckinType, String)](Microsoft.SharePoint.Client.FileFolderExtensions.CheckInFileWebStringCheckinTypeString.md) | Checks in a file
| [CheckOutFile(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.CheckOutFileWebString.md) | Checks out a file
| [CopyStream(IO.Stream, IO.Stream)](Microsoft.SharePoint.Client.FileFolderExtensions.CopyStreamIO.StreamIO.Stream.md) | 
| [CreateDocumentSet(Folder, String, ContentTypeId)](Microsoft.SharePoint.Client.FileFolderExtensions.CreateDocumentSetFolderStringContentTypeId.md) | Creates a new document set as a child of an existing folder, with the specified content type ID.
| [ConvertFolderToDocumentSet(List, String)](Microsoft.SharePoint.Client.FileFolderExtensions.ConvertFolderToDocumentSetListString.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSet(List, Folder)](Microsoft.SharePoint.Client.FileFolderExtensions.ConvertFolderToDocumentSetListFolder.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSetImplementation(List, Folder)](Microsoft.SharePoint.Client.FileFolderExtensions.ConvertFolderToDocumentSetImplementationListFolder.md) | Internal implementation of the Folder conversion to Document set
| [CreateFolder(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.CreateFolderWebString.md) | Creates a folder with the given name as a child of the Web. Note it is more common to create folders within an existing Folder, such as the RootFolder of a List.
| [CreateFolder(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.CreateFolderFolderString.md) | Creates a folder with the given name.
| [CreateFolderImplementation(FolderCollection, String, Folder, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.CreateFolderImplementationFolderCollectionStringFolderLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [DoesFolderExists(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.DoesFolderExistsWebString.md) | Checks if a specific folder exists
| [EnsureFolder(Web, Folder, String, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.EnsureFolderWebFolderStringLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [EnsureFolder(Web, String, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.EnsureFolderWebStringLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [EnsureFolder(Folder, String, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.EnsureFolderFolderStringLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [EnsureFolderImplementation(FolderCollection, String, Folder, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.EnsureFolderImplementationFolderCollectionStringFolderLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [EnsureFolderPath(Web, String, Linq.Expressions.Expression<Func<Folder,Object>>[])](Microsoft.SharePoint.Client.FileFolderExtensions.EnsureFolderPathWebStringLinq.Expressions.Expression<Func<Folder,Object>>[].md) | 
| [FindFiles(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FindFilesWebString.md) | Finds files in the web. Can be slow.
| [FindFiles(List, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FindFilesListString.md) | Find files in the list, Can be slow.
| [FindFiles(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FindFilesFolderString.md) | Find files in a specific folder
| [FolderExists(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FolderExistsWebString.md) | Checks if the folder exists at the top level of the web site.
| [FolderExists(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FolderExistsFolderString.md) | Checks if the subfolder exists.
| [FolderExistsImplementation(FolderCollection, String)](Microsoft.SharePoint.Client.FileFolderExtensions.FolderExistsImplementationFolderCollectionString.md) | 
| [GetFileAsString(Web, String)](Microsoft.SharePoint.Client.FileFolderExtensions.GetFileAsStringWebString.md) | Returns a file as string
| [ParseFiles(Folder, String, ClientContext, Collections.Generic.List<File>&)](Microsoft.SharePoint.Client.FileFolderExtensions.ParseFilesFolderStringClientContextCollections.Generic.List<File>&.md) | 
| [PublishFile(Web, String, String)](Microsoft.SharePoint.Client.FileFolderExtensions.PublishFileWebStringString.md) | Publishes a file existing on a server url
| [ResolveSubFolder(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.ResolveSubFolderFolderString.md) | 
| [SaveFileToLocal(Web, String, String, String, Func<String,Boolean>)](Microsoft.SharePoint.Client.FileFolderExtensions.SaveFileToLocalWebStringStringStringFunc<String,Boolean>.md) | 
| [UploadFile(Folder, String, String, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.UploadFileFolderStringStringBoolean.md) | Uploads a file to the specified folder.
| [UploadFile(Folder, String, IO.Stream, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.UploadFileFolderStringIO.StreamBoolean.md) | Uploads a file to the specified folder.
| [UploadFileWebDav(Folder, String, String, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.UploadFileWebDavFolderStringStringBoolean.md) | Uploads a file to the specified folder by saving the binary directly (via webdav).
| [UploadFileWebDav(Folder, String, IO.Stream, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.UploadFileWebDavFolderStringIO.StreamBoolean.md) | Uploads a file to the specified folder by saving the binary directly (via webdav). Note: this method does not work using app only token.
| [GetFile(Folder, String)](Microsoft.SharePoint.Client.FileFolderExtensions.GetFileFolderString.md) | Gets a file in a document library.
| [VerifyIfUploadRequired(File, String)](Microsoft.SharePoint.Client.FileFolderExtensions.VerifyIfUploadRequiredFileString.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [VerifyIfUploadRequired(File, IO.Stream)](Microsoft.SharePoint.Client.FileFolderExtensions.VerifyIfUploadRequiredFileIO.Stream.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [SetFileProperties(File, Collections.Generic.IDictionary<String,String>, Boolean)](Microsoft.SharePoint.Client.FileFolderExtensions.SetFilePropertiesFileCollections.Generic.IDictionary<String,String>Boolean.md) | 
| [PublishFileToLevel(File, FileLevel)](Microsoft.SharePoint.Client.FileFolderExtensions.PublishFileToLevelFileFileLevel.md) | Publishes a file based on the type of versioning required on the parent library.
| [WildcardToRegex(String)](Microsoft.SharePoint.Client.FileFolderExtensions.WildcardToRegexString.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
