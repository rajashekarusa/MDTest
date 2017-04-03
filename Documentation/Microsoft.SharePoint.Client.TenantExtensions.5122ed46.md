# TenantExtensions.CreateSiteCollection Method  
**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid CreateSiteCollection(Tenant tenant,String siteFullUrl,String title,String siteOwnerLogin,String template,Int32 storageMaximumLevel,Int32 storageWarningLevel,Int32 timeZoneId,Int32 userCodeMaximumLevel,Int32 userCodeWarningLevel,UInt32 lcid,Boolean removeFromRecycleBin,Boolean wait,Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
&emsp;&emsp;  
  
*siteFullUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*title*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*siteOwnerLogin*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*template*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*storageMaximumLevel*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
*storageWarningLevel*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
*timeZoneId*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
*userCodeMaximumLevel*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
*userCodeWarningLevel*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;  
  
*lcid*  
&emsp;&emsp;Type: System.UInt32  
&emsp;&emsp;  
  
*(optional) removeFromRecycleBin*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) wait*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage,System.Boolean>  
&emsp;&emsp;  
  
### Return Value
Type: [System.Guid]  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
