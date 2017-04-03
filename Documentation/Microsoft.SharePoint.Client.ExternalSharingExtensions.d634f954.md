# ExternalSharingExtensions.CreateAnonymousLinkWithExpirationForDocument Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string CreateAnonymousLinkWithExpirationForDocument(Web web,String urlToDocument,ExternalSharingDocumentOption shareOption,DateTime expireTime)
```
### Parameters
*web*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;Web for the context used for people picker search  
  
*urlToDocument*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Full URL to the file which is shared  
  
*shareOption*  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ExternalSharingDocumentOption  
&emsp;&emsp;Type of the link to be created - View or Edit  
  
*expireTime*  
&emsp;&emsp;Type: System.DateTime  
&emsp;&emsp;Date time for link expiration - will be converted to ISO 8601 format automatically  
  
### Return Value
Type: [System.String]  
Anonymous URL to the file as string

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)