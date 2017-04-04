# TenantExtensions.GetWebTemplates Method  
Returns available webtemplates/site definitions  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static Microsoft.Online.SharePoint.TenantAdministration.SPOTenantWebTemplateCollection GetWebTemplates(Tenant tenant, UInt32 lcid, Int32 compatibilityLevel)
```
### Parameters
*tenant*  
&emsp;&emsp;Type: Microsoft.Online.SharePoint.TenantAdministration.Tenant  
&emsp;&emsp;A tenant object pointing to the context of a Tenant Administration site  
  
*lcid*  
&emsp;&emsp;Type: System.UInt32  
&emsp;&emsp;  
  
*compatibilityLevel*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;14 for SharePoint 2010, 15 for SharePoint 2013/SharePoint Online  
  
### Return Value
Type: Microsoft.Online.SharePoint.TenantAdministration.SPOTenantWebTemplateCollection  


## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
