# ExternalSharingExtensions.ShareDocument Method  
Abstracted methid for sharing documents just with given email address.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  ShareDocument(Web web,String urlToDocument,String targetEmailToShare,ExternalSharingDocumentOption shareOption,Boolean sendEmail,String emailBody,Boolean useSimplifiedRoles)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*urlToDocument*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*targetEmailToShare*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*shareOption*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ExternalSharingDocumentOption](Microsoft.SharePoint.Client.ExternalSharingDocumentOption.md) 
&emsp;&emsp;  
  
*(optional) sendEmail*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) emailBody*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) useSimplifiedRoles*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.SharingResult](Microsoft.SharePoint.Client.SharingResult.md)  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
