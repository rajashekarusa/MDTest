# ExternalSharingExtensions.CreateAnonymousLinkWithExpirationForDocument Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string CreateAnonymousLinkWithExpirationForDocument(Web web,String urlToDocument,ExternalSharingDocumentOption shareOption,DateTime expireTime)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*urlToDocument*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*shareOption*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ExternalSharingDocumentOption](Microsoft.SharePoint.Client.ExternalSharingDocumentOption.md) 
&emsp;&emsp;  
  
*expireTime*  
&emsp;&emsp;Type: [System.DateTime](System.DateTime.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.String](System.String.md)  
Anonymous URL to the file as string

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
