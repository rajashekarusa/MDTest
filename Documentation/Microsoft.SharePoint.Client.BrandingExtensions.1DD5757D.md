Web, String, String# BrandingExtensions.UploadThemeFile members
Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery 
            (usually only exists in the root web of a site collection).  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadThemeFile(Web, String, String)
```
### Parameters
#### web
Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
#### 
#### localFilePath
Type: [System.String](System.String.md) 
#### 
#### (optional) themeFolderVersion
Type: [System.String](System.String.md) 
#### 
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)The uploaded file, with at least the ServerRelativeUrl property available
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
