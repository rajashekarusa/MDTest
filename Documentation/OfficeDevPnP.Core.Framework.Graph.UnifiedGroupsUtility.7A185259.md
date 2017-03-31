# UnifiedGroupsUtility.CreateUnifiedGroup Method  
Creates a new Office 365 Group (i.e. Unified Group) with its backing Modern SharePoint Site  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  CreateUnifiedGroup(String displayName,String description,String mailNickname,String accessToken,String[] owners,String[] members,Boolean isPrivate,Int32 retryCount,Int32 delay)
```
### Parameters
*displayName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*description*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*mailNickname*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*accessToken*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) owners*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*(optional) members*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*(optional) isPrivate*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) retryCount*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) delay*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
### Return Value
Type: [OfficeDevPnP.Core.Entities.UnifiedGroupEntity](OfficeDevPnP.Core.Entities.UnifiedGroupEntity.md 
)The just created Office 365 Group

## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
