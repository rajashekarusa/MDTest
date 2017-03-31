# ExternalSharingExtensions.ShareSite Method  
Share site for a person using just email. Will resolve needed people picker JSON value automatically.  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  ShareSite(Web web,String email,ExternalSharingSiteOption shareOption,Boolean sendEmail,String emailBody,Boolean useSimplifiedRoles)
```
### Parameters
*web*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.Web](Microsoft.SharePoint.Client.Web.md) 
&emsp;&emsp;  
  
*email*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*shareOption*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ExternalSharingSiteOption](Microsoft.SharePoint.Client.ExternalSharingSiteOption.md) 
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
