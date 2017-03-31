# YammerUtility.CreateYammerGroupDiscussionPartXml Method  
Constructs the webpart XML for yammer group needed to inject as Yammer web part to SharePoint page  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static string CreateYammerGroupDiscussionPartXml(String yammerNetworkName,Int32 yammerGroupId,Boolean showHeader,Boolean showFooter,Boolean useSSO)
```
### Parameters
*yammerNetworkName*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*yammerGroupId*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*showHeader*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*showFooter*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
*(optional) useSSO*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [System.String](System.String.md)  
The constructed web part XML

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
