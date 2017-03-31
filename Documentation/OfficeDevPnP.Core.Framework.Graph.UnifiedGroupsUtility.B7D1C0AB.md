String, String, String, String, String[], String[], Stream, Boolean, Int32, Int32# UnifiedGroupsUtility.CreateUnifiedGroup members
Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateUnifiedGroup(String, String, String, String, String[], String[], Stream, Boolean, Int32, Int32)
```
### Parameters
#### displayName
Type: [System.String](System.String.md) 
#### 
#### description
Type: [System.String](System.String.md) 
#### 
#### mailNickname
Type: [System.String](System.String.md) 
#### 
#### accessToken
Type: [System.String](System.String.md) 
#### 
#### (optional) owners
Type: [System.String[]](System.String[].md) 
#### 
#### (optional) members
Type: [System.String[]](System.String[].md) 
#### 
#### (optional) groupLogo
Type: [System.IO.Stream](System.IO.Stream.md) 
#### 
#### (optional) isPrivate
Type: [System.Boolean](System.Boolean.md) 
#### 
#### (optional) retryCount
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) delay
Type: [System.Int32](System.Int32.md) 
#### 
### Return Value
Type: [OfficeDevPnP.Core.Entities.UnifiedGroupEntity](OfficeDevPnP.Core.Entities.UnifiedGroupEntity.md)The just created Office 365 Group
## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
