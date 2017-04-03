# FileFolderExtensions.SaveFileToLocal Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SaveFileToLocal(Web web,String serverRelativeUrl,String localPath,String localFileName,Func<String, Boolean> fileExistsCallBack)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;  
  
*serverRelativeUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*localPath*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*(optional) localFileName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*(optional) fileExistsCallBack*  
&emsp;&emsp;Type: System.Func<System.String,System.Boolean>  
&emsp;&emsp;  
  
### Return Value
Type: [System.Void]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
