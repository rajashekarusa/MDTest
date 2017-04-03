# YammerUtility.CreateYammerDiscussionPartXml Method  
Constructs the webpart XML for yammer group needed to inject as Yammer web part to SharePoint page  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string CreateYammerDiscussionPartXml(String yammerNetworkName,Int32 yammerGroupId,Boolean showHeader,Boolean showFooter,Boolean useSSO)
```
### Parameters
*yammerNetworkName*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Name of the network  
  
*yammerGroupId*  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Group ID  
  
*showHeader*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*showFooter*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) useSSO*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
### Return Value
Type: [System.String]  
The constructed web part XML

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
