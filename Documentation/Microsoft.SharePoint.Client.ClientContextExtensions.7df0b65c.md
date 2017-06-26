# ClientContextExtensions.ExecuteQueryRetry Method  
 Executes the current set of data retrieval queries and method invocations and retries it if needed.   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void ExecuteQueryRetry(this ClientRuntimeContext clientContext, Int32 retryCount = 10, Int32 delay = 500)
```
### Parameters
#### clientContext  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ClientRuntimeContext  
&emsp;&emsp;clientContext to operate on  

  

#### (optional) retryCount  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Number of times to retry the request  

  

#### (optional) delay  
&emsp;&emsp;Type: System.Int32  
&emsp;&emsp;Milliseconds to wait before retrying the request. The delay will be increased (doubled) every retry  

  

### Return Value
Type: void  

## See also
- [ClientContextExtensions](Microsoft.SharePoint.Client.ClientContextExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
