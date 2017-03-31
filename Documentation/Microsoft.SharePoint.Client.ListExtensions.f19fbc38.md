# ListExtensions.AddRemoteEventReceiver Method  
Registers a remote event receiver  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  AddRemoteEventReceiver(List list,String name,String url,EventReceiverType eventReceiverType,EventReceiverSynchronization synchronization,Int32 sequenceNumber,Boolean force)
```
### Parameters
*list*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.List](Microsoft.SharePoint.Client.List.md) 
&emsp;&emsp;  
  
*name*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*url*  
&emsp;&emsp;Type: [System.String](System.String.md) 
&emsp;&emsp;  
  
*eventReceiverType*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.EventReceiverType](Microsoft.SharePoint.Client.EventReceiverType.md) 
&emsp;&emsp;  
  
*synchronization*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.EventReceiverSynchronization](Microsoft.SharePoint.Client.EventReceiverSynchronization.md) 
&emsp;&emsp;  
  
*sequenceNumber*  
&emsp;&emsp;Type: [System.Int32](System.Int32.md) 
&emsp;&emsp;  
  
*force*  
&emsp;&emsp;Type: [System.Boolean](System.Boolean.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.EventReceiverDefinition](Microsoft.SharePoint.Client.EventReceiverDefinition.md  
)Returns an EventReceiverDefinition if succeeded. Returns null if failed.

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
