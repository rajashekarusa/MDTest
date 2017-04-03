# PublishingExtensions.GetPublishingPage Method  
Gets a Publishing Page from any folder in the Pages library.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  GetPublishingPage(Web web,String fileLeafRef,Folder folder)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;The web.  
  
*fileLeafRef*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The file leaf reference.  
  
*folder*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Folder  
&emsp;&emsp;The folder where to search the page.  
  
### Return Value
Type: [Microsoft.SharePoint.Client.Publishing.PublishingPage]  
The PublishingPage object, if any. Otherwise null.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)