# PnPClientContext.Clone Method  
Clones a PnPClientContext object while "taking over" the security context of the existing PnPClientContext instance  

**Namespace:** [OfficeDevPnP.Core](OfficeDevPnP.Core.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public OfficeDevPnP.Core.PnPClientContext Clone(String siteUrl)
```
### Parameters
*siteUrl*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;Site url to be used for cloned ClientContext  
  
### Return Value
Type: [OfficeDevPnP.Core.PnPClientContext](OfficeDevPnP.Core.PnPClientContext.md)  
A PnPClientContext object created for the passed site url

## See also
- [OfficeDevPnP.Core](OfficeDevPnP.Core.md)
