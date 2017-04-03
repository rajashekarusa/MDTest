# BrandingExtensions.UploadThemeFile Method  
Uploads the specified file (usually an spcolor or spfont file) to the web site themes gallery 
            (usually only exists in the root web of a site collection).  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  UploadThemeFile(Web web,String localFilePath,String themeFolderVersion)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web site to upload to  
  
*localFilePath*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Location of the file to be uploaded  
  
*(optional) themeFolderVersion*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Leaf folder name to upload to; default is "15"  
  
### Return Value
Type: [Microsoft.SharePoint.Client.File]  
The uploaded file, with at least the ServerRelativeUrl property available

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)