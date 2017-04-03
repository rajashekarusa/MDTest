# MailUtility.SendEmail Method  
**Namespace:** [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static void SendEmail(String servername,String fromAddress,String fromUserPassword,IEnumerable<String> to,IEnumerable<String> cc,String subject,String body,Boolean sendAsync,Object asyncUserToken)
```
### Parameters
*servername*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*fromAddress*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*fromUserPassword*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*to*  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<System.String>  
&emsp;&emsp;  
  
*cc*  
&emsp;&emsp;Type: System.Collections.Generic.IEnumerable<System.String>  
&emsp;&emsp;  
  
*subject*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*body*  
&emsp;&emsp;Type: System.String  
&emsp;&emsp;  
  
*(optional) sendAsync*  
&emsp;&emsp;Type: System.Boolean  
&emsp;&emsp;  
  
*(optional) asyncUserToken*  
&emsp;&emsp;Type: System.Object  
&emsp;&emsp;  
  
### Return Value
Type: [System.Void]  

## See also
- [OfficeDevPnP.Core.Utilities](OfficeDevPnP.Core.Utilities.md)
