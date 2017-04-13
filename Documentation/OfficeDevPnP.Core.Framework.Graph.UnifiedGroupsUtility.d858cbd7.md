# UnifiedGroupsUtility.GetUnifiedGroupSiteUrl Method  
 Returns the URL of the Modern SharePoint Site backing an Office 365 Group (i.e. Unified Group)   

**Namespace:** [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string GetUnifiedGroupSiteUrl(String groupId, String accessToken, Int32 retryCount, Int32 delay)
```
### Parameters
#### groupId  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The ID of the Office 365 Group  

  

#### accessToken  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;The OAuth 2.0 Access Token to use for invoking the Microsoft Graph  

  

#### (optional) retryCount  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Number of times to retry the request in case of throttling  

  

#### (optional) delay  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Milliseconds to wait before retrying the request. The delay will be increased (doubled) every retry  

  

### Return Value
Type: string  
The URL of the modern site backing the Office 365 Group  


## Remarks
  
## See also
- [UnifiedGroupsUtility](OfficeDevPnP.Core.Framework.Graph.UnifiedGroupsUtility.md) 
- [OfficeDevPnP.Core.Framework.Graph](OfficeDevPnP.Core.Framework.Graph.md) 
