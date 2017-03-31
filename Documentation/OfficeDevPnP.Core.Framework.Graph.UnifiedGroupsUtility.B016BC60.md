String, String, Int32, Int32, String, String, String[], String[], Stream, Boolean# UnifiedGroupsUtility.UpdateUnifiedGroup members
Updates the logo, members or visibility state of an Office 365 Group  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean UpdateUnifiedGroup(String, String, Int32, Int32, String, String, String[], String[], Stream, Boolean)
```
### Parameters
#### groupId
Type: [System.String](System.String.md) 
#### 
#### accessToken
Type: [System.String](System.String.md) 
#### 
#### (optional) retryCount
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) delay
Type: [System.Int32](System.Int32.md) 
#### 
#### (optional) displayName
Type: [System.String](System.String.md) 
#### 
#### (optional) description
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
### Return Value
Type: [System.Boolean](System.Boolean.md)Declares whether the Office 365 Group has been updated or not
## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
