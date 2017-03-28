# FileFolderExtensions
Class that holds the deprecated file and folder methods  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Classes
System.Object  
## Syntax
```C#
public class FileFolderExtensions
```
## Methods
|**Name**|**Description**|
|:-----|:-----|
| [ApproveFile(Web, String, String)](FileFolderExtensionsApproveFileWebStringString.md) | Approves a file
| [CheckInFile(Web, String, CheckinType, String)](FileFolderExtensionsCheckInFileWebStringCheckinTypeString.md) | Checks in a file
| [CheckOutFile(Web, String)](FileFolderExtensionsCheckOutFileWebString.md) | Checks out a file
| [CopyStream(IO.Stream, IO.Stream)](FileFolderExtensionsCopyStreamIO.StreamIO.Stream.md) | 
| [CreateDocumentSet(Folder, String, ContentTypeId)](FileFolderExtensionsCreateDocumentSetFolderStringContentTypeId.md) | Creates a new document set as a child of an existing folder, with the specified content type ID.
| [ConvertFolderToDocumentSet(List, String)](FileFolderExtensionsConvertFolderToDocumentSetListString.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSet(List, Folder)](FileFolderExtensionsConvertFolderToDocumentSetListFolder.md) | Converts a folder with the given name as a child of the List RootFolder.
| [ConvertFolderToDocumentSetImplementation(List, Folder)](FileFolderExtensionsConvertFolderToDocumentSetImplementationListFolder.md) | Internal implementation of the Folder conversion to Document set
| [CreateFolder(Web, String)](FileFolderExtensionsCreateFolderWebString.md) | Creates a folder with the given name as a child of the Web. Note it is more common to create folders within an existing Folder, such as the RootFolder of a List.
| [CreateFolder(Folder, String)](FileFolderExtensionsCreateFolderFolderString.md) | Creates a folder with the given name.
| [CreateFolderImplementation(FolderCollection, String, Folder, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsCreateFolderImplementationFolderCollectionStringFolderLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [DoesFolderExists(Web, String)](FileFolderExtensionsDoesFolderExistsWebString.md) | Checks if a specific folder exists
| [EnsureFolder(Web, Folder, String, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsEnsureFolderWebFolderStringLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [EnsureFolder(Web, String, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsEnsureFolderWebStringLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [EnsureFolder(Folder, String, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsEnsureFolderFolderStringLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [EnsureFolderImplementation(FolderCollection, String, Folder, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsEnsureFolderImplementationFolderCollectionStringFolderLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [EnsureFolderPath(Web, String, Linq.Expressions.Expression1<Func2<Folder,Object>>[])](FileFolderExtensionsEnsureFolderPathWebStringLinq.Expressions.Expression1<Func2<Folder,Object>>[].md) | 
| [FindFiles(Web, String)](FileFolderExtensionsFindFilesWebString.md) | Finds files in the web. Can be slow.
| [FindFiles(List, String)](FileFolderExtensionsFindFilesListString.md) | Find files in the list, Can be slow.
| [FindFiles(Folder, String)](FileFolderExtensionsFindFilesFolderString.md) | Find files in a specific folder
| [FolderExists(Web, String)](FileFolderExtensionsFolderExistsWebString.md) | Checks if the folder exists at the top level of the web site.
| [FolderExists(Folder, String)](FileFolderExtensionsFolderExistsFolderString.md) | Checks if the subfolder exists.
| [FolderExistsImplementation(FolderCollection, String)](FileFolderExtensionsFolderExistsImplementationFolderCollectionString.md) | 
| [GetFileAsString(Web, String)](FileFolderExtensionsGetFileAsStringWebString.md) | Returns a file as string
| [ParseFiles(Folder, String, ClientContext, Collections.Generic.List1<File>&)](FileFolderExtensionsParseFilesFolderStringClientContextCollections.Generic.List1<File>&.md) | 
| [PublishFile(Web, String, String)](FileFolderExtensionsPublishFileWebStringString.md) | Publishes a file existing on a server url
| [ResolveSubFolder(Folder, String)](FileFolderExtensionsResolveSubFolderFolderString.md) | 
| [SaveFileToLocal(Web, String, String, String, Func2<String,Boolean>)](FileFolderExtensionsSaveFileToLocalWebStringStringStringFunc2<String,Boolean>.md) | 
| [UploadFile(Folder, String, String, Boolean)](FileFolderExtensionsUploadFileFolderStringStringBoolean.md) | Uploads a file to the specified folder.
| [UploadFile(Folder, String, IO.Stream, Boolean)](FileFolderExtensionsUploadFileFolderStringIO.StreamBoolean.md) | Uploads a file to the specified folder.
| [UploadFileWebDav(Folder, String, String, Boolean)](FileFolderExtensionsUploadFileWebDavFolderStringStringBoolean.md) | Uploads a file to the specified folder by saving the binary directly (via webdav).
| [UploadFileWebDav(Folder, String, IO.Stream, Boolean)](FileFolderExtensionsUploadFileWebDavFolderStringIO.StreamBoolean.md) | Uploads a file to the specified folder by saving the binary directly (via webdav). Note: this method does not work using app only token.
| [GetFile(Folder, String)](FileFolderExtensionsGetFileFolderString.md) | Gets a file in a document library.
| [VerifyIfUploadRequired(File, String)](FileFolderExtensionsVerifyIfUploadRequiredFileString.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [VerifyIfUploadRequired(File, IO.Stream)](FileFolderExtensionsVerifyIfUploadRequiredFileIO.Stream.md) | Used to compare the server file to the local file. This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.
| [SetFileProperties(File, Collections.Generic.IDictionary2<String,String>, Boolean)](FileFolderExtensionsSetFilePropertiesFileCollections.Generic.IDictionary2<String,String>Boolean.md) | 
| [PublishFileToLevel(File, FileLevel)](FileFolderExtensionsPublishFileToLevelFileFileLevel.md) | Publishes a file based on the type of versioning required on the parent library.
| [WildcardToRegex(String)](FileFolderExtensionsWildcardToRegexString.md) | 
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
