# FileFolderExtensions.VerifyIfUploadRequired Method  
Used to compare the server file to the local file.
            This enables users with faster download speeds but slow upload speeds to evaluate if the server file should be overwritten.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean VerifyIfUploadRequired(File serverFile,String localFile)
```
### Parameters
*serverFile*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.File](Microsoft.SharePoint.Client.File.md) 
&emsp;&emsp;  
  
*localFile*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md 
)
## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)