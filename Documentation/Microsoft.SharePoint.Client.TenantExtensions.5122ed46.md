# TenantExtensions.CreateSiteCollection Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static guid CreateSiteCollection(Tenant tenant, String siteFullUrl, String title, String siteOwnerLogin, String template, Int32 storageMaximumLevel, Int32 storageWarningLevel, Int32 timeZoneId, Int32 userCodeMaximumLevel, Int32 userCodeWarningLevel, UInt32 lcid, Boolean removeFromRecycleBin, Boolean wait, Func<TenantOperationMessage, Boolean> timeoutFunction)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
*siteFullUrl*  
&emsp;&emsp;Type: System.String  
*title*  
&emsp;&emsp;Type: System.String  
*siteOwnerLogin*  
&emsp;&emsp;Type: System.String  
*template*  
&emsp;&emsp;Type: System.String  
*storageMaximumLevel*  
&emsp;&emsp;Type: System.Int32  
*storageWarningLevel*  
&emsp;&emsp;Type: System.Int32  
*timeZoneId*  
&emsp;&emsp;Type: System.Int32  
*userCodeMaximumLevel*  
&emsp;&emsp;Type: System.Int32  
*userCodeWarningLevel*  
&emsp;&emsp;Type: System.Int32  
*lcid*  
&emsp;&emsp;Type: System.UInt32  
*(optional) removeFromRecycleBin*  
&emsp;&emsp;Type: System.Boolean  
*(optional) wait*  
&emsp;&emsp;Type: System.Boolean  
*(optional) timeoutFunction*  
&emsp;&emsp;Type: System.Func<OfficeDevPnP.Core.TenantOperationMessage, System.Boolean>  
### Return Value
Type: System.Guid  

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
