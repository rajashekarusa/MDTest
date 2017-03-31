# BrandingExtensions.UploadThemeFile Method  
Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery 
            (usually only exists in the root web of a site collection).  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadThemeFile(Web web,String fileName,Stream localStream,String themeFolderVersion)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*fileName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*localStream*  
&emsp;&emsp;Type: [System.IO.Stream](System.IO.Stream.md) 
&emsp;&emsp;  
  
*(optional) themeFolderVersion*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md)  
The uploaded file, with at least the ServerRelativeUrl property available

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
