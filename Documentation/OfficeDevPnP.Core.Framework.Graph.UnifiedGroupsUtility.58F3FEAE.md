String, String, String, Int32, Int32, Boolean, Int32, Int32# UnifiedGroupsUtility.ListUnifiedGroups members
Returns all the Office 365 Groups in the current Tenant based on a startIndex. IncludeSite adds additional properties about the Modern SharePoint Site backing the group  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static collections.generic.list`1<officedevpnp.core.entities.unifiedgroupentity> ListUnifiedGroups(String, String, String, Int32, Int32, Boolean, Int32, Int32)
```
### Parameters
#### accessToken
Type: [System.String](System.String.md) 
#### 
#### (optional) displayName
Type: [System.String](System.String.md) 
#### 
#### (optional) mailNickname
Type: [System.String](System.String.md) 
#### 
#### (optional) startIndex
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) endIndex
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) includeSite
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) retryCount
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) delay
Type: [System.Int32](System.Int32.md) 
#### 
### Return Value
Type: [System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.UnifiedGroupEntity>](System.Collections.Generic.List`1<OfficeDevPnP.Core.Entities.UnifiedGroupEntity>.md)An IList of SiteEntity objects
## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
