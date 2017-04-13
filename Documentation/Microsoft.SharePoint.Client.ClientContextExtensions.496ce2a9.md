# ClientContextExtensions.Clone Method  
 Clones a ClientContext object while "taking over" the security context of the existing ClientContext instance   

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static ClientContext Clone(ClientRuntimeContext clientContext, String siteUrl)
```
### Parameters
#### clientContext  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.ClientRuntimeContext  
&emsp;&emsp;ClientContext to be cloned  

  

#### siteUrl  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Site url to be used for cloned ClientContext  

  

### Return Value
Type: ClientContext  
A ClientContext object created for the passed site url  


## Remarks
  
## See also
- [ClientContextExtensions](Microsoft.SharePoint.Client.ClientContextExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 
