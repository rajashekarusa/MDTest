# UnifiedGroupsUtility.ListUnifiedGroups Method  
Returns all the Office 365 Groups in the current Tenant based on a startIndex. IncludeSite adds additional properties about the Modern SharePoint Site backing the group  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<officedevpnp.core.entities.unifiedgroupentity> ListUnifiedGroups(String accessToken,String displayName,String mailNickname,Int32 startIndex,Int32 endIndex,Boolean includeSite,Int32 retryCount,Int32 delay)
```
### Parameters
*accessToken*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) displayName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) mailNickname*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) startIndex*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) endIndex*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) includeSite*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) retryCount*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) delay*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.UnifiedGroupEntity>](System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.UnifiedGroupEntity>.md)  
An IList of SiteEntity objects

## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
