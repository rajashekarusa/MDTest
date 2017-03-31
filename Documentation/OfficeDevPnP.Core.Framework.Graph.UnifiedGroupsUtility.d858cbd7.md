# UnifiedGroupsUtility.GetUnifiedGroupSiteUrl Method  
Returns the URL of the Modern SharePoint Site backing an Office 365 Group (i.e. Unified Group)  

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string GetUnifiedGroupSiteUrl(String groupId,String accessToken,Int32 retryCount,Int32 delay)
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
  
### Return Value
Type: [System.String](System.String.md  
)The URL of the modern site backing the Office 365 Group

## See also
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)
