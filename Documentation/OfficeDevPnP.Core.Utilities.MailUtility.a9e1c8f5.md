# MailUtility.SendEmail Method  
  

**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SendEmail(String servername, String fromAddress, SecureString fromUserPassword, IEnumerable<String> to, IEnumerable<String> cc, String subject, String body, Boolean sendAsync, Object asyncUserToken)
```
### Parameters
*servername*  
&emsp;&emsp;Type: System.String  
*fromAddress*  
&emsp;&emsp;Type: System.String  
*fromUserPassword*  
&emsp;&emsp;Type: System.Security.SecureString  
*to*  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<System.String>  
*cc*  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<System.String>  
*subject*  
&emsp;&emsp;Type: System.String  
*body*  
&emsp;&emsp;Type: System.String  
*(optional) sendAsync*  
&emsp;&emsp;Type: System.Boolean  
*(optional) asyncUserToken*  
&emsp;&emsp;Type: System.Object  
### Return Value
Type: void  

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
