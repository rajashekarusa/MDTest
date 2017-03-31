# UnifiedGroupsUtility.UpdateUnifiedGroup Method  
Updates the logo, members or visibility state of an Office 365 Group  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static boolean UpdateUnifiedGroup(String groupId,String accessToken,Int32 retryCount,Int32 delay,String displayName,String description,String[] owners,String[] members,Stream groupLogo,Boolean isPrivate)
```
### Parameters
*groupId*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*accessToken*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) retryCount*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) delay*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*(optional) displayName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) description*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*(optional) owners*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*(optional) members*  
&emsp;&emsp;Type: [System.String[]](System.String[].md) 
&emsp;&emsp;  
  
*(optional) groupLogo*  
&emsp;&emsp;Type: [System.IO.Stream](System.IO.Stream.md) 
&emsp;&emsp;  
  
*(optional) isPrivate*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.Boolean](System.Boolean.md 
)Declares whether the Office 365 Group has been updated or not

## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
