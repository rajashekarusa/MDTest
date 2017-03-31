# ClientContextExtensions.Clone Method  
Clones a ClientContext object while "taking over" the security context of the existing ClientContext instance  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static  Clone(ClientRuntimeContext clientContext,Uri siteUrl)
```
### Parameters
*clientContext*  
&emsp;&emsp;Type: [Microsoft.SharePoint.Client.ClientRuntimeContext](Microsoft.SharePoint.Client.ClientRuntimeContext.md) 
&emsp;&emsp;  
  
*siteUrl*  
&emsp;&emsp;Type: [System.Uri](System.Uri.md) 
&emsp;&emsp;  
  
### Return Value
Type: [Microsoft.SharePoint.Client.ClientContext](Microsoft.SharePoint.Client.ClientContext.md  
)A ClientContext object created for the passed site url

## See also
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)
