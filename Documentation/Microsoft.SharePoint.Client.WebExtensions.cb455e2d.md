# WebExtensions.UninstallSolution Method  
Uninstalls a sandbox solution package (.WSP) file  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void UninstallSolution(Site site,Guid packageGuid,String fileName,Int32 majorVersion,Int32 minorVersion)
```
### Parameters
*site*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Site](Microsoft.SharePoint.Client.Site.md) 
&emsp;&emsp;  
  
*packageGuid*  
&emsp;&emsp;Type: [System.Guid](System.Guid.md) 
&emsp;&emsp;  
  
*fileName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) majorVersion*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) minorVersion*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Void](System.Void.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
